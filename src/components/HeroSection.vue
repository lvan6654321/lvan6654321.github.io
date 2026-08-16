<template>
  <header>
    <div class="container">
      <div class="hero-left">
        <h1>Who am i ？<br><span class="grad-name">Davis Luona</span></h1>
        <p class="hero-sub">Entrepreneur | China E-commerce Practitioner | Business Connector</p>
        <div class="hero-cta">
          <a href="#about" class="btn btn-primary">Learn More →</a>
          <a href="https://x.com/tinln25249" class="btn btn-ghost">Follow Twitter</a>
        </div>
      </div>
      <div class="hero-right">
        <div class="hero-carousel">
          <div class="slide"><img :src="slide1" alt="Slide 1"></div>
          <div class="slide"><img :src="slide2" alt="Slide 2"></div>
          <div class="slide"><img :src="slide3" alt="Slide 3"></div>
          <div class="carousel-dots">
            <span class="dot"></span>
            <span class="dot"></span>
            <span class="dot"></span>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script setup>
import slide1 from '../assets/slide1.png'
import slide2 from '../assets/slide2.png'
import slide3 from '../assets/slide3.png'
</script>
