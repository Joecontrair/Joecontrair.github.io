---
title: Hayden Anderson
layout: single
---
# Welcome to My roomies Page!
![Hayden](assets/Images/Hayden1.png.jpg) <br/>
This here is Hayden Anderson, ma roomie. Figured he deserved the honor of having a lil page of his own. 
<button onClick="playSong()">Haydens Favorite</button> <br/>

[back](../index.md)

<audio id="Weezer Roulette" src="assets/Audio/FrogsUpdated.mp3" type="audio/mp3" preload="auto">
    </audio>


<script>
    const songs = ["Personal/assets/Audio/Camel by Camel - Mix Vocal.mp3","Personal/assets/Audio/Weezer - Island In The Sun.mp3",
    "Personal/assets/Audio/Weezer - Say It Ain't So.mp3","Personal/assets/Audio/Weezer (Red Album) - Pork and Beans.mp3"]
    function playSong(){
    const songIndex = Math.round(Math.random()*(songs.length-1))
    const WeezerRouletteElement = document.getElementById("Weezer Roulette")
    WeezerRouletteElement.setAttribute("src", songs[songIndex])
    if(WeezerRouletteElement.paused){WeezerRouletteElement.play()}
    else{WeezerRouletteElement.pause()}
    }
    
</script> 
