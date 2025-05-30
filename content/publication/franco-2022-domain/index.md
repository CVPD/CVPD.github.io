---
title: Deep learning based domain adaptation for mitochondria segmentation on EM volumes
authors:
- Daniel Franco-Barranco
- Julio Pastor-Tronch
- Aitor Gonzalez-Marfil
- Arrate Muñoz-Barrutia
- Ignacio Arganda-Carreras
date: '2022-01-01'
publishDate: '2025-03-05T11:10:32.699709Z'
publication_types:
- article-journal
publication: '*Computer Methods and Programs in Biomedicine*'
doi: https://doi.org/10.1016/j.cmpb.2022.106949
abstract: 'Background and Objective: Accurate segmentation of electron microscopy
  (EM) volumes of the brain is essential to characterize neuronal structures at a
  cell or organelle level. While supervised deep learning methods have led to major
  breakthroughs in that direction during the past years, they usually require large
  amounts of annotated data to be trained, and perform poorly on other data acquired
  under similar experimental and imaging conditions. This is a problem known as domain
  adaptation, since models that learned from a sample distribution (or source domain)
  struggle to maintain their performance on samples extracted from a different distribution
  or target domain. In this work, we address the complex case of deep learning based
  domain adaptation for mitochondria segmentation across EM datasets from different
  tissues and species. Methods: We present three unsupervised domain adaptation strategies
  to improve mitochondria segmentation in the target domain based on (1) state-of-the-art
  style transfer between images of both domains; (2) self-supervised learning to pre-train
  a model using unlabeled source and target images, and then fine-tune it only with
  the source labels; and (3) multi-task neural network architectures trained end-to-end
  with both labeled and unlabeled images. Additionally, to ensure good generalization
  in our models, we propose a new training stopping criterion based on morphological
  priors obtained exclusively in the source domain. The code and its documentation
  are publicly available at https://github.com/danifranco/EM_domain_adaptation. Results:
  We carried out all possible cross-dataset experiments using three publicly available
  EM datasets. We evaluated our proposed strategies and those of others based on the
  mitochondria semantic labels predicted on the target datasets. Conclusions: The
  methods introduced here outperform the baseline methods and compare favorably to
  the state of the art. In the absence of validation labels, monitoring our proposed
  morphology-based metric is an intuitive and effective way to stop the training process
  and select in average optimal models.'
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0169260722003315
---
