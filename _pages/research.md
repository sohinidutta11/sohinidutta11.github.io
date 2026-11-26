---
permalink: /research/
title: "Research"
author_profile: true
---

## Current Research

<div class="pub">
  <figure class="pub-figure">
    <img src="/images/research/spixseg.jpg" alt="One image split into superpixels once, and the same superpixels used for referring segmentation, generalized referring segmentation, semantic segmentation and bounding boxes.">
  </figure>
  <p class="pub-title">SPiXSeg: Rethinking MLLM-based Image Segmentation as Superpixel Classification</p>
  <p class="pub-authors">Piyush Tiwary, <strong>Sohini Dutta</strong>, Prathosh A. P. <span class="pub-badge">Preprint</span></p>
  <p>SPiXSeg recasts segmentation with multimodal LLMs as superpixel classification. Each image is split once, without the query, into non-overlapping superpixels, and this one set of regions serves every task: referring segmentation keeps a subset, and semantic segmentation gives each superpixel a class. S2M scores each superpixel from the model's own hidden states, and the mask is the union of the chosen superpixels.</p>
  <p class="pub-role"><span>My role</span> I designed and built S2M, the superpixel tokens and the pluggable superpixel segmenters, and built the training and evaluation pipeline.</p>
  <p class="pub-links"><a href="https://arxiv.org/abs/2611.33842">arXiv</a></p>
</div>

<div class="pub">
  <figure class="pub-figure">
    <img src="/images/research/articollision.jpg" alt="Two renders of the same cabinet with a box beside it. On the left the box is 9 mm inside the door's path and the door collides; on the right it is 16 mm outside and the door opens fully.">
  </figure>
  <p class="pub-title">ArtiCollision: Can Multimodal LLMs Predict the Consequences of Articulated Motion?</p>
  <p class="pub-authors"><strong>Sohini Dutta</strong>, Prathosh A. P. <span class="pub-badge">Ongoing research</span></p>
  <p>Can multimodal LLMs predict whether an articulated object will collide with its surroundings from a single image and an action? I study this using controlled simulated scenes that separate sensitivity to collision geometry from simpler visual cues.</p>
  <p class="pub-role"><span>My role</span> I initiated and lead the project, built the simulation pipeline, and run the training and diagnostic experiments.</p>
  <p class="pub-links"><a href="https://drive.google.com/file/d/1os2fuhWqmc05iWVTzoiSSeA96v0qo9xY/view?usp=sharing">Manuscript (PDF)</a></p>
</div>

## Previous Research

<div class="pub pub--compact">
  <figure class="pub-figure">
    <img src="/images/research/ground-plane.jpg" alt="Corridor image with the detected floor highlighted in green">
  </figure>
  <div class="pub-body">
    <p class="pub-title">Monocular Path Perception for Autonomous Navigation</p>
    <p class="pub-authors">Undergraduate research · IIT Madras · Dr. P. V. Manivannan <span class="pub-badge">2022</span></p>
    <p>Detected the drivable floor from a single RGB image using monocular depth, superpixels and region merging, for robots without a depth sensor.</p>
    <p class="pub-links"><a href="https://github.com/sohinidutta11/ground-plane-estimation">Code</a></p>
  </div>
</div>
