
<!DOCTYPE html><html>
        <head>
        <title>cmsite</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
        <link href="https://fonts.googleapis.com/css?family=Quicksand:300,400,500,700,900" rel="stylesheet">
        <link rel="stylesheet" href="./../cmsimde/static/chimper/fonts/icomoon/style.css">
        <link rel="stylesheet" href="./../cmsimde/static/chimper/css/bootstrap.min.css">
        <link rel="stylesheet" href="./../cmsimde/static/chimper/css/magnific-popup.css">
        <link rel="stylesheet" href="./../cmsimde/static/chimper/css/jquery-ui.css">
        <link rel="stylesheet" href="./../cmsimde/static/chimper/css/owl.carousel.min.css">
        <link rel="stylesheet" href="./../cmsimde/static/chimper/css/owl.theme.default.min.css">
        <link rel="stylesheet" href="./../cmsimde/static/chimper/css/bootstrap-datepicker.css">
        <link rel="stylesheet" href="./../cmsimde/static/chimper/fonts/flaticon/font/flaticon.css">
        <link rel="stylesheet" href="./../cmsimde/static/chimper/css/aos.css">
        <link rel="stylesheet" href="./../cmsimde/static/chimper/css/style.css">
        <link rel="shortcut icon" href="./../cmsimde/static/favicons.png">
        
        <style type='text/css'>
            .site-section {
            background-color: #FFFF;
            padding: 40px 40px;
            }
            body > div > div.dropdown.open {
                display: block;
            }
        </style>
    
        <!-- <script src="./../cmsimde/static/jquery.js"></script> -->
        <!-- <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script> -->
        <script src="../cmsimde/static/chimper/js/jquery-3.3.1.min.js"></script>
        <link rel="stylesheet" href="./../cmsimde/static/tipuesearch/css/normalize.min.css">
        <script src="./../cmsimde/static/tipuesearch/tipuesearch_set.js"></script>
        <script src="tipuesearch_content.js"></script>
        <link rel="stylesheet" href="./../cmsimde/static/tipuesearch/css/tipuesearch.css">
        <script src="./../cmsimde/static/tipuesearch/tipuesearch.js"></script>
        <!-- for Wink3 客製化關閉 -->
        <!--
        <link rel="stylesheet" type="text/css" href="./../cmsimde/static/winkPlayer.css" />
        <script type="text/javascript" src="./../cmsimde/static/winkPlayer.js"></script>
        -->
        <script>
            /* original tipuesearch
            $(document).ready(function() {
                 $('#tipue_search_input').tipuesearch();
            });
            */
            // customed doSearch
            function doSearch() {
                $('#tipue_search_input').tipuesearch({
                    newWindow: true, 
                    minimumLength: 2,
                    wholeWords: false, // for search 中文
                });
            }
            $(document).ready(doSearch);
        </script>
        
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shCore.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushBash.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushDiff.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushJScript.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushJava.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushPython.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushSql.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushHaxe.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushXml.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushPhp.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushPowerShell.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushLua.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushCpp.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushCss.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushCSharp.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushDart.js"></script>
<script type="text/javascript" src="./../cmsimde/static/syntaxhighlighter/shBrushRust.js"></script>
<link type="text/css" rel="stylesheet" href="./../cmsimde/static/syntaxhighlighter/css/shCoreDefault.css"/>
<script type="text/javascript">SyntaxHighlighter.all();</script>
<!-- 暫時不用
<script src="./../cmsimde/static/fengari-web.js"></script>
<script type="text/javascript" src="./../cmsimde/static/Cango-13v08-min.js"></script>
<script type="text/javascript" src="./../cmsimde/static/CangoAxes-4v01-min.js"></script>
<script type="text/javascript" src="./../cmsimde/static/gearUtils-05.js"></script>
-->
<!-- for Brython 暫時不用
<script src="https://scrum-3.github.io/web/brython/brython.js"></script>
<script src="https://scrum-3.github.io/web/brython/brython_stdlib.js"></script>
-->
<style>
img.add_border {
    border: 3px solid blue;
}
</style>

