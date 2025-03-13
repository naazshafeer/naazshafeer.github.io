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
    transition: transform 0.3s ease, box-shadow 0.3s ease; /* Hover effect */
  }

  .photo-grid img:hover {
    transform: scale(1.02); /* Slightly enlarge on hover */
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2); /* Add shadow */
  }

  /* Full-width image styling */
  .full-width {
    flex: 1 1 100%; /* Take up full width */
    max-width: 100%; /* Ensure it spans the entire container */
    border-radius: 0; /* Remove rounded corners for full-width images */
  }

  /* Style for the horizontal line */
   hr {
  border: 0;
  height: 1px;
  background: linear-gradient(to right, transparent, #000, transparent); /* Gradient line */
  margin: 40px 0;
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
  }
</style>

<!-- Line before the "Eye" image -->
<hr>

<!-- Full-width "Eye" image -->
<div class="photo-grid">
  <img src="/assets/img/eye.jpg" alt="Eye with Prime Lens" class="full-width">
</div>

<!-- Line after the "Eye" image -->
<hr>

<!-- Grid for the rest of the images -->
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
  <img src="/assets/img/birds.jpg" alt="Alignment of Birds">
</div>
