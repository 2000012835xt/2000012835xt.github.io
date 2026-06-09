---
title: "ReaLM: Reliable and Efficient Large Language Model Inference with Statistical Algorithm-based Fault Tolerance"
collection: publications
category: conferences
permalink: /publication/realm-dac-2025
excerpt: >-
  Large language models (LLMs) have showcased remarkable performance across various tasks and are increasingly adopted for reliability-critical applications. However, the accelerators on which LLMs are deployed are susceptible to hardware faults due to aging, variation, and cosmic radiation. Algorithm-Based Fault Tolerance (ABFT) is proposed for error detection with algorithm-circuit co-design. However, classical ABFT overlooks the inherent error resilience of LLMs and lacks detailed hardware cost analysis for LLM accelerators, leading to high latency and power overhead. In this paper, we propose ReaLM, a novel algorithm/circuit co-design framework designed for reliable and efficient LLM inference. We first perform a large-scale error injection study of representative LLMs and tasks and systematically characterize the error resilience of different types of faults. Based on the characterization, we propose a statistical ABFT approach that fully captures the error distribution statistics to reduce the recomputation overhead. We also customize the online error detection circuits to enable low-cost statistics collection. With extensive experiments, we demonstrate that with minimal area and power overhead, ReaLM can relax the bit error rate (BER) threshold for recomputation by 115x to 2373x on different network components without compromising model performance. Furthermore, this relaxation reduces recomputation latency by up to 4.09x.
date: 2025-06-22
venue: "DAC 2025"
paperurl: "https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11132610"
citation: '<strong>Tong Xie</strong>, Jiawang Zhao, Zishen Wan, Zuodong Zhang, Yuan Wang, Runsheng Wang, Ru Huang, and Meng Li. (2025). &quot;ReaLM: Reliable and Efficient Large Language Model Inference with Statistical Algorithm-based Fault Tolerance.&quot; <i>DAC</i>.'
---

First-author publication.
