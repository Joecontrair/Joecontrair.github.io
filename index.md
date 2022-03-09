---
layout: default
---
<button onClick="togglePlay()">tunes</button>
# About Me:
Hey, I'm Joe Daly here to give you Joe Daily. I'm a student enrolled at St Mary's College of Maryland studying Mathematics with a minor in both Philosophy and Business. I currently work 3 jobs on campus and hope to continue building up my Resume! As of last year I have taken up climbing and can now do up to V5s, and recently have started learning a little bit of computer science. <br/>
![Me](Personal/assets/Images/Pic.png)

# Blog: 
This is gonna be a mix of neat websites and other posts I've found and some of the current Proofs I've been working on in Foundations of Mathematics. [Blog](Personal/BlogPage.md)

# Resume: 
This is my General Resume, essentially a list of all previous job experience and relevant educational experiences. 
[Resume](Personal/assets/Resume%20General%20Joe%20Daly.pdf)

# The pals
Felt like making a page for ma roomie so I did. [Roomie](Personal/Roomie.md)<br/>
Some of my other buds too!: <br/>
[Keppler](Personal/Keppler.md)<br/>

[Forrest](Personal/Forrest.html)

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