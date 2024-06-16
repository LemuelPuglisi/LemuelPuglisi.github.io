---
layout: post
title: Brain Latent Progression (BrLP) early-accepted (top 11%) at MICCAI 2024 
date: 2024-05-13
inline: false
related_posts: false
---


I'm excited to announce that our paper, "Enhancing Spatiotemporal Disease Progression Models via Latent Diffusion and Prior Knowledge," has been early accepted and ranked among the top 11% of papers at MICCAI 2024, the top-tier conference in medical imaging.

* [📜 Link to Arxiv pre-print](https://arxiv.org/abs/2405.03328) 
* [🖥️ Link to GitHub open-source code](https://github.com/LemuelPuglisi/BrLP) 

In this work, we introduce the Brain Latent Progression (BrLP), an innovative spatiotemporal model to predict future structural changes in the brains of individuals with neurological disorders via 3D brain MRI.

The video below illustrates four case studies where BrLP predicts structural changes in subjects experiencing (1) mild cognitive impairments, (2) normal aging, and (3) Alzheimer's disease. In the fourth case study, we demonstrate the simulated progression of a single subject under these three distinct cognitive statuses.

<br>

<iframe width="100%" height="315" src="https://www.youtube.com/embed/6YKz2MNM4jg?si=9e5CMFEaFcw4t8v-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br>


Key technical details: BrLP incorporates subject metadata, including demographic and potentially genetic factors. It leverages longitudinal data when available and integrates prior knowledge of disease progression to precisely predict changes across different brain regions. The model operates in a small latent space, significantly reducing the computational resources needed compared to running the progression in the 3D imaging space. Additionally, we introduce a technique called Latent Average Stabilization (LAS) to improve the spatiotemporal consistency of the predicted progression.

<br>

{% include figure.html path="assets/img/brlp-pipeline.png" class="img-fluid rounded z-depth-1" %}

<br>

**Stay tuned for more news about BrLP!**



