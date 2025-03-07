---
title: Optimizing Video Analytics Deployment for In-Flight Cabin Readiness Verification
authors:
- Unai Elordi
- Nerea Aranjuelo
- Luis Unzueta
- Jose Luis Apellaniz
- Ignacio Arganda-Carreras
date: '2023-01-01'
publishDate: '2025-02-05T09:06:52.045193Z'
publication_types:
- article-journal
publication: '*IEEE Access*'
doi: 10.1109/ACCESS.2023.3309050
abstract: This paper proposes an approach to optimize the deployment of on-board video analytics for checking the correct positioning of luggage in aircraft cabins. The system consists of embedded cameras installed on top of the cabin and a heterogeneous embedded processor. Each camera covers multiple regions of interest (i.e., multiple seats or aisle sections) to minimize the number of cameras required. Each image region is processed by a separate image classification algorithm trained with the expected kind of visual appearance considering the effect of perspective and lens distortion. They classify these regions as correct or incorrect for cabin readiness by exploiting the hierarchical structure of classes composed of different configurations of passengers’ and objects’ presence or absence and the objects’ location. Our approach leverages semantic distances between classes to guide prototypical neural networks for multi-tasking between the main classification (i.e., correct or incorrect status) and auxiliary attributes (i.e., scene configurations), learning robust features from different data domains (i.e., various cabins, real or synthetic). The processing pipeline optimizes response delay and power consumption by leveraging embedded processors’ computing capabilities. We carried out experiments in a cabin mockup with a Jetson AGX Xavier, efficiently obtaining better-quality descriptive information from the scene to improve the system’s accuracy compared to alternative state-of-the-art methods.
links:
- name: URL
  url: https://doi.org/10.1109/ACCESS.2023.3309050

---
