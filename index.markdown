---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<html>
  <head>
    <meta charset="utf-8">
    <title>CIT480 Blog</title>
    <style>
      body {
        background-color: #eeeeee;
        background-image: url(img/n2sj8ochlfk61.png);
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        color: #eeeeee;
      }
      .center {
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 50%;
      }
      h1 {
        text-align: center;
        color: #000000;
      }
      div {
        background-color: #eeeeee;
        border-radius: 10px;
        /* box-shadow: 0px 0px 3px #000000; */
        opacity: 0.95;
      }
      a {
        color: #000000;
      }
      a:visited {
        color: #000000;
      }
      span.post-meta {
        color: #000000;
      }
    </style>
    <script>
      function setHalfVolume() {
        var myAudio = document.getElementById("dogsong");  
        myAudio.volume = 20%;
      }
    </script>
  </head>
  <body>
    <audio id="dogsong" autoplay loop onloadeddata="setHalfVolume()">
      <source src="DogSong.mp3"/>
    </audio>
    <audio id="bark" src="undertale_dog_bark.mp3"></audio>
    <div>
        <img src="img/1z4FBfS.gif" onclick="document.getElementById('bark').play();" class="center">
      <h1>Welcome to my CIT480 Blog!</h1>
    </div>
  </body>
</html>