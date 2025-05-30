---
title: 'Enhancing MRI brain tumor classification: A comprehensive approach integrating
  real-life scenario simulation and augmentation techniques'
authors:
- Mohamad Abou Ali
- Fadi Dornaika
- Ignacio Arganda-Carreras
- Rejdi Chmouri
- Hussien Shayeh
date: '2024-01-01'
publishDate: '2025-05-30T15:30:23.979221Z'
publication_types:
- article-journal
publication: '*Physica Medica*'
doi: 10.1016/j.ejmp.2024.104841
abstract: 'Brain cancer poses a significant global health challenge, with mortality
  rates showing a concerning surge over recent decades. The incidence of brain cancer-related
  mortality has risen from 140,000 to 250,000, accompanied by a doubling in new diagnoses
  from 175,000 to 350,000. In response, magnetic resonance imaging (MRI) has emerged
  as a pivotal diagnostic tool, facilitating early detection and treatment planning.
  However, the translation of deep learning approaches to brain cancer diagnosis faces
  a critical obstacle: the scarcity of public clinical datasets reflecting real-world
  complexities. This study aims to bridge this gap through a comprehensive exploration
  and augmentation of training data. Initially, a battery of pre-trained deep models
  undergoes evaluation on a main brain cancer MRI “BT-MRI” dataset, yielding remarkable
  performance metrics, including 100% accuracy, precision, recall, and F1-Score, substantiated
  by the Score-CAM methodology. This initial success underscores the potential of
  deep learning in brain cancer diagnosis. Subsequently, the model’s efficacy undergoes
  further scrutiny using a supplementary brain cancer MRI “BCD-MRI” dataset, affirming
  its robustness and applicability across diverse datasets. However, the ultimate
  litmus test lies in confronting the model with synthetic testing datasets crafted
  to emulate real-world scenarios. The synthetic testing datasets, a BCD-MRI testing
  sub-dataset enriched with noise, blur, and simulated patient motion, reveal a sobering
  reality: the model’s performance plummets, exposing inherent limitations in generalization.
  To address this issue, a diverse set of optimization strategies and augmentation
  techniques, ranging from diverse optimizers to sophisticated data augmentation methods,
  are exhaustively explored. Despite these efforts, the problem of generalization
  persists. The breakthrough emerges with the integration of noise and blur as augmentation
  techniques during the training process. Leveraging Gaussian noise and Gaussian blur
  kernels, the model undergoes a transformative evolution, exhibiting newfound robustness
  and resilience. Retesting the refined model against the challenging synthetic datasets
  reveals a remarkable transformation, with performance metrics witnessing a notable
  ascent. This achievement underscores the important role of correct selection of
  data augmentation in fortifying the generalization of deep learning models for brain
  cancer diagnosis. This study not only advances the frontiers of diagnostic precision
  in brain cancer but also underscores the paramount importance of methodological
  rigor and innovation in confronting the complexities of real-world clinical scenarios.'
---
