---
title: Chasing a Better Decision Margin for Discriminative Histopathological Breast
  Cancer Image Classification
authors:
- Pendar Alirezazadeh
- Fadi Dornaika
- Abdelmalik Moujahid
date: '2023-01-01'
publishDate: '2025-06-13T10:28:35.698686Z'
publication_types:
- article-journal
publication: '*Electronics*'
doi: 10.3390/electronics12204356
abstract: 'When considering a large dataset of histopathologic breast images captured
  at various magnification levels, the process of distinguishing between benign and
  malignant cancer from these images can be time-intensive. The automation of histopathological
  breast cancer image classification holds significant promise for expediting pathology
  diagnoses and reducing the analysis time. Convolutional neural networks (CNNs) have
  recently gained traction for their ability to more accurately classify histopathological
  breast cancer images. CNNs excel at extracting distinctive features that emphasize
  semantic information. However, traditional CNNs employing the softmax loss function
  often struggle to achieve the necessary discriminatory power for this task. To address
  this challenge, a set of angular margin-based softmax loss functions have emerged,
  including angular softmax (A-Softmax), large margin cosine loss (CosFace), and additive
  angular margin (ArcFace), each sharing a common objective: maximizing inter-class
  variation while minimizing intra-class variation. This study delves into these three
  loss functions and their potential to extract distinguishing features while expanding
  the decision boundary between classes. Rigorous experimentation on a well-established
  histopathological breast cancer image dataset, BreakHis, has been conducted. As
  per the results, it is evident that CosFace focuses on augmenting the differences
  between classes, while A-Softmax and ArcFace tend to emphasize augmenting within-class
  variations. These observations underscore the efficacy of margin penalties on angular
  softmax losses in enhancing feature discrimination within the embedding space. These
  loss functions consistently outperform softmax-based techniques, either by widening
  the gaps among classes or enhancing the compactness of individual classes.'
links:
- name: URL
  url: https://www.mdpi.com/2079-9292/12/20/4356
---
