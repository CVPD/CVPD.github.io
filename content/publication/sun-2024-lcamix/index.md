---
title: 'LCAMix: Local-and-contour aware grid mixing based data augmentation for medical
  image segmentation'
authors:
- Danyang Sun
- Fadi Dornaika
- Jinan Charafeddine
date: '2024-01-01'
publishDate: '2025-06-17T12:13:50.325549Z'
projects:
- carla-2021
url_code: https://github.com/DanielaPlusPlus/DataAug4Medical
publication_types:
- article-journal
publication: '*Information Fusion*'
doi: https://doi.org/10.1016/j.inffus.2024.102484
abstract: 'Medical image segmentation often faces challenges related to overfitting,
  primarily due to the limited and complex training samples. This challenge often
  prompts the use of self-supervised learning and data augmentation. However, self-supervised
  learning requires well-defined hand-crafted tasks and multiple training stages.
  On the other hand, basic image augmentation techniques like cropping, rotation,
  and flipping, effective for natural scene images, have limited efficacy for medical
  images due to their isotropic nature. While regional dropout regularization data
  augmentation methods have proven effective in image recognition tasks, their application
  in image segmentation is not as extensively studied. Additionally, existing augmentation
  methods often operate on square regions, leading to the loss of crucial contour
  information. This is particularly problematic for medical image segmentation tasks
  dealing with regions of interest characterized by intricate shapes. In this work,
  we introduce LCAMix, a novel data augmentation approach designed for medical image
  segmentation. LCAMix operates by blending two images and their segmentation masks
  based on their superpixels, incorporating a local-and-contour-aware strategy. The
  training process on augmented images adopts two auxiliary pretext tasks: firstly,
  classifying local superpixels in augmented images using an adaptive focal margin,
  leveraging segmentation ground truth masks as prior knowledge; secondly, reconstructing
  the two source images using mixed superpixels as mutual masks, emphasizing spatial
  sensitivity. Our method stands out as a simple, one-stage, model-agnostic, and plug-and-play
  data augmentation solution applicable to various segmentation tasks. Notably, it
  requires no external data or additional models. Extensive experiments validate its
  superior performance across diverse medical segmentation datasets and tasks. The
  source codes are available at https://github.com/DanielaPlusPlus/DataAug4Medical.'
tags:
- Data augmentation
- Medical image segmentation
- Superpixel
- Focal and angular margin
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1566253524002628
---
