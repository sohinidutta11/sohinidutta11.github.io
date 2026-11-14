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
    <p>Vision models can estimate how an object's parts move, but acting on an object also means predicting what that motion will do in a particular scene, such as whether an opening door will hit the box beside it. ArtiCollision asks whether multimodal LLMs can make this prediction from a single image and an action. In each family of simulated scenes, the object, part, action and viewpoint stay fixed and only the obstacle moves, so an obstacle just inside the part's path can be compared with one just outside it. Fine-tuning improves accuracy, but the models we test do not reliably separate these pairs, and their predictions respond to the obstacle's position without consistently locating the edge of the motion. I am now studying what the models' internal representations encode about this geometry, and whether explicit geometric inputs help.</p>
    <p><em>My role:</em> I initiated and lead the project, designed the task, built the simulation pipeline for generating matched scenes, and ran the training, evaluation and diagnostic experiments.</p>
    <p><a href="https://drive.google.com/file/d/1os2fuhWqmc05iWVTzoiSSeA96v0qo9xY/view?usp=sharing">Manuscript (PDF)</a></p>
  </div>
</div>

<div class="project-row project-row--wide">
  <img src="/images/research/spixseg.jpg" alt="An image of two birds split into superpixels, the superpixels the model selected for each bird, and the final segmentation mask.">
  <div class="project-text">
    <p class="project-title"><strong>SPiXSeg: Segmenting Images by Selecting Regions with Multimodal LLMs</strong></p>
    <p class="project-meta">Piyush Tiwary, Sohini Dutta, Prathosh A. P. · Manuscript in preparation</p>
    <p>Multimodal LLMs can segment images by writing masks out as text, but labelling every image patch makes the output long and limits resolution. SPiXSeg divides the image into superpixels, small regions that follow object boundaries, and the model answers by choosing regions. About 64–128 region labels replace roughly 1,024 patch labels, and masks are recovered at full image resolution. Our first version had the model write region IDs as text. The current version selects regions directly from the model's hidden representations, which improves referring-expression segmentation.</p>
    <p><em>My role:</em> I co-designed, built and ablated the mask-based positional encoding for regions, contributed geometry-aware pooling, and built the region-level supervision and the training and evaluation pipeline.</p>
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
