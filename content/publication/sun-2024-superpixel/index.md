---
title: 'Superpixel Mixing: A Data Augmentation Technique For Robust Deep Visual Recognition
  Models'
authors:
- Danyang Sun
- Fadi Dornaika
- Vinh Truong Hoang
- Nagore Barrena
date: '2024-10-01'
publishDate: '2025-06-10T13:46:55.323411Z'
publication_types:
- paper-conference
publication: '*2024 IEEE International Conference on Image Processing (ICIP)*'
doi: 10.1109/ICIP51287.2024.10648078
abstract: Data augmentation can mitigate overfitting problems in data exploration
  without increasing the size of the model. Existing cutmix-based data augmentation
  has been proven to significantly enhance deep learning performance. However, many
  existing methods overlook the discriminative local context of the image and rely
  on ad hoc regions consisting of square or rectangular local regions, resulting in
  the loss of complete semantic object parts. In this work, we propose a superpixelwise
  local-context-aware efficient image mixing approach for data augmentation, aiming
  to overcome the limitations previously mentioned. Our approach only requires one
  forward propagation using a superpixel attention-based label mixing with lower computational
  complexity. The model is trained using a combination of a global classification
  of the mixed (augmented) image loss, a superpixel-wise weighted local classification
  loss, and a superpixel-based weighted contrastive learning loss. The last two losses
  are based on the superpixel-aware attentive embeddings. Thus, the resulting deep
  encoder can learn both local and global features of the images, capturing object-part
  local context information. Experiments on diverse benchmarks, such as ImageNet-1K
  and CUB-200-2011, indicate that the proposed method out-performs many augmentation
  methods for visual recognition. We have not only demonstrated its effectiveness
  on CNN models, but also on transformer models.
---
