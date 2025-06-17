---
title: 'LGCOAMix: Local and Global Context-and-Object-Part-Aware Superpixel-Based
  Data Augmentation for Deep Visual Recognition'
authors:
- Fadi Dornaika
- Danyang Sun
date: '2024-01-01'
publishDate: '2025-06-17T08:17:01.583660Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Image Processing*'
doi: 10.1109/TIP.2023.3336532
abstract: Cutmix-based data augmentation, which uses a cut-and-paste strategy, has
  shown remarkable generalization capabilities in deep learning. However, existing
  methods primarily consider global semantics with image-level constraints, which
  excessively reduces attention to the discriminative local context of the class and
  leads to a performance improvement bottleneck. Moreover, existing methods for generating
  augmented samples usually involve cutting and pasting rectangular or square regions,
  resulting in a loss of object part information. To mitigate the problem of inconsistency
  between the augmented image and the generated mixed label, existing methods usually
  require double forward propagation or rely on an external pre-trained network for
  object centering, which is inefficient. To overcome the above limitations, we propose
  LGCOAMix, an efficient context-aware and object-part-aware superpixel-based grid
  blending method for data augmentation. To the best of our knowledge, this is the
  first time that a label mixing strategy using a superpixel attention approach has
  been proposed for cutmix-based data augmentation. It is the first instance of learning
  local features from discriminative superpixel-wise regions and cross-image superpixel
  contrasts. Extensive experiments on various benchmark datasets show that LGCOAMix
  outperforms state-of-the-art cutmix-based data augmentation methods on classification
  tasks, and weakly supervised object location on CUB200-2011. We have demonstrated
  the effectiveness of LGCOAMix not only for CNN networks, but also for Transformer
  networks. Source codes are available at https://github.com/DanielaPlusPlus/LGCOAMix.
tags:
- Data augmentation
- Training
- Semantics
- Visualization
- Deep learning
- Transformers
- Kernel
- Superpixel
- data augmentation
- context-and-object-part-aware
- contrastive learning
- local and global
---
