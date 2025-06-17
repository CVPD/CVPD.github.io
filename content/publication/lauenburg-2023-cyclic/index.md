---
title: 3D Domain Adaptive Instance Segmentation Via Cyclic Segmentation GANs
authors:
- Leander Lauenburg
- Zudi Lin
- Ruihan Zhang
- Márcia dos Santos
- Siyu Huang
- Ignacio Arganda-Carreras
- Edward S. Boyden
- Hanspeter Pfister
- Donglai Wei
date: '2023-01-01'
publishDate: '2025-03-05T11:10:32.671393Z'
projects:
  - carla-2021
publication_types:
- article-journal
publication: '*IEEE Journal of Biomedical and Health Informatics*'
doi: 10.1109/JBHI.2023.3281332
abstract: "3D instance segmentation for unlabeled imaging modalities is a challenging but essential task as collecting expert annotation can be expensive and time-consuming. Existing works segment a new modality by either deploying pre-trained models optimized on diverse training data or sequentially conducting image translation and segmentation with two relatively independent networks. In this work, we propose a novel Cyclic Segmentation Generative Adversarial Network (CySGAN) that conducts image translation and instance segmentation simultaneously using a unified network with weight sharing. Since the image translation layer can be removed at inference time, our proposed model does not introduce additional computational cost upon a standard segmentation model. For optimizing CySGAN, besides the CycleGAN losses for image translation and supervised losses for the annotated source domain, we also utilize self-supervised and segmentation-based adversarial objectives to enhance the model performance by leveraging unlabeled target domain images. We benchmark our approach on the task of 3D neuronal nuclei segmentation with annotated electron microscopy (EM) images and unlabeled expansion microscopy (ExM) data. The proposed CySGAN outperforms pre-trained generalist models, feature-level domain adaptation models, and the baselines that conduct image translation and segmentation sequentially. Our implementation and the newly collected, densely annotated ExM zebrafish brain nuclei dataset, named NucExM, are publicly available at https://connectomics-bazaar.github.io/proj/CySGAN/index.html."
url_code: https://connectomics-bazaar.github.io/proj/CySGAN/index.html
---
