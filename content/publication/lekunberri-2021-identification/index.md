---
title: Identification and measurement of tropical tuna species in purse seiner catches
  using computer vision and deep learning
authors:
- Xabier Lekunberri
- Jon Ruiz
- Iñaki Quincoces
- Fadi Dornaika
- Ignacio Arganda-Carreras
- Jose A Fernandes
date: '2021-01-01'
publishDate: '2025-03-05T11:10:32.738527Z'
publication_types:
- article-journal
publication: '*Ecological Informatics*'
doi: 10.1016/j.ecoinf.2021.101495
abstract: Fishery monitoring programs are essential for effective management of marine resources, as they provide scientists and managers with the necessary data for both the preparation of scientific advice and fisheries control and surveillance. The monitoring is generally done by human observers, both in port and onboard, with a high cost involved. Consequently, some Regional Fisheries Management Organizations (RFMO) are opting for electronic monitoring (EM) as an alternative or complement to human observers in certain fisheries. This is the case of the tropical tuna purse seine fishery operating in the Indian and Atlantic oceans, which started an EM program on a voluntary basis in 2017. However, even when the monitoring is conducted though EM, the image analysis is a tedious task manually performed by experts. In this paper, we propose a cost-effective methodology for the automatic processing of the images already being collected by cameras onboard tropical tuna purse seiners. Firstly, the images are preprocessed to homogenize them across all vessels and facilitate subsequent steps. Secondly, the fish are individually segmented using a deep neural network (Mask R-CNN). Then, all segments are passed through other deep neural network (ResNet50V2) to classify them by species and estimate their size distribution. For the classification of fish, we achieved an accuracy for all species of over 70%, i.e., about 3 out of 4 individuals are correctly classified to their corresponding species. The size distribution estimates are aligned with official port measurements but calculated using a larger number of individuals. Finally, we also propose improvements to the current image capture systems which can facilitate the work of the proposed automation methodology.
---
