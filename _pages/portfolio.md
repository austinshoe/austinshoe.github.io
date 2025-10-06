---
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

Here's some of the art I've done! I've divided it into sections for digital and physical art, as well as my 3D Modelling work!

## Digital Art

<div id="dig-slideshow" style="max-width:800px; margin:auto; position:relative;">
  <a href="https://www.instagram.com/froglogs_/" target="_blank">
    <img class="slide" src="/images/phoenix and ginkgo brighte.png" alt="Phoenix and Ginkgo">
    <img class="slide" src="/images/Froggers hoppers.png" alt="Froggers hoppers">
    <img class="slide" src="/images/Slideshow images/cherry.png" alt="Cherry art">
  </a>

  <!-- Dot navigation -->
  <div class="dots" style="text-align:center; margin-top:10px;">
    <span class="dot" onclick="currentSlide('dig-slideshow', 1)"></span>
    <span class="dot" onclick="currentSlide('dig-slideshow', 2)"></span>
    <span class="dot" onclick="currentSlide('dig-slideshow', 3)"></span>
  </div>
</div>

<style>
/* Dot styling */
.dots .dot {
  height: 12px;
  width: 12px;
  margin: 0 4px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  cursor: pointer;
  transition: background-color 0.3s;
}

.dots .dot.active {
  background-color: #717171;
}

/* Slide fade */
.slide {
  width: 100%;
  display: none;
  opacity: 0;
  transition: opacity 0.6s ease;
  position: absolute;
  top: 0;
  left: 0;
}

.slide.visible {
  display: block;
  opacity: 1;
  position: relative;
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function() {

  function initSlideshow(containerId, interval = 5000) {
    const container = document.getElementById(containerId);
    if (!container) return;

    const slides = Array.from(container.getElementsByClassName("slide"));
    const dots = Array.from(container.getElementsByClassName("dot"));

    let index = 0;
    let timer = null;

    function updateUI() {
      slides.forEach((s, i) => {
        s.classList.toggle("visible", i === index);
      });
      dots.forEach((d, i) => d.classList.toggle("active", i === index));
    }

    function goTo(n) {
      index = ((n % slides.length) + slides.length) % slides.length;
      updateUI();
      resetTimer();
    }

    function next() {
      goTo(index + 1);
    }

    function resetTimer() {
      clearTimeout(timer);
      timer = setTimeout(next, interval);
    }

    container.addEventListener("mouseenter", () => clearTimeout(timer));
    container.addEventListener("mouseleave", () => resetTimer());

    // Expose global function for inline onclick
    window.currentSlide = function(id, n) {
      if (id !== containerId) return;
      goTo(n - 1); // dots are 1-indexed
    }

    updateUI();
    resetTimer();
  }

  // Initialize slideshow
  initSlideshow("dig-slideshow", 5000);

});
</script>

## Physical Art

## 3D Models
