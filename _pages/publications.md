---
layout: page
permalink: /portfolio/
title: Portfolio
description: This is a portfolio of my photography. Scroll through and see through the lens of my camera!
nav: true
nav_order: 2
---

<style>
  .photo-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); /* Responsive grid with minimum column width of 300px */
    gap: 20px; /* Spacing between images */
    padding: 20px;
  }

  .photo-grid img {
    width: 100%; /* Images fill their grid cells */
    height: auto; /* Maintain aspect ratio */
    border-radius: 15px; /* Optional: Subtle rounded corners */
    display: block; /* Remove extra space below images */
  }
</style>

<div class="photo-grid">
  <img src="/assets/img/zayed.jpg" alt="Sheikh Zayed Mosque">
  <img src="/assets/img/mogface.jpg" alt="Light and Shadow on the Face">
  <img src="/assets/img/sky.jpg" alt="Clouds">
  <img src="/assets/img/angularity.jpeg" alt="Angularity">
  <img src="/assets/img/souq.jpg" alt="Herbs Souq">
  <img src="/assets/img/wheat.jpg" alt="Wheat">
  <img src="/assets/img/koenigsegg.jpg" alt="Koenigsegg">
  <img src="/assets/img/sacrementor.jpeg" alt="Sacramento in SF">
  <img src="/assets/img/profheadshot.jpg" alt="Professional Headshot">
</div>
