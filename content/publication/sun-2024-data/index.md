---
title: Data augmentation for deep visual recognition using superpixel based pairwise
  image fusion
authors:
- Danyang Sun
- Fadi Dornaika
date: '2024-01-01'
publishDate: '2025-06-17T08:17:01.591339Z'
publication_types:
- article-journal
publication: '*Information Fusion*'
doi: https://doi.org/10.1016/j.inffus.2024.102308
abstract: Data augmentation is an important paradigm for boosting the generalization
  capability of deep learning in image classification tasks. Image augmentation using
  cut-and-paste strategies has shown very good performance improvement for deep learning.
  However, these existing methods often overlook the image's discriminative local
  context and rely on ad hoc regions consisting of square or rectangular local regions,
  leading to the loss of complete semantic object parts. In this work, we attempt
  to overcome these limitations and propose a superpixel-wise local-context-aware
  efficient image fusion approach for data augmentation. Our approach requires only
  one forward propagation using a superpixel attention-based label fusion with less
  computational complexity. The model is trained using a combination of a global classification
  of the fused (augmented) image loss, a superpixel-wise weighted local classification
  loss, and a superpixel-based weighted contrastive learning loss. The last two losses
  are based on the superpixel-aware attentive embeddings. Thus, the resulting deep
  encoder can learn both local and global features of the images while capturing object-part
  local context and information. Experiments on diverse benchmark image datasets indicate
  that the proposed method out-performs many region-based augmentation methods for
  visual recognition. We have demonstrated its effectiveness not only on CNN models
  but also on transformer models. The codes are accessible at https://github.com/DanielaPlusPlus/SAFuse.
tags:
- Superpixel
- Image fusion
- Data augmentation
- Weighted contrastive learning loss
- Local context
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1566253524000861
---
