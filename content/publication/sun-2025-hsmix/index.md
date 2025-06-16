---
title: 'HSMix: Hard and soft mixing data augmentation for medical image segmentation'
authors:
- Danyang Sun
- Fadi Dornaika
- Nagore Barrena
date: '2025-01-01'
publishDate: '2025-06-10T13:46:55.312214Z'
projects:
- carla-2021
publication_types:
- article-journal
publication: '*Information Fusion*'
doi: 10.1016/j.inffus.2024.102741
abstract: Due to the high cost of annotation or the rarity of some diseases, medical
  image segmentation is often limited by data scarcity and the resulting overfitting
  problem. Self-supervised learning and semi-supervised learning can mitigate the
  data scarcity challenge to some extent. However, both of these paradigms are complex
  and require either hand-crafted pretexts or well-defined pseudo-labels. In contrast,
  data augmentation represents a relatively simple and straightforward approach to
  addressing data scarcity issues. It has led to significant improvements in image
  recognition tasks. However, the effectiveness of local image editing augmentation
  techniques in the context of segmentation has been less explored. Additionally,
  traditional data augmentation methods for local image editing augmentation methods
  generally utilize square regions, which cause a loss of contour information. We
  propose HSMix, a novel approach to local image editing data augmentation involving
  hard and soft mixing for medical semantic segmentation. In our approach, a hard-augmented
  image is created by combining homogeneous regions (superpixels) from two source
  images. A soft mixing method further adjusts the brightness of these composed regions
  with brightness mixing based on locally aggregated pixel-wise saliency coefficients.
  The ground-truth segmentation masks of the two source images undergo the same mixing
  operations to generate the associated masks for the augmented images. Our method
  fully exploits both the prior contour and saliency information, thus preserving
  local semantic information in the augmented images while enriching the augmentation
  space with more diversity. Our method is a plug-and-play solution that is model
  agnostic and applicable to a range of medical imaging modalities. Extensive experimental
  evidence has demonstrated its effectiveness in a variety of medical segmentation
  tasks. The source code is available in https://github.com/DanielaPlusPlus/HSMix.
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1566253524005190
---
