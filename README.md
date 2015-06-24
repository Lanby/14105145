# 14105145 行銷一乙 陳冠蓁
環境安裝

一開始到Bootstrap網站按Bootstrap，
之後開始Download Bootstrap，
解壓縮檔案後有三個資料夾CSS、fonts、js丟到Sublime Text 3，
建立新檔案index.html，
開始版面設計。

Bootstrap

<!DOCTYPE html>
   <html lang="utf-8">
  <head>  
<title> 頁面標題  </title>
    路徑
    <link rel="stylesheet" type="text/css" href="css/bootstrap.css"> 
    可以做連結
    <link rel="stylesheet" type="text/css" href="css/main.css">                         
  </head>
  <body> 
頁面導覽列
 <div class='navbar navbar-default navbar-static-top '> 
      <div class="container" >
        顯示在標題下
        <div class='navbar-header'> 
          標題
          <a href='index.html' class='navbar-brand'>TED talk</a> 
          縮小螢幕後按鈕
          <button type='button' class='navbar-toggle'   
          data-toggle='collapse'
          data-target='.navbar-collapse'>
          選項
          <span class='sr-only'> </span> 
          按鈕裡的線 一行一條線
          <span class='icon-bar'></span>      
          </button>
        </div>
        <ul class='nav navbar-nav navbar-right collapse navbar-collapse'> 
         旁邊的副標項目
         <li><a href='index.html'> </a></li> 
        </ul>
      </div>
    </div>
   <div class="container">
   段落內文
   <p></p> 
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
  <script src="js/bootstrap.js"></script>
  </div>
 </body>
</html>

欄位: class=’col-md-4’ 電腦大螢幕所顯示格數  ‘col-sm-4’ 小螢幕所顯示格數
隱藏: hidden-(xs/md/sm/lg)
顯示: visible-(xs/md/sm/lg)
字型: font-family
字體大小: font-size
行高: line-height
顏色: color
背景顏色: background-color
置中: text-center
可以調按鈕大小: .btn-xs .btn-sm .btn-lg
可以換按鈕顏色: class="btn btn- " 白色Default 藍色primary  綠色Success 
水藍 Info 橘色Warning 紅色Danger  沒有方框會顯示藍色底線Link
可以換導覽列顏色: 白色.navbar-default 黑色.navbar-inverse
最頂端會移動.navbar-static-top不會移動.navbar-fixed-top
建立類別: row
顯示照片 後面是可以調顯示的寬跟高比例: <img src=" " style=" ">
到bootstrap的components裡選小圖，然後把小圖底下英文貼到引號裡，就可以顯示: <i class=" "></i>
超連結: <a href= ></a>
設定按鈕: <button type='button'> </button>
字體大小:<h1></h1> 數字越小 字體越小<h2></h2>  
放在文字前，一個&nbsp;可以空半格: &nbsp;&nbsp;&nbsp;&nbsp; 
把內文框起來:well 
顯示間格:<div class='col-md-offset-1 '></div> 
12格裡顯示4格 最多只能用12格:<div class="col-md-4"> 

在css資料夾裡新增main.css
連結<link rel="stylesheet" type="text/css" href="css/main.css">
即可在裡面更改顏色 
ex:h1{color:#333}

1.	搜尋Sublime Text 3 package control → 按第一個→ ctrl+C 到sublime
2.	Sublime→ ctrl + ` →ctrl+V 套件安裝
3.	安裝後 ctrl+shift+P →install →按第一個 → emmet 《方便打語法》
4.	Ctrl+shift+p → install→按第一個→html 找 HTML Beautify→ ctrl+Alt+shift+F 《排版》
5.	Ctrl+shift+p → install→按第一個→seti_UI
網頁 →Q seti →seti_UI→Example →Sublime 可以換sublime的小圖