</head>
<body>
<div class='container'><nav>
        
    <div class="site-wrap">

    <div class="site-mobile-menu">
      <div class="site-mobile-menu-header">
        <div class="site-mobile-menu-close mt-3">
          <span class="icon-close2 js-menu-toggle"></span>
        </div>
      </div>
      <div class="site-mobile-menu-body"></div>
    </div>
    
            <header class="site-navbar py-4 bg-white" role="banner">
              <div class="container">
                <div class="row align-items-center">
                <h1>40832244</h1>
                <div class="pl-4">
                    <form>
                    <input type="text" placeholder="Search" name="q" id="tipue_search_input" pattern=".{2,}" title="At least 2 characters" required>
                    </form>
                </div>
                  <!-- <div class="col-11 col-xl-2">
                    <h1 class="mb-0 site-logo"><a href="index.html" class="text-black h2 mb-0">40832244</a></h1> 
                  </div>
                  -->
                  <div class="col-12 col-md-10 d-none d-xl-block">
                    <nav class="site-navigation position-relative text-right" role="navigation">
    <ul class='site-menu js-clone-nav mr-auto d-none d-lg-block'>
                        <li class="active has-children"><a href="index.html">Home</a>
                        <ul class="dropdown">
                            <li><a href="sitemap.html">Site Map</a></li>
                            <li><a href="./../reveal/index.html">reveal</a></li>
                            <li><a href="./../blog/index.html">blog</a></li>
                        </ul>
                      </li>
                     <li><a href='40832244的倉儲.html'>40832244的倉儲</a><li class='has-children'><a href='HW.html'>HW</a><ul class='dropdown'><li class='has-children'><a href='W6.html'>W6</a><ul class='dropdown'><li><a href='零件.html'>零件</a><li><a href='組合.html'>組合</a></li></ul><li><a href='W8.html'>W8</a><li><a href='W10.html'>W10</a><li><a href='W11.html'>W11</a><li><a href='W12.html'>W12</a><li><a href='W13.html'>W13</a><li class='has-children'><a href='w14.html'>w14</a><ul class='dropdown'><li><a href='Sovelspace.html'>Sovelspace</a><li><a href='Onshape.html'>Onshape</a><li><a href='NX.html'>NX</a></li></ul><li><a href='W15.html'>W15</a><li><a href='W16.html'>W16</a><li class='has-children'><a href='期末作業.html'>期末作業</a><ul class='dropdown'><li><a href='解決辦法.html'>解決辦法</a><li><a href='彈珠檯程式碼.html'>彈珠檯程式碼</a></li></li></ul></ul><li class='has-children'><a href='Note.html'>Note</a><ul class='dropdown'><li><a href='編輯子模組(cmsimde).html'>編輯子模組(cmsimde)</a><li><a href='ADD, REMOVE OR CHANGE PASSPHRASE OF AN SSH KEY.html'>ADD, REMOVE OR CHANGE PASSPHRASE OF AN SSH KEY</a><li><a href='Brython 編輯.html'>Brython 編輯</a><li><a href='python筆記.html'>python筆記</a><li><a href='當大型擋案卡住無法上傳時解決辦法.html'>當大型擋案卡住無法上傳時解決辦法</a><li><a href='製作wink影片.html'>製作wink影片</a></li></ul><li><a href='心得總結.html'>心得總結</a></li>
                      </ul>
                </nav>
              </div>
              <div class="d-inline-block d-xl-none ml-md-0 mr-auto py-3" style="position: relative; top: 3px;"><a href="#" class="site-menu-toggle js-menu-toggle text-black"><span class="icon-menu h3"></span></a></div>
              </div>

            </div>
          </div>
          
        </header>
    <div id="tipue_search_content"> <a href='HW.html'>Next</a> >> HW<br /><h1>40832244的倉儲</h1>
<p></p>
<p></p>
<p><img alt="" height="220" src="./../images/貓貓.jpg" width="229"/></p>
<p></p>
<p>40832244的網站 : <a href="https://mdecad2022.github.io/site-40832244-github/content/index.html">https://mdecad2022.github.io/site-40832244-github/content/index.html</a></p>
<p>40832244的倉儲:<a href="https://github.com/mdecad2022/site-40832244-github">https://github.com/mdecad2022/site-40832244-github</a></p>
<p>cmsite(課程倉儲) : wcms use <a href="https://github.com/mdecycu/cmsimde">https://github.com/mdecycu/cmsimde</a> as submodule</p>
<p>-------------------------------------------------------------------------------------------------------</p>
<p></p>
<p></p>
<br /> <a href='HW.html'>Next</a> >> HW</div>
        
    <!-- footer -->
      <div class="container">
        <div class="row pt-3 mx-auto">
            <p>
            <!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
            Copyright &copy;<script>document.write(new Date().getFullYear());</script> All rights reserved | This template is made with <i class="icon-heart" aria-hidden="true"></i> by <a href="https://colorlib.com" target="_blank" >Colorlib</a>
            <!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
            </p>
        </div>
      </div>
    <!-- for footer -->
    
        </div> <!-- for site wrap -->
            <!-- <script src="../cmsimde/static/chimper/js/jquery-3.3.1.min.js"></script> -->
            <script src="../cmsimde/static/chimper/js/jquery-migrate-3.0.1.min.js"></script>
            <script src="../cmsimde/static/chimper/js/jquery-ui.js"></script>
            <script src="../cmsimde/static/chimper/js/popper.min.js"></script>
            <script src="../cmsimde/static/chimper/js/bootstrap.min.js"></script>
            <script src="../cmsimde/static/chimper/js/owl.carousel.min.js"></script>
            <script src="../cmsimde/static/chimper/js/jquery.stellar.min.js"></script>
            <script src="../cmsimde/static/chimper/js/jquery.countdown.min.js"></script>
            <script src="../cmsimde/static/chimper/js/jquery.magnific-popup.min.js"></script>
            <script src="../cmsimde/static/chimper/js/bootstrap-datepicker.min.js"></script>
            <script src="../cmsimde/static/chimper/js/aos.js"></script>
            <!--
            <script src="../cmsimde/static/chimper/js/typed.js"></script>
                    <script>
                    var typed = new Typed('.typed-words', {
                    strings: ["Web Apps"," WordPress"," Mobile Apps"],
                    typeSpeed: 80,
                    backSpeed: 80,
                    backDelay: 4000,
                    startDelay: 1000,
                    loop: true,
                    showCursor: true
                    });
                    </script>
            -->
            <script src="../cmsimde/static/chimper/js/main.js"></script>
        
<!-- 啟用 LaTeX equations 編輯 -->
  <!-- <script>
  MathJax = {
    tex: {inlineMath: [['$', '$'], ['\(', '\)']]}
  };
  </script>
  <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>-->
    </body></html>
        
