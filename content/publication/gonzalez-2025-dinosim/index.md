---
title: 'DINOSim: Zero-Shot Object Detection and Semantic Segmentation on Electron
  Microscopy Images'
authors:
- Aitor González-Marfil
- Estibaliz Gómez-de-Mariscal
- Ignacio Arganda-Carreras
date: '2025-01-01'
publishDate: '2025-05-30T15:30:24.017577Z'
projects:
- carla-2021
- giu23-022
publication_types:
- article
publication: '*bioRxiv*'
doi: 10.1101/2025.03.09.642092
abstract: We present DINOSim, a novel approach leveraging the DINOv2 pretrained encoder
  for zero-shot object detection and segmentation in electron microscopy datasets.
  By exploiting semantic embeddings, DINOSim generates pseudo-labels from patch distances
  to a user-selected reference, which are subsequently employed in a k-nearest neighbors
  framework for inference. Our method effectively detects and segments previously
  unseen objects in electron microscopy images without additional finetuning or prompt
  engineering. We also investigate the impact of prompt selection and model size on
  accuracy and generalization. To promote accessibility, we developed an open-source
  Napari plugin, enabling streamlined application in scientific research. DINOSim
  offers a flexible and efficient solution for object detection in resource-constrained
  settings, addressing a critical gap in bioimage analysis.
url_code: https://github.com/AAitorG/napari-dinoSim

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'DINOSim enables zero-shot image segmentation by selecting reference points on an image.'
  focal_point: ""
  preview_only: false
---
