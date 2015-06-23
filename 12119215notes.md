## bootstrap
###1.用Sublime Text做網頁排版
######1.直接在sublime text開啟新的資料夾(此命名為bst)
######2.到Boostrap網站下載資料->把檔案抓進去sublime text
######3.在bst下面開起New File --> 命名為index.html
######4.
        <!DOCTYE html>
        <html lang="utf-8">
          <head>
            <title>_(title name)_</title>
        </head>
          
        <body>
          <div class="col-mod-__(欄)/col-md-offset-__(間隔)/hidden-_(隱藏)">
          <div class="container(置中)/container-fluid">[區域、區塊、範圍]
              <H1>_(標題)_</H1>
              <P>_(段落)_</P>
              <buttton type="button">__(button name)__</button>
          </div>
          </div>
          <div class="col-mod-__(欄)/col-md-offset-__(間隔)/hidden-_(隱藏)">
               <img src="__(圖片網址)__" style="width:___%">
          </div>
          <footer>
          </footer>
           <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
  	   <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
  	   <script src="js/bootstrap.min.js"></script>
  			  (25.26.27行，可以到boostrap網站->Getting Started->Basic Temlate下面複製)
        </body>
        

####2.裝套件
######1.搜尋sublime text 3 package control，選擇第一個
######2.複製SUBLIME TEXT 3，貼回sublime text(ctrl+[~這格])
######套件1:ctrl+shift+P --> install --> 第一個 --> emmet
######套件2(排版:ctrl+alt+shift+F):ctrl+shift+P --> install --> 第一個 --> html Beautify
######套件3:ctrl+shift+P --> install --> 第一個 --> seti_UI --> 
######套件4(color):color highlighter

####3.欄 class:col-md-md(桌機)/sm/xs
####4.間隔 col-md-offset-
####5.隱藏 hidden-lg/md/sm/xs
####6.字型 font-family
####7.字體大小 font-size
####8.行高 line-height
####9.顏色 color
####10.背景顏色 background-color
####11.空格 &nbsp; (4個可以空一個字)
####12.置中 text-center

####13.頁腳
######1.SUBLIME TEXT INDEX : <footer class=container-fluid>
######2.SUBLIME TEXT CSS : footer{background-color: #aaa;}
######3.SUBLIME TEXT INDEX : div-->col-md-3 (分好下面各要占幾欄)
######4.<div class=container>
######5.ul.li + tab --> <ul class="list-unstyled(沒有標記符號)/inline(並排)">

###14.加入Glyphicons
######1.找到要加入的位置 --> SUBLIME TEXT INDEX : <i class="glyphicon __(Boostrap->Components->選擇一個喜歡的)___"></i>
######2.SUBLIME TEXT CSS : .feature .glyphicon{font-sixe:__px}
######3.SUBLIME TEXT INDEX : 複製一個<link rel......> -->貼到下一行 -->bootstrap改成main
######4.在同一個<div>的""加入feature

###15.加入按鈕
######1.找到要加入按鈕的地方
######2.<button typo="button" class="btn btn-xs/sm/lg">_(button name)_</button>
######3.按鈕顏色 : btn-danger(紅)/warning(黃)/default(白)/primpary(灰)/success(綠)/info(淡藍)

###16.導覽列
######1.navbar-brand(靠左/放大)/nav-pills/nav-tabs(適合放在內部EX產品分類)/navbar-nav navbar-right(靠右)
######2.navbar-default(白)/inverse(黑)
######3.navbar-static(跟著移動)-top/bottom//fixed(固定)-top(在上面)/bottom(在下面)
######4.如果用Fixed要改SUBLIME TEXT CSS --> body{padding-top: __px}
######5.collapse : 此裝置必須在手機板的時候才有功用(隱藏)，必須設定在有"nav"的後面
######6.navbar-collapse : 手機以外要顯示
######7.
<div class="navbar-header">
	<a href="index.html" class="navbar-brand">TED分享-郎祖筠</a>
	<button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
		<span class="sr-only">Toggle navigation</span>
		<span class="icon-bar"></span>
		<span class="icon-bar"></span>
		<span class="icon-bar"></span>
	</button>
</div>
<ul class="list-unstyled nav navbar-nav navbar-right collapse navbar-collapse">

####17.分隔線 Hr
####18.左右對齊 text-align: justify
