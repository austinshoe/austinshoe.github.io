---
title: "Projects"
permalink: /projects/
author_profile: true
---

Welcome to my projects page! Here's some of the stuff I've been doing (<small>pictures are slideshows that auto-rotate every 5 seconds)</small>.

## Pokémon Heto
<div id="Heto-slideshow" style="max-width:800px; margin:auto;">
  <a href="https://github.com/austinshoe/PokemonHeto" target="_blank">
    <img class="slide" src="/images/Pokémon_Heto_Demo.png" style="width:100%; height:auto;">
    <img class="slide" src="/images/Slideshow images/Heto2.png" style="width:100%; height:auto; display:none;">
    <img class="slide" src="/images/Slideshow images/Heto3.png" style="width:100%; height:auto; display:none;">
    <img class="slide" src="/images/Slideshow images/Heto4.png" style="width:100%; height:auto; display:none;">
    <img class="slide" src="/images/Slideshow images/Heto5.png" style="width:100%; height:auto; display:none;">
    <img class="slide" src="/images/Slideshow images/Heto6.png" style="width:100%; height:auto; display:none;">
    <img class="slide" src="/images/Slideshow images/Heto7.png" style="width:100%; height:auto; display:none;">
    <img class="slide" src="/images/Slideshow images/Heto8.png" style="width:100%; height:auto; display:none;">
    <img class="slide" src="/images/Slideshow images/Heto9.png" style="width:100%; height:auto; display:none;">
    <img class="slide" src="/images/Slideshow images/Heto10.png" style="width:100%; height:auto; display:none;">
  </a>
</div>

<script>
function initSlideshow(containerId, interval=5000) {
  let slideIndex = 0;
  const container = document.getElementById(containerId);
  const slides = container.getElementsByClassName("slide");

  function showSlides() {
    for (let i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
    }
    slideIndex++;
    if (slideIndex > slides.length) { slideIndex = 1; }
    slides[slideIndex - 1].style.display = "block";
    setTimeout(showSlides, interval);
  }

  showSlides();
}
</script>
<script>
initSlideshow("heto-slideshow", 5000);
</script>

[🔗 GitHub Repo](https://github.com/austinshoe/PokemonHeto)

A custom Gen III styled Pokémon Decompilation fan game! Drew inspiration from the world of *86: Eighty-Six*! Developed using a publicly available, open-source decompilation of Pokémon Emerald, reconstructed for educational and fan-use purposes.
Contains custom art, a custom soundtrack, new plotline, region and fakemon! 

---

## Hobo Wizard Adventures
<div id="hobo-slideshow" style="max-width:800px; margin:auto;">
  <a href="https://www.instagram.com/froglogs_/" target="_blank">
    <img class="slide" src="/images/Slideshow images/HWA1.png" style="width:100%; height:auto;">
    <img class="slide" src="/images/Slideshow images/HWA3.png" style="width:100%; height:auto; display:none;">
    <img class="slide" src="/images/Slideshow images/HWA4.png" style="width:100%; height:auto; display:none;">
    <img class="slide" src="/images/Slideshow images/HWA5.png" style="width:100%; height:auto; display:none;">
  </a>
</div>

<script>
initSlideshow("hobo-slideshow", 5000);
</script>

[🔗 GitHub Repo](https://github.com/austinshoe/Hobo-Wizard-Adventures)

A WIP Unity based deckbuilding game! Play as a Hobo Wizard Frog and build your hand of doom!

A production of [Studio Citrus](https://github.com/Studio-Of-Citrus). 
<small>Note: Public Github Updates will be discontinued as we plan to eventually monetize and publish the game on Steam. 
Follow our progress on instagram at [froglogs_](https://www.instagram.com/froglogs_/)!</small>

---

## Chibi Frog Adventures
<div id="chibi-slideshow" style="max-width:800px; margin:auto;">
  <a href="https://www.instagram.com/froglogs_/" target="_blank">
    <img class="slide" src="/images/Slideshow images/Chibi1.png" style="width:100%; height:auto;">
    <img class="slide" src="/images/Slideshow images/Chibi2.png" style="width:100%; height:auto; display:none;">
    <img class="slide" src="/images/Slideshow images/Chibi3.png" style="width:100%; height:auto; display:none;">
    <img class="slide" src="/images/Slideshow images/Chibi4.png" style="width:100%; height:auto; display:none;">
    <img class="slide" src="/images/Slideshow images/Chibi5.png" style="width:100%; height:auto; display:none;">
  </a>
</div>
<script>
initSlideshow("chibi-slideshow", 5000);
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
<div id="chibi-slideshow" style="max-width:800px; margin:auto;">
  <a href="https://github.com/austinshoe/Lost-Youkai" target="_blank">
    <img class="slide" src="/images/Slideshow images/cherry.png" style="width:100%; height:auto;">
    <img class="slide" src="/images/Slideshow images/cherryblossom.png" style="width:100%; height:auto; display:none;">
  </a>
</div>
<script>
initSlideshow("chibi-slideshow", 5000);
</script>

[🔗 GitHub Repo](https://github.com/austinshoe/Lost-Youkai)

My team's Lightning Round (1 week) project at CMU Precollege's NHSGA! It's a reboot on the arcade classic Robotron, but set in a post ghost apocalyptic world...
