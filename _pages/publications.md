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
    display: flex;
    flex-wrap: wrap; /* Allow items to wrap to the next line */
    gap: 20px; /* Spacing between images */
    padding: 20px;
  }

  .photo-grid img {
    flex: 1 1 calc(33.333% - 20px); /* Each image takes up roughly 1/3 of the space, minus the gap */
    max-width: calc(33.333% - 20px); /* Ensure images don't exceed their container */
    height: auto; /* Maintain aspect ratio */
    border-radius: 15px; /* Optional: Subtle rounded corners */
    object-fit: contain; /* Ensure the entire image is visible */
  }

  /* Adjust for smaller screens */
  @media (max-width: 768px) {
    .photo-grid img {
      flex: 1 1 calc(50% - 20px); /* Two columns on smaller screens */
      max-width: calc(50% - 20px);
    }
  }

  @media (max-width: 480px) {
    .photo-grid img {
      flex: 1 1 100%; /* Single column on mobile */
      max-width: 100%;
    }
    
    .photo-grid img {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.photo-grid img:hover {
  transform: scale(1.02); /* Slightly enlarge on hover */
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2); /* Add shadow */
}
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
