---
title: 'ConvNeXt Meets Vision Transformers: A Powerful Hybrid Framework for Facial
  Age Estimation'
authors:
- Gaby Maroun
- Salah Eddine Bekhouche
- Fadi Dornaika
date: '2026-01-01'
publishDate: '2026-04-13T10:15:13.123563Z'
publication_types:
- article-journal
publication: '*Applied Sciences*'
doi: 10.3390/app16073281
abstract: Age estimation based on facial images is a challenging task due to the complex
  and nonlinear nature of facial aging, which is influenced by both genetic and environmental
  factors. To address this challenge, we propose a hybrid ConvNeXt-Transformer framework
  that combines convolutional local feature extraction with attention-based global
  contextual modeling within a unified age regression pipeline. The methodological
  contribution of this work lies in the sequential integration of these two complementary
  paradigms for facial age estimation, allowing the model to capture both fine-grained
  textural cues—such as wrinkles and skin spots—and long-range spatial dependencies.
  We evaluate the proposed framework on benchmark datasets including MORPH II, CACD,
  UTKFace, and AFAD. The results show competitive performance across these datasets
  and confirm the effectiveness of the proposed hybrid design through extensive ablation
  analyses. Experimental results demonstrate that our approach achieves state-of-the-art
  MAE on MORPH II (2.26), CACD (4.35), and AFAD (3.09) under the adopted benchmark
  settings while remaining competitive on UTKFace. To address computational efficiency,
  we employ ImageNet pre-trained backbones and explore different architectural configurations,
  including fusion strategies and varying depths of the Transformer module, as well
  as regularization techniques such as stochastic depth and label smoothing. Ablation
  studies confirm the contribution of each component, particularly the role of attention
  mechanisms, in enhancing the model's sensitivity to age-relevant features. Overall,
  the proposed hybrid framework provides a robust and accurate solution for facial
  age estimation, effectively balancing performance and computational cost.
links:
- name: URL
  url: https://www.mdpi.com/2076-3417/16/7/3281
---
