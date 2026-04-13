---
title: Multi-view semi-supervised classification via innovative graph construction
  and smoothness-aware graph convolution
authors:
- Guowen Peng
- Fadi Dornaika
- Denis Hamad
- Vinh Truong Hoang
date: '2026-01-01'
publishDate: '2026-04-13T10:15:13.131147Z'
publication_types:
- article-journal
publication: '*Knowledge-Based Systems*'
doi: https://doi.org/10.1016/j.knosys.2026.115586
abstract: 'Multi-view semi-supervised classification (Mv-SSC) aims to leverage complementary
  information from multiple views and unlabeled data to enhance classification performance.
  However, existing methods often struggle with constructing robust graphs, effectively
  fusing heterogeneous features. Therefore, we propose a novel framework, Multi-view
  Semi-supervised Classification with Graph Construction Innovation and Smoothness-aware
  Graph Convolution (GCSGC), which introduces three key innovations. First, we employ
  sparse autoencoders (SAEs) coupled with a learnable feature fusion module based
  on a one-layer fully connected network. The SAEs extract compact and discriminative
  representations from each view by enforcing sparsity to remove redundancies, while
  the fully connected layer adaptively aligns the multi-view latent features with
  the learnable shared features to preserve complementary semantic information. Second,
  GCSGC introduces two types of view-based graphs: (1) a Cosine-KNN-based Collaborative
  Graph (CKG) that integrates K-Nearest Neighbor relationships with cosine similarity
  of the learned view-specific latent features, and (2) a robust semi-supervised graph
  that enhances inter-view consistency and structural stability. Third, we design
  a hybrid loss function that combines cross-entropy and smoothness regularization
  to guide the optimization of the graph convolutional network. Extensive experiments
  on multiple benchmark datasets demonstrate that GCSGC consistently outperforms state-of-the-art
  Mv-SSC methods, validating the effectiveness of its innovative graph construction
  strategy, sparse feature fusion mechanism, and dual-loss optimization. This work
  provides a new perspective on integrating structural modeling, feature transformation,
  and loss design in multi-view semi-supervised learning.'
tags:
- Multi-view semi-supervised classification
- Graph convolutional network
- Feature fusion
- Graph construction
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0950705126003266
---
