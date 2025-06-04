---
title: Single phase multi-view clustering using unified graph learning and spectral
  representation
authors:
- Fadi Dornaika
- Sally El Hajjar
date: '2023-01-01'
publishDate: '2025-06-04T11:13:08.966826Z'
publication_types:
- article-journal
publication: '*Information Sciences*'
doi: 10.1016/j.ins.2023.119366
abstract: 'The most widely used multi-view clustering approaches can be classified
  into different groups: Subspace multi-view clustering algorithms, multi-view kernel
  approaches, matrix factorization approaches, and spectral clustering algorithms.
  Most approaches rely on combining predefined individual similarity matrices from
  multiple views, and then estimate the common similarity matrix. Therefore, their
  performance can be severely affected by noisy original similarity matrices. Moreover,
  most of these methods integrate different spectral projection matrices of each view
  together, which can also affect the clustering results. To address these shortcomings,
  we propose a single-phase multiview clustering method with Consensus Graph Learning
  and Spectral Representation (MCGLSR) in this paper. Instead of directly integrating
  the similarity matrices of the different views, which could introduce noise, our
  proposed method jointly generates similarity graphs of the views and their common
  similarity matrix (graph matrix) using a unified global objective function. At this
  stage, the similarity matrices of the different views are enforced to be sufficiently
  similar, which eliminates the problem of noise and promotes a clearer unified data
  structure. Moreover, our proposed objective function is able to recover the common
  spectral projection and soft cluster assignments based on the common graph structure.
  The proposed method takes as input a kernelized representation of the views features
  and directly provides the individual graphs, the common graph, the common spectral
  representation, and the cluster assignments. Our technique allows us to obtain the
  final cluster assignments without requiring an external clustering algorithm. Several
  real-world datasets are used to evaluate our technique and demonstrate its efficacy.
  The code of the proposed method will be available at the following link: https://github.com/SallyHajjar/MCGLSR.git.'
tags:
- Multi-view clustering
- Consensus graph learning
- Consensus spectral representation matrix
- Cluster assignment matrix
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0020025523009519
---
