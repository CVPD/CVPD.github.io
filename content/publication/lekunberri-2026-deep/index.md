---
title: Deep learning for accurate vision-based catch composition in tropical tuna
  purse seiners
authors:
- Xabier Lekunberri
- Ahmad Kamal
- Izaro Goienetxea
- Jon Ruiz
- Iñaki Quincoces
- Jaime Valls Miro
- Ignacio Arganda-Carreras
- Jose A Fernandes-Salvador
date: '2026-01-01'
publishDate: '2026-08-24T07:45:25.348071Z'
publication_types:
- article-journal
projects:
- carla-2021
- giu23-022
publication: '*ICES Journal of Marine Science*'
doi: 10.1093/icesjms/fsag151
abstract: "Purse seiners play a crucial role in tuna fishing, as approximately 69%
  of the world's tropical tuna is caught using this gear. All tuna Regional Fisheries
  Management Organizations have established minimum standards for the use of electronic
  monitoring (EM) in fisheries in addition to traditional observers. These EM systems
  produce a massive amount of video data that human analysts must process. Integrating
  artificial intelligence (AI) into their workflow can decrease that workload and
  improve the accuracy of the reports. However, species identification still poses
  significant challenges for AI, as achieving balanced performance across all species
  requires appropriate training data. Here, we quantify the difficulty experts face
  to distinguish bigeye tuna (BET, Thunnus obesus) from yellowfin tuna (YFT, Thunnus
  albacares) using images captured by EM systems. We found inter-expert agreements
  of 42.9% ± 35.6% for BET and 57.1% ± 35.6% for YFT. We then present a multi-stage
  pipeline to estimate the species composition of the catches using a reliable ground-truth
  dataset based on identifications made by observers on board. Three segmentation
  approaches are compared: Mask R-CNN, a combination of DINOv2 with SAM2, and an integration
  of YOLOv9 with SAM2. We found that the latter performs the best, with a validation
  mean average precision of 0.66 ± 0.03 and a recall of 0.85 ± 0.03. Segmented individuals
  are tracked using ByteTrack. For classification, we evaluated a standard multiclass
  classification model and a hierarchical approach. Their performance depended on
  the fishing trip considered, suggesting that both approaches are promising, but
  additional testing is needed to determine which strategy generalizes better overall.
  All our models were cross-validated during training and tested on fishing operations
  with fully known catch composition. Combining YOLOv9-SAM2 with the hierarchical
  classification produced the best estimations, with 84.8% of the individuals being
  segmented and classified with a mean absolute error of 4.5%."
links:
- name: URL
  url: https://doi.org/10.1093/icesjms/fsag151
---
