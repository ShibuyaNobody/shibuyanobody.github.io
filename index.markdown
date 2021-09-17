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
        color: grey;
      }
      div {
        background-color: #eeeeee;
        border-radius: 10px;
        /* box-shadow: 0px 0px 3px #000000; */
        opacity: 0.95;
      }
    </style>
    <script>
      var aAudio = new Audio('undertale_dog_bark.mp3')
      var bAudio = new Audio('sqek.mp3')
      // function myAudioFunction (letter) {
      //   if(letter == 'a') {
      //     aAudio.play();
      //   }
      //   else if (letter =='b') {
      //     bAudio.play();
      //   }
      // }
    </script>
  </head>
  <body>
    <!-- <embed src="DogSong.mp3" loop="true" autostart="true" width="2" height="0"> -->
    <div>
      <!-- <a onclick="myAudioFunction('A');> -->
        <img src="img/1z4FBfS.gif" onclick="document.getElementById('undertale_dog_bark.mp3').play();">
      <!-- </a> -->
      <h1>Welcome to my CIT480 Blog!</h1>
    </div>
  </body>
</html>