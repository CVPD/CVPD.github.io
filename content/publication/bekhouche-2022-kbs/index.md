---
title: Driver drowsiness detection in video sequences using hybrid selection of deep
  features
authors:
- Salah Eddine Bekhouche
- Yassine Ruichek
- Fadi Dornaika
date: '2022-01-01'
publishDate: '2025-07-08T13:16:32.448096Z'
publication_types:
- article-journal
publication: '*Knowledge-Based Systems*'
doi: https://doi.org/10.1016/j.knosys.2022.109436
abstract: Monitoring driver's drowsiness is a complex problem that involves many indicators
  whether behavioral or physiological. Drowsiness is a challenging problem that can
  lead to road disasters. Sleeping driver is more dangerous on the road than a speeding
  driver. Many statistics showed that one-fifth of road accidents in the world were
  due to driver fatigue, hence safety modules that can alert drowsy drivers in the
  hopes of reducing the risk of accidents are very important. This paper proposes
  a framework for driver drowsiness detection based on a computer vision solution.
  The proposed framework's first task is to detect the driver's face. A transfer learning
  is then performed for extracting the deep features from the driver's face image
  using a pre-trained deep convolutional network model trained on a facial recognition
  dataset. The previous tasks are applied in a sliding temporal window (less than
  a second) in which the frames are sampled. In this work, 9 frames were the best
  choice. The extracted features of these frames represent the observation matrix.
  Then temporal feature aggregation is applied to construct the raw feature vector.
  To obtain the final feature vector, a proposed feature selection is applied to omit
  possible irrelevant features. The final feature vector is finally fed to a binary
  classifier to decide whether there is drowsiness or not. Extensive experiments are
  applied to NTHU Drowsy Driver Detection (NTHU-DDD) video dataset. The outcomes show
  the outperformance of the proposed approach compared with the state-of-the-art approaches.
tags:
- Drowsiness detection
- Transfer learning
- Feature selection
- SVM classifier
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0950705122007225
---
