---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in ML and Data Science, EPITA, 2024
* B.S. in Software Engineering, EPITA, 2022

Work experience
======
* Spring 2024 - Present: ML/MLOps Engineer @ Valeo Brain Division
  * Co-developed L2+/L3 autonomous driving features (lane detection, vehicle detection, and multi-object tracking) using SOTA research for pseudo-label generation comparable to manual annotation
  * Led the development of scalable Dataflow LiDAR perception pipelines enabling 100× faster throughput than manual annotation with only a slight KPI reduction.
  * Implemented a training pipeline with KFP and Pytorch Lightning for on-board semantic segmentation.
  * Developed internal cloud-based platform for point-cloud visualization, dataset creation and pipeline triggering, reducing data-access time from hours to ~seconds and eliminating egress-heavy workflows.


Personal projects
======
* LeRobot Hackathon / LeKiwi
  * Won the 2025 GOSIM AI LeRobot x Seeed studio hackathon in Paris
  * Built a mobile base for my SO-100 (LeKiwi)
  * Developed face tracking and voice localization with dora-rs and ODAS
* Deep Learning for Perception
  * Trained multiple Deep Learning models from scratch on ImageNet with PyTorch Lightning
  * Reached original ResNet paper’s performance (92% Acc@5) on a 20e budget

Skills
======

* Programming languages: Python (3+ years), C/C++ (2 years)
* Google Cloud Platform (Dataflow, KFP)
* ML framework: Pytorch (2+ years)
  * Pytorch Lightning
  * Weights and biases
* Hands on experience with model training for computer vision tasks (image classification, semantic segmentation)

<!-- Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
