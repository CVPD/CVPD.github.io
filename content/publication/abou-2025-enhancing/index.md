---
title: Enhancing Generalization and Mitigating Overfitting in Deep Learning for Brain
  Cancer Diagnosis from MRI
authors:
- Mohamad Abou Ali
- Jinan Charafeddine
- Fadi Dornaika
- Ignacio Arganda-Carreras
date: '2025-01-01'
publishDate: '2025-05-30T15:30:23.995028Z'
projects:
- carla-2021
- giu23-022
publication_types:
- article-journal
publication: '*Applied Magnetic Resonance*'
doi: 10.1007/s00723-024-01743-y
abstract: 'Brain cancer represents a significant global health challenge with increasing
  incidence and mortality rates. Magnetic Resonance Imaging (MRI) plays a pivotal
  role in early detection and treatment planning. This study adopts a systematic approach
  across four phases: (1) Optimal Model Selection using the Adam optimizer, emphasizing
  accuracy metrics, weight computation, early stopping, and ReduceLROnPlateau techniques.
  (2) Real-world Scenario Simulation through synthetic perturbed datasets created
  by applying noise, blur (to simulate various magnetic field strengths: 1T, 1.5T,
  3T), and patient motion artifacts (mimicking MRI scanning motion effects) to the
  testing data from the BT-MRI dataset, an online published brain tumor MRI dataset.
  (3) Optimization involving a range of optimizers (Adam, Adagrad, Nadam, RMSprop,
  SGD) and online augmentation techniques (AutoMix, CutMix, LGCOAMix, PatchUp). (4)
  Solution Exploration integrating Gaussian Noise and Blur as augmentation strategies
  during training to enhance model generalization under diverse conditions. Initial
  evaluations achieved strong performance, consistently reaching 99.45% accuracy on
  the BT-MRI dataset. However, testing against synthetic perturbed datasets mimicking
  real-world conditions revealed challenges in maintaining robust model performance.
  Despite employing diverse optimization methods and advanced augmentation techniques,
  this study identifies persistent challenges in ensuring model robustness with synthetic
  perturbed datasets. Notably, the integration of Gaussian Noise and Blur during training
  significantly improved model resilience. This research underscores the critical
  role of methodological rigor and innovative augmentation strategies in advancing
  deep learning applications for precise brain cancer diagnosis using MRI.'
---
