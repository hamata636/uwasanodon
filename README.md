# uwasanodon

<html>
<head>

<meta charset="UTF-8">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=EmulateIE10" />
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<!--ここから上はお決まりの定型文です-->


<!--ここからが表現の書式などを決めるcssという部分-->

<style type="text/css">
 p {
color: #0000ff;
font-size: 1.5em;
 }
 

 .red {color:#ff0000;}
 .grey {color:#ffffff; background:#999999;}
 .snow {color:#fffafa;}
 .yellow {color:#ff0000; background:#ffff00;}
 .blue {color:#0000ff;}
 .white {color:#ffffff; blinking;}
 .waku {border:2px dotted #99cc66;
　　　　　　line-height: 200%;
　　　　　　padding: 10px;}

 
 main {
background-color: rgba(255, 255, 255, 0.5);
}

section {
background-color: rgba(0, 225, 0, 0.3);
}
 

/* 点滅 */
.blinking{
	-webkit-animation:blink 1.5s ease-in-out infinite alternate;
    -moz-animation:blink 1.5s ease-in-out infinite alternate;
    animation:blink 1.5s ease-in-out infinite alternate;
}
@-webkit-keyframes blink{
    0% {opacity:0;}
    100% {opacity:1;}
}
@-moz-keyframes blink{
    0% {opacity:0;}
    100% {opacity:1;}
}
@keyframes blink{
    0% {opacity:0;}
    100% {opacity:1;}
}

#wrap {background:none} /*PC用の背景はオフ*/
    
/*背景を表示させる部分*/
body::before {
  content:"";
  display:block;
  position:fixed;
  top:0;
  left:0;
  z-index:-1;
  width:100%;
  height:100vh;
  background:url(20210221_007.JPG) center/cover no-repeat; 
  -webkit-background-size:cover;/*Android4*/
  }
  
a.p:hover {
    position: relative;
    text-decoration: none;
}
a.p span {
    display: none;
    position: relative;
    top: -0.5em;
    left: 2em;
}
a.p:hover span {
    border: none;
    display: block;
    width: 800px;
}   
 

@media	screen and (min-width: 540px),
	screen and (orientation: landscape) {
   p.note { display: none; }
}

</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">

</head>

<body>

<p class="note">
  モバイル端末をお使いの場合は、画面を横向きにすると
  より見やすくご覧頂けます。
</p>
    
<!--ここまでは定型文としてそのままコピペして再利用します-->

<p align="left"> <img src="QR_uwasanidon.png" alt="アクセス用QRコード" width="100">アクセス用QRコード</p>

<h1><span class="yellow"><marquee behavior="alternate">!!! 久々にご近所で犬の散歩していてら、住宅街の中にお持ち帰りの丼屋さんができてました !!!</marquee></span></h1>


<h3><span class="blue">メニューを見ていたら、一家総出でお出迎え</span></h3>

<a href="20210221_001.JPG" data-lightbox="abc"><img src="20210221_001.JPG" alt="サンプル画像" width="900" /></a>
<br>
<h3><span class="blue">同じ場所に英語の塾も併設されていて、奥様が英語の先生です<br>英語塾のHPリンク↓</span></h3>
	
<a href="https://www.willenglish.jp/" target="_blank" rel="noopener noreferrer">https://www.willenglish.jp/</a>
<a href="20210221_002.JPG" data-lightbox="abc"><img src="20210221_002.JPG" alt="サンプル画像" width="900" /></a>
<a href="20210221_003.JPG" data-lightbox="abc"><img src="20210221_003.JPG" alt="サンプル画像" width="900" /></a>
	
<h3><span class="blue">しばらくするとBAGELの販売も始めるそうです</span></h3>
<a href="20210221_004.JPG" data-lightbox="abc"><img src="20210221_004.JPG" alt="サンプル画像" width="900" /></a>
<a href="20210221_005.JPG" data-lightbox="abc"><img src="20210221_005.JPG" alt="サンプル画像" width="900" /></a>

<h3><span class="blue">2月の営業カレンダー</span></h3>
<a href="20210221_006.JPG" data-lightbox="abc"><img src="20210221_006.JPG" alt="サンプル画像" width="900" /></a>

<h3><span class="blue">最後になりましたが、噂の丼、HPリンク↓</span></h3>
<a href="https://omochikaeri.com/r/ZARRaHwXOdswhGm3EMCK" target="_blank" rel="noopener noreferrer">https://omochikaeri.com/r/ZARRaHwXOdswhGm3EMCK</a>

<h3><span class="blue">BAGEL用のHPもありました。HPリンク↓</span></h3>
<a href="https://omochikaeri.com/r/HwC5a9XcY3zgIES41tBT" target="_blank" rel="noopener noreferrer">https://omochikaeri.com/r/HwC5a9XcY3zgIES41tBT</a>
<br>
<h3><span class="blue">このお店のシステムは全国展開されている様ですね↓</span></h3>
<a href="https://omochikaeri.com/" target="_blank" rel="noopener noreferrer">https://omochikaeri.com/</a>

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>



<!-- フッタ -->
 <footer>
 Copyright 2021/02/21 S.Hada
 </footer>
 
 <!--HPにさまざまなJavaScriptを呼び込むための書式-->
<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>

<script type='text/javascript' src='https://globalsps.mds.honda.com/sites/jphgt38/Shared%20Documents/jquery.js?ver=1.12.4'></script> 
<script src="https://globalsps.mds.honda.com/sites/jphgt38/Shared%20Documents/jquery.goup.min.js"></script> 
<script src="https://globalsps.mds.honda.com/sites/jphgt38/Shared%20Documents/my.js"></script>


</body>

</html>
