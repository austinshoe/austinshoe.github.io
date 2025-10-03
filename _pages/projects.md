---
title: "Projects"
permalink: /projects/
author_profile: true
---

Welcome to my projects page! Here's some of the stuff I've been doing.

## Pokémon Heto
[![Pokemon Heto Screenshot](/images/Pokémon_Heto_Demo.png)](https://github.com/austinshoe/PokemonHeto)
[🔗 GitHub Repo](https://github.com/austinshoe/PokemonHeto)

A custom Gen III styled Pokémon Decompilation fan game! Drew inspiration from the world of *86: Eighty-Six*!
Contains custom art, a custom soundtrack, new plotline, region and fakemon! Completion rate: 93%

---

## Hobo Wizard Adventures
<div style="max-width:750px; margin:auto;">
  <a href="https://www.instagram.com/froglogs_/" target="_blank">
    <img class="slideshow" src="/images/Slideshow images/HWA1.png" style="width:100%; height:auto;">
    <img class="slideshow" src="/images/Slideshow images/HWA3.png" style="width:100%; height:auto; display:none;">
    <img class="slideshow" src="/images/Slideshow images/HWA4.png" style="width:100%; height:auto; display:none;">
    <img class="slideshow" src="/images/Slideshow images/HWA5.png" style="width:100%; height:auto; display:none;">
  </a>
</div>

<script>
let slideIndex = 0;
const slides = document.getElementsByClassName("slideshow");

function showSlides() {
  for (let i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) { slideIndex = 1 }    
  slides[slideIndex-1].style.display = "block";  
  setTimeout(showSlides, 5000); // Change every 30 seconds
}

showSlides();
</script>
[🔗 GitHub Repo](https://github.com/austinshoe/Hobo-Wizard-Adventures)

A WIP Unity based deckbuilding game! Play as a Hobo Wizard Frog and build your hand of doom!

A production of [Studio Citrus](https://github.com/Studio-Of-Citrus). 
<small>Note: Public Github Updates will be discontinued as we plan to eventually monetize and publish the game on Steam. 
Follow our progress on instagram at [froglogs_](https://www.instagram.com/froglogs_/)!</small>

---

## Chibi Frog Adventures
<div style="max-width:750px; margin:auto;">
  <a href="https://www.instagram.com/froglogs_/" target="_blank">
    <img class="slideshow" src="/images/Slideshow images/Chibi1.png" style="width:100%; height:auto;">
    <img class="slideshow" src="/images/Slideshow images/Chibi2.png" style="width:100%; height:auto; display:none;">
    <img class="slideshow" src="/images/Slideshow images/Chibi3.png" style="width:100%; height:auto; display:none;">
    <img class="slideshow" src="/images/Slideshow images/Chibi4.png" style="width:100%; height:auto; display:none;">
    <img class="slideshow" src="/images/Slideshow images/Chibi5.png" style="width:100%; height:auto; display:none;">
  </a>
</div>

<script>
let slideIndex = 0;
const slides = document.getElementsByClassName("slideshow");

function showSlides() {
  for (let i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) { slideIndex = 1 }    
  slides[slideIndex-1].style.display = "block";  
  setTimeout(showSlides, 5000); // Change every 30 seconds
}

showSlides();
</script>

A WIP Unity based RPG Game, built off the setting of Hobo Wizard Adventures!

A production of [Studio Citrus](https://github.com/Studio-Of-Citrus). 
<small>Note: Public Github Updates will be discontinued as we plan to eventually monetize and publish the game on Steam. 
Follow our progress on instagram at [froglogs_](https://www.instagram.com/froglogs_/)!</small>

---

## 32-bit MIPS CPU
[🔗 GitHub Repo](https://github.com/austinshoe/32-bit-CPU-MIPS)

Practicing Digital Design with Verilog by creating a simple 32-bit MIPS CPU!

---

## Lost Youkai
[🔗 GitHub Repo](https://github.com/austinshoe/Lost-Youkai)

My team's Lightning Round (1 week) project at CMU Precollege's NHSGA! It's a reboot on the arcade classic Robotron, but set in a post ghost apocalyptic world...
