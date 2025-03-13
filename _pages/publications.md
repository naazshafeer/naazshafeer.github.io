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
    grid-auto-rows: 250px; /* Set a base row height */
  }

  .photo-grid img {
    width: 100%; /* Images fill their grid cells */
    height: 100%; /* Fill the height of the grid cell */
    object-fit: cover; /* Ensures the image covers the cell without distortion */
    border-radius: 15px; /* Optional: Subtle rounded corners */
    display: block; /* Remove extra space below images */
  }

  /* Adjust grid row spans for taller images */
  .photo-grid .tall {
    grid-row: span 2; /* Span 2 rows for taller images */
  }

  .photo-grid .wide {
    grid-column: span 2; /* Span 2 columns for wider images */
  }
</style>

<div class="photo-grid">
  <img src="/assets/img/zayed.jpg" alt="Sheikh Zayed Mosque" class="tall">
  <img src="/assets/img/mogface.jpg" alt="Light and Shadow on the Face">
  <img src="/assets/img/sky.jpg" alt="Clouds" class="wide">
  <img src="/assets/img/angularity.jpeg" alt="Angularity">
  <img src="/assets/img/souq.jpg" alt="Herbs Souq" class="tall">
  <img src="/assets/img/wheat.jpg" alt="Wheat">
  <img src="/assets/img/koenigsegg.jpg" alt="Koenigsegg" class="wide">
  <img src="/assets/img/sacrementor.jpeg" alt="Sacramento in SF">
  <img src="/assets/img/profheadshot.jpg" alt="Professional Headshot" class="tall">
</div>
