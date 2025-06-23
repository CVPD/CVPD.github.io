---
title: Sample-weighted fused graph-based semi-supervised learning on multi-view data
authors:
- Jingjun Bi
- Fadi Dornaika
date: '2024-01-01'
publishDate: '2025-06-17T08:17:01.557965Z'
publication_types:
- article-journal
publication: '*Information Fusion*'
doi: https://doi.org/10.1016/j.inffus.2023.102175
abstract: 'Research in semi-supervised learning on graphs has attracted more and more
  attention in recent years, as learning on graphs is applied in more and more domains
  and labeling data is expensive and time-consuming. Some scenarios have inherent
  graph structures in their data, such as the relationships between people in social
  scenarios or the relationships between objects that are mutually referenced. However,
  there are also many data types without inherent graph structures, such as image
  data, and each image can be described with different features, which is a typical
  type of multi-view data. For image data and other non-graph data, there are significantly
  fewer deep learning approaches that target multi-view graph-based semi-supervised
  learning. This paper attempts to fill this gap. Based on the Graph Convolutional
  Network (GCN) architecture, we propose a Sample-weighted Fused Graph-based Semi-supervised
  Classification (WFGSC) method for multi-view data in this paper. It (i) constructs
  a semi-supervised graph in each view using a flexible model for joint graph and
  label estimation, (ii) obtains an additional graph based on the representation of
  nodes provided by the joint estimator, and then obtains a fused graph between all
  views, (iii) gives higher weights to hard-to-classify samples, (iv) proposes a loss
  function to train the GCN on the fused features and the consensus graph that integrates
  graph auto-encoder loss and label smoothing over the consensus graph. The results
  of our experiments on six multi-view datasets show that our WFGSC performs well
  on both fused graph construction and semi-supervised classification, and generally
  outperforms traditional GCNs and other multi-view semi-supervised multi-view classification
  methods.11Source code: https://github.com/BiJingjun/WFGSC.'
url_code: https://github.com/BiJingjun/WFGSC
tags:
- Multi-view data
- Semi-supervised classification
- Semi-supervised graph construction
- Fused graph
- Graph convolutional networks
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1566253523004918
---
