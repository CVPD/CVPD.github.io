---
title: Deep Learning with Discriminative Margin Loss for Cross-Domain Consumer-to-Shop
  Clothes Retrieval
authors:
- Pendar Alirezazadeh
- Fadi Dornaika
- Abdelmalik Moujahid
date: '2022-01-01'
publishDate: '2025-06-13T10:28:35.713554Z'
publication_types:
- article-journal
publication: '*Sensors*'
doi: 10.3390/s22072660
abstract: Consumer-to-shop clothes retrieval refers to the problem of matching photos
  taken by customers with their counterparts in the shop. Due to some problems, such
  as a large number of clothing categories, different appearances of clothing items
  due to different camera angles and shooting conditions, different background environments,
  and different body postures, the retrieval accuracy of traditional consumer-to-shop
  models is always low. With advances in convolutional neural networks (CNNs), the
  accuracy of garment retrieval has been significantly improved. Most approaches addressing
  this problem use single CNNs in conjunction with a softmax loss function to extract
  discriminative features. In the fashion domain, negative pairs can have small or
  large visual differences that make it difficult to minimize intraclass variance
  and maximize interclass variance with softmax. Margin-based softmax losses such
  as Additive Margin-Softmax (aka CosFace) improve the discriminative power of the
  original softmax loss, but since they consider the same margin for the positive
  and negative pairs, they are not suitable for cross-domain fashion search. In this
  work, we introduce the cross-domain discriminative margin loss (DML) to deal with
  the large variability of negative pairs in fashion. DML learns two different margins
  for positive and negative pairs such that the negative margin is larger than the
  positive margin, which provides stronger intraclass reduction for negative pairs.
  The experiments conducted on publicly available fashion datasets DARN and two benchmarks
  of the DeepFashion dataset—(1) Consumer-to-Shop Clothes Retrieval and (2) InShop
  Clothes Retrieval—confirm that the proposed loss function not only outperforms the
  existing loss functions but also achieves the best performance.
links:
- name: URL
  url: https://www.mdpi.com/1424-8220/22/7/2660
---
