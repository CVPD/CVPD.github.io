---
title: Multi-Level XAI-Driven MLOps Pipeline for the Adjustment of Fruit and Vegetable
  Classifiers
authors:
- Francisco Javier Iriarte
- Miguel E Ortiz
- Luis Unzueta
- Javier Martı́nez
- Javier Zaldivar
- Ignacio Arganda-Carreras
date: '2024-01-01'
publishDate: '2025-05-30T15:30:23.964492Z'
projects:
- carla-2021
publication_types:
- paper-conference
publication: '*2024 IEEE 12th International Conference on Intelligent Systems (IS)*'
doi: 10.1109/IS61756.2024.10705202
abstract: In this paper, we present a machine learning operations (MLOps) pipeline
  that exploits explainable artificial intelligence (XAI) to adjust deep neural network
  (DNN)-based fruit and vegetable image classifiers to data observed at super-market
  self-checkouts. DNNs are currently the most successful AI models for several automation
  tasks, including fruit and vegetable classification. However, adjusting them to
  on-site observations to avoid model drift is challenging, as they work as black
  boxes that take inputs and return results without showing the processes that lead
  to their responses. State-of-the-art XAI techniques could help mitigate this problem,
  but integrating them in MLOps pipelines is also challenging due to their high computational
  cost. We propose multi-task B-cos (MTBC) DNNs integrated at different pipeline levels
  to obtain automated information about the system's on-site performance. MTBC DNNs
  allow indentification of fruit and vegetable types with contextual attributes in
  real time and generation of contribution maps that highlight task-relevant features
  for enhanced model adjustment. Experimental results show that MTBC DNNs obtain similar
  accuracy and performance to the equivalent baseline DNNs for fruit and vegetable
  classification but with the added benefit of explainability, supporting MLOps processes
  such as drift detection and exploratory data analysis.
---
