---
title: Multi-view Data Clustering Through Consensus Graph and Data Representation
  Learning
authors:
- Fadi Dornaika
- Sally El Hajjar
date: '2024-01-01'
publishDate: '2025-06-04T11:13:09.019793Z'
publication_types:
- chapter
publication: '*Advances in Data Clustering: Theory and Applications*'
doi: 10.1007/978-981-97-7679-5_6
abstract: In the domain of multi-view clustering, existing methodologies can be categorized
  into subspace multi-view clustering algorithms, multi-view kernel approaches, matrix
  factorization approaches, and spectral clustering algorithms. However, a common
  limitation among these approaches is their dependence on combining predefined individual
  similarity matrices from multiple views. This susceptibility to noisy original similarity
  matrices, along with the integration of various spectral projection matrices, often
  affects their overall performance. To address these limitations, we introduce a
  novel approach named multi-view clustering with consensus graph learning and spectral
  representation (MCGLSR). In contrast to the traditional practice of directly integrating
  similarity matrices from different views, which may introduce noise, our proposed
  method simultaneously generates similarity graphs for each view and their shared
  similarity matrix (graph matrix) through a unified global objective function. This
  unified objective function ensures that the similarity matrices from different views
  are compelled to be sufficiently similar, effectively mitigating the impact of noise
  and promoting a more coherent unified data structure. Moreover, our approach facilitates
  the recovery of the common spectral projection and soft cluster assignments based
  on the shared graph structure. Crucially, MCGLSR operates on a kernelized representation
  of the views' features, producing individual graphs, a common graph, a common spectral
  representation, and cluster assignments directly. This eliminates the need for an
  external clustering algorithm in the final stage. To validate the efficacy of our
  technique, we conduct experiments on several real-world datasets, demonstrating
  its robust performance and addressing the identified shortcomings in existing approaches.
links:
- name: URL
  url: https://doi.org/10.1007/978-981-97-7679-5_6
---
