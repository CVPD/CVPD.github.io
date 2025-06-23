---
title: Towards a unified framework for graph-based multi-view clustering
authors:
- Fadi Dornaika
- Sally El Hajjar
date: '2024-01-01'
publishDate: '2025-06-04T11:13:08.958760Z'
projects:
- carla-2021
publication_types:
- article-journal
- giu23-022
publication: '*Neural Networks*'
doi: 10.1016/j.neunet.2024.106197
abstract: 'Recently, clustering data collected from various sources has become a hot
  topic in real-world applications. The most common methods for multi-view clustering
  can be divided into several categories: Spectral clustering algorithms, subspace
  multi-view clustering algorithms, matrix factorization approaches, and kernel methods.
  Despite the high performance of these methods, they directly fuse all similarity
  matrices of all views and separate the affinity learning process from the multiview
  clustering process. The performance of these algorithms can be affected by noisy
  affinity matrices. To overcome this drawback, this paper presents a novel method
  called One Step Multi-view Clustering via Consensus Graph Learning and Nonnegative
  Embedding (OSMGNE). Instead of directly merging the similarity matrices of different
  views, which may contain noise, a step of learning a consensus similarity matrix
  is performed. This step forces the similarity matrices of different views to be
  too similar, which eliminates the problem of noisy data. Moreover, the use of the
  nonnegative embedding matrix (soft cluster assignment matrix makes it possible to
  directly obtain the final clustering result without any extra step. The proposed
  method can solve five subtasks simultaneously. It jointly estimates the similarity
  matrix of all views, the similarity matrix of each view, the corresponding spectral
  projection matrix, the unified clustering indicator matrix, and automatically gives
  the weight of each view without the use of hyper-parameters. In addition, another
  version of our method is also studied in this paper. This method differs from the
  first one by using a consensus spectral projection matrix and a consensus Laplacian
  matrix over all views. An iterative algorithm is proposed to solve the optimization
  problem of these two methods. The two proposed methods are tested on several real
  datasets, which prove their superiority.'
tags:
- Graph-based multi-view clustering
- Unified and consensus graph learning
- Data fusion
- Spectral embedding
- Soft cluster assignments
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0893608024001217
---
