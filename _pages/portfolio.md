---
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

Here's some of the art I've done! I've divided it into sections for digital and physical art, as well as my 3D Modelling work!

## Digital Art
<div id="dig-slideshow" style="max-width:800px; margin:auto; position:relative;">
  <a href="https://www.instagram.com/froglogs_/" target="_blank">
    <img class="slide" src="/images/phoenix and ginkgo brighte.png" style="width:100%; display:block;">
    <img class="slide" src="/images/Froggers hoppers.png" style="width:100%; display:none;">
    <img class="slide" src="/images/Slideshow images/cherry.png" style="width:100%; display:none;">
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
</style>

<script>
function initSlideshow(containerId, interval = 5000) {
  const container = document.getElementById(containerId);
  if (!container) return console.warn("Slideshow container not found:", containerId);

  const slides = Array.from(container.getElementsByClassName("slide"));
  const dots = Array.from(container.getElementsByClassName("dot"));

  let index = 0;
  let timer = null;

  function updateUI() {
    slides.forEach((s, i) => {
      s.style.display = (i === index) ? "block" : "none";
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

  window.currentSlide = function(id, n) {
    if (id !== containerId) return;
    goTo(n - 1);
  }

  updateUI();
  resetTimer();
}

initSlideshow("dig-slideshow", 5000);
</script>


## Physical Art

## 3D Models

