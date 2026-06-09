---
title: "ASCEND: Accurate yet Efficient End-to-end Stochastic Computing Acceleration of Vision Transformer"
collection: publications
category: conferences
permalink: /publication/ascend-date-2024
excerpt: >-
  Stochastic computing (SC) has emerged as a promising computing paradigm for neural acceleration. However, how to accelerate the state-of-the-art Vision Transformer (ViT) with SC remains unclear. Unlike convolutional neural networks, ViTs introduce notable compatibility and efficiency challenges because of their nonlinear functions, e.g., softmax and Gaussian Error Linear Units (GELU). In this paper, for the first time, a ViT accelerator based on end-to-end SC, dubbed ASCEND, is proposed. ASCEND co-designs the SC circuits and ViT networks to enable accurate yet efficient acceleration. To overcome the compatibility challenges, ASCEND proposes a novel deterministic SC block for GELU and leverages an SC-friendly iterative approximate algorithm to design an accurate and efficient softmax circuit. To improve inference efficiency, ASCEND develops a two-stage training pipeline to produce accurate low-precision ViTs. With extensive experiments, we show the proposed GELU and softmax blocks achieve 56.3% and 22.6% error reduction compared to existing SC designs, respectively, and reduce the area-delay product (ADP) by 5.29x and 12.6x, respectively. Moreover, compared to the baseline low-precision ViTs, ASCEND also achieves significant accuracy improvements on CIFAR10 and CIFAR100.
date: 2024-03-24
venue: "DATE 2024"
paperurl: "https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10546691"
citation: '<strong>Tong Xie</strong>, Yixuan Hu, Renjie Wei, Meng Li, Yuan Wang, Runsheng Wang, and Ru Huang. (2024). &quot;ASCEND: Accurate yet Efficient End-to-end Stochastic Computing Acceleration of Vision Transformer.&quot; <i>DATE</i>.'
---

First-author publication.
