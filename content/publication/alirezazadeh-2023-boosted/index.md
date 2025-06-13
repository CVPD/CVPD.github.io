---
title: Boosted Additive Angular Margin Loss for breast cancer diagnosis from histopathological
  images
authors:
- Pendar Alirezazadeh
- Fadi Dornaika
date: '2023-01-01'
publishDate: '2025-06-13T10:28:35.690880Z'
publication_types:
- article-journal
publication: '*Computers in Biology and Medicine*'
doi: 10.1016/j.compbiomed.2023.107528
abstract: Pathologists use biopsies and microscopic examination to accurately diagnose
  breast cancer. This process is time-consuming, labor-intensive, and costly. Convolutional
  neural networks (CNNs) offer an efficient and highly accurate approach to reduce
  analysis time and automate the diagnostic workflow in pathology. However, the softmax
  loss commonly used in existing CNNs leads to noticeable ambiguity in decision boundaries
  and lacks a clear constraint for minimizing within-class variance. In response to
  this problem, a solution in the form of softmax losses based on angular margin was
  developed. These losses were introduced in the context of face recognition, with
  the goal of integrating an angular margin into the softmax loss. This integration
  improves discrimination features during CNN training by effectively increasing the
  distance between different classes while reducing the variance within each class.
  Despite significant progress, these losses are limited to target classes only when
  margin penalties are applied, which may not lead to optimal effectiveness. In this
  paper, we introduce Boosted Additive Angular Margin Loss (BAM) to obtain highly
  discriminative features for breast cancer diagnosis from histopathological images.
  BAM not only penalizes the angle between deep features and their target class weights,
  but also considers angles between deep features and non-target class weights. We
  performed extensive experiments on the publicly available BreaKHis dataset. BAM
  achieved remarkable accuracies of 99.79%, 99.86%, 99.96%, and 97.65% for magnification
  levels of 40X, 100X, 200X, and 400X, respectively. These results show an improvement
  in accuracy of 0.13%, 0.34%, and 0.21% for 40X, 100X, and 200X magnifications, respectively,
  compared to the baseline methods. Additional experiments were performed on the BACH
  dataset for breast cancer classification and on the widely accepted LFW and YTF
  datasets for face recognition to evaluate the generalization ability of the proposed
  loss function. The results show that BAM outperforms state-of-the-art methods by
  increasing the decision space between classes and minimizing intra-class variance,
  resulting in improved discriminability.
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0010482523009939
---
