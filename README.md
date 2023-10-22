const fs = require('fs')
const path = require('path')

const content = fs.readFileSync(path.resolve(__dirname, 'zmd-with-code.md'), 'utf-8')
// https://regex101.com/r/nIlW1U/6
const PATTERN = /^([A-Za-z \t]*)```([A-Za-z]*)?\n([\s\S]*?)```([A-Za-z \t]*)*$/gm

function findCodeBlocks(block) {
  let matches
  let errors = []
  let blocks = []
  while ((matches = PATTERN.exec(block)) !== null) {
    if (matches.index === PATTERN.lastIndex) {
      PATTERN.lastIndex++ // avoid infinite loops with zero-width matches
    }
    const [ match, prefix, syntax, content, postFix ] = matches
    const lang = syntax || 'none'
    const lineNumber = getLineNumber(block, matches)
    let hasError = false
    /* // debug
    console.log(`prefix: "${prefix}"`)
    console.log(`postFix: "${postFix}"`)
    console.log('syntax:', lang)
    console.log('Content:')
    console.log(content.trim())
    console.log('───────────────────────')
    /** */

    /* Validate code blocks */
    if (prefix && prefix.match(/\S/)) {
      hasError = true
      errors.push({
        line: lineNumber,
        position: matches.index,
        message: `Prefix "${prefix}" not allowed on line ${lineNumber}. Remove it to fix the code block.`,
        block: match
      })
    }
    if (postFix && postFix.match(/\S/)) {
      hasError = true
      const line = lineNumber + (countLines(match) - 1)
      errors.push({
        line,
        position: matches.index + match.length,
        message: `Postfix "${postFix}" not allowed on line ${line}. Remove it to fix the code block.`,
        block: match
      })
    }

    if (!hasError) {
      blocks.push({
        line: lineNumber,
        position: matches.index,
        syntax: lang,
        block: match,
        code: content.trim()
      })
    }
  }

  return {
    errors,
    blocks
  }
}

function countLines(text = '') {
  return text.split('\n').length
}

function getLineNumber(text = '', matches) {
  return countLines(text.substr(0, matches.index))
}

const { blocks, errors } = findCodeBlocks(content)
console.log('blocks') 
console.log(blocks) 
console.log('errors') 
console.log(errors)
