---
layout: default
---
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-1RD501NP1L"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-1RD501NP1L');
</script>

<button onClick="togglePlay()">tunes</button>

<link href="https://fonts.cdnfonts.com/css/comic-sans" rel="stylesheet">
                
# About Me:
Hey, I'm Joe Daly here to give you Joe Daily. I'm a student at St Mary's College of Maryland studying Mathematics. Outside of education I work at the [Hawk Studios](https://www.instagram.com/smcm_hawkstudio/), SMCMs podcast studio. I also am the president of the Ping pong club and started climbing at our wall freshman year!<br/>

Here's me (on the right) and my buddy Ex, somewhere in Solomons Island!<br/>
![Me](Personal/assets/Images/MeAndEx.jpg)<br/>

# Blog: 
This is gonna be a mix of neat websites and other posts I've found and some old Proofs I've worked on in Foundations of Mathematics(Intro to proofs course) plus some new stuff I'md doing in my current number theory course. [Blog](Personal/BlogPage.md)

# Resume: 
This is my General Resume:
[Resume](Personal/assets/Resume%20General%20Joe%20Daly-2.pdf)<br/>
I also have a [Professional website](Joe'sResumePage/JoesResume.html) that has my resume and some references! 
<br/>

# Silly stuff
[Here's](Personal/SamAl.html) the first site I made when messing around with HTML<br/>
[My buddy](Personal/Forrest.html)

<audio id="myAudio" src="Personal\assets\Audio\Saint Pepsi - Enjoy yourself.mp3" type="Audio/mp3" preload="auto">
</audio>

<script>

    var myAudio = document.getElementById("myAudio");
    var isPlaying = false;

    function togglePlay() {
    isPlaying ? myAudio.pause() : myAudio.play();
    };

    myAudio.onplaying = function() {
    isPlaying = true;
    };
    myAudio.onpause = function() {
    isPlaying = false;
    };
</script>
