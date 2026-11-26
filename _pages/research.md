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
  <img src="/images/research/spixseg.jpg" alt="An image split into superpixels, the superpixels selected for each object, and the final segmentation mask.">
  <div class="project-text">
    <p class="project-title"><strong>SPiXSeg: Rethinking MLLM Segmentation as Superpixel Classification</strong></p>
    <p class="project-meta">Piyush Tiwary, Sohini Dutta, Prathosh A. P. · Preprint</p>
    <p>SPiXSeg recasts segmentation with multimodal LLMs as superpixel classification. Each image is split once, without the query, into non-overlapping superpixels, and this one set of regions serves every task: referring segmentation keeps a subset, and semantic segmentation gives each superpixel a class. S2M scores each superpixel from the model's own hidden states, and the mask is the union of the chosen superpixels.</p>
    <p><em>My role:</em> I designed and built S2M, the superpixel tokens and the pluggable superpixel segmenters, and built the training and evaluation pipeline.</p>
    <p><a href="https://arxiv.org/abs/2611.33842">arXiv</a></p>
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
