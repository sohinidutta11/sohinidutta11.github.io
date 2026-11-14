---
permalink: /research/
title: "Research"
author_profile: true
---

## Current Research

<div class="project-row project-row--wide">
  <img src="/images/research/articollision.jpg" alt="Two renders of the same cabinet with a box beside it. On the left the box is 9 mm inside the door's path and the door collides; on the right it is 16 mm outside and the door opens fully.">
  <div class="project-text">
    <p class="project-title"><strong>ArtiCollision: Can Multimodal LLMs Predict the Consequences of Articulated Motion?</strong></p>
    <p class="project-meta">Sohini Dutta, Prathosh A. P. · Ongoing research</p>
    <p>Can multimodal LLMs predict whether an articulated object will collide with its surroundings from a single image and an action? I study this using controlled simulated scenes that separate sensitivity to collision geometry from simpler visual cues.</p>
    <p><em>My role:</em> I initiated and lead the project, built the simulation pipeline, and run the training and diagnostic experiments.</p>
    <p><a href="https://drive.google.com/file/d/1os2fuhWqmc05iWVTzoiSSeA96v0qo9xY/view?usp=sharing">Manuscript (PDF)</a></p>
  </div>
</div>

<div class="project-row project-row--wide">
  <img src="/images/research/spixseg.jpg" alt="An image of two birds split into superpixels, the superpixels the model selected for each bird, and the final segmentation mask.">
  <div class="project-text">
    <p class="project-title"><strong>SPiXSeg: Segmenting Images by Selecting Regions with Multimodal LLMs</strong></p>
    <p class="project-meta">Piyush Tiwary, Sohini Dutta, Prathosh A. P. · Manuscript in preparation</p>
    <p>SPiXSeg segments images with a multimodal LLM by working with image regions instead of patches. The image is divided into superpixels that follow object boundaries, and the model selects the regions belonging to each answer directly from its hidden representations, so masks are recovered at full resolution. The same regions serve different segmentation tasks.</p>
    <p><em>My role:</em> I co-designed and built the mask-based positional encoding for regions, contributed geometry-aware pooling, and built the training and evaluation pipeline.</p>
    <p><a href="https://drive.google.com/file/d/1wdgOCyRm_HXQ90b4Y-iGfFPqKJEKutkw/view">Earlier version (PDF)</a></p>
  </div>
</div>

## Previous Research

<div class="project-row">
  <img src="/images/research/ground-plane.jpg" alt="Corridor image with the detected floor highlighted in green">
  <div class="project-text">
    <p class="project-title"><strong>Monocular Path Perception for Autonomous Navigation</strong></p>
    <p class="project-meta">Undergraduate research · IIT Madras · Dr. P. V. Manivannan · 2022</p>
    <p>Detected the drivable floor from a single RGB image using monocular depth, superpixels and region merging, for robots without a depth sensor.</p>
    <p><a href="https://github.com/sohinidutta11/ground-plane-estimation">Code</a></p>
  </div>
</div>
