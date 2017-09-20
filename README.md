<!DOCTYPE html>
<head>
    <meta charset="utf-8"> 
    <link rel='stylesheet' href='./style_home.css'>
    <title>Movie Sound Track</title>
    <meta property="og:url" content="http://limp0417.cafe24.com">
    <meta property="og:type" content="website">
    <meta property="og:title" content="Movie Sound Track">
    <meta property="og:image" content="./img/open-graph.png">
    <meta property="og:description"  type='text/css' content="음악으로 영화를 만나다.">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <link rel="shortcut icon" href="./favicon.ico" >
    <link rel="icon" href="./favicon.ico" >

<script>
var music = new Audio();
music.src = "A Lovely Night.mp3";

var music1 = new Audio();
music1.src = "A Step You Can`t Take Back.mp3";

var music2 = new Audio();
music2.src = "Up.mp3";

var music3 = new Audio();
music3.src = "Belle.mp3";

</script>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js">
</script>

<script> 

var menu = $("#lp");
        lp.rotate({animateTo:100});



    });
}); 



 
</script>


</head>

<body>



<header>
<svg id="menu-icon" fill="#191919" height="30" viewBox="0 0 24 24" width="30" xmlns="http://www.w3.org/2000/svg" 
onclick="nav.style.left='0px';" >
    <path d="M0 0h24v24H0z" fill="none"/>
    <path d="M15 6H3v2h12V6zm0 4H3v2h12v-2zM3 16h8v-2H3v2zM17 6v8.18c-.31-.11-.65-.18-1-.18-1.66 0-3 1.34-3 3s1.34 3 3 3 3-1.34 3-3V8h3V6h-5z"/>
</svg>
<a href="./index.html">Movie Sound Track</a>

</header>    


<nav class="desktop">
  <ul>
    <li class="title">
        <div class="title">
            MOVIE PLAY LIST
        </div>
    </li>

    <li onmouseover="music.play()" id="menu" onmouseout="music.pause()">
        <div class="image">
          <img src="./img/lala land.jpg" class="circle">
        </div>
        <div class="text">
          <a class="musicMenu" href="./lala land.html" >Lala Land</a>
        </div>
    </li>

    <li onmouseover="music1.play()" id="menu" onmouseout="music1.pause()">
        <div class="image">
          <img src="./img/slider_beginagain.png" class="circle">
        </div>
        <div class="text">
          <a class="musicMenu" href="./beginagain.html" >Begin Again</a>
        </div>
    </li>

    <li onmouseover="music2.play()" onmouseout="music2.pause()">
        <div class="image">
          <img src="./img/sing street.jpg" class="circle">
        </div>
        <div class="text">
         <a class="musicMenu" href="./sing street.html" >Sing Street</a>
        </div>
    </li> 

    <li onmouseover="music3.play()" onmouseout="music3.pause()">
        <div class="image">
          <img src="./img/slider_beauty and the beast.png" class="circle">
        </div>
        <div class="text">
         <a class="musicMenu" href="./beauty and the beast.html" >Beauty And The Beast</a>
        </div>
    </li>
 
    <li onmouseover="music.play()" onmouseout="music.pause()">
        <div class="image">
          <img src="./img/lala land.jpg" class="circle">
        </div>
        <div class="text">
          <a class="musicMenu" href="./lala land.html" >Lala Land</a>
        </div>
    </li>

    <li onmouseover="music1.play()" onmouseout="music1.pause()">
        <div class="image">
          <img src="./img/slider_beginagain.png" class="circle">
        </div>
        <div class="text">
          <a class="musicMenu" href="./beginagain.html" >Begin Again</a>
        </div>
    </li>
  </ul>
</nav>




		 	
<nav id="nav" class="mobile">

<ul>
        <li onclick="nav.style.left='-240px'">
          <svg id="close-icon" fill="#4c4c4c" height="30" viewBox="0 0 24 24" width="30" xmlns="http://www.w3.org/2000/svg">
          <path d="M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12z"/>
          <path d="M0 0h24v24H0z" fill="none"/>
        </svg>
        </li>
        <li><a href="./lala land.html" >Lala Land</a></li>
        <li><a href="./beginagain.html" >Begin Again</a></li>
        <li><a href="./sing street.html" >Sing Street</a></li>
        <li><a href="./beauty and the beast.html" >Beauty And The Beast</a></li>
        <li><a href="./lala land.html" >Lala Land</a></li>
        <li><a href="./beginagain.html" >Begin Again</a></li>
</ul>

</nav>







<article>

<audio audio autoplay loop>
  <source src="./">
</audio>

<div class="wrap" >
          <img id="lp" style="-webkit-animation: spin 90s  infinite;
   animation: spin 90s infinite;" " class="bottom" src="./img/lp.png">
          <img class="top" src="./img/lp_1.png">
</div>




</article>


</body>



           

    

