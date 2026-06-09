---
title: "SpecMamba: Accelerating Mamba Inference on FPGA with Speculative Decoding"
collection: publications
category: conferences
permalink: /publication/specmamba-iccad-2025
excerpt: >-
  The growing demand for efficient long-sequence modeling on edge devices has propelled widespread adoption of State Space Models (SSMs) like Mamba, due to their superior computational efficiency and scalability. As its autoregressive generation process remains memory-bound, speculative decoding has been proposed that incorporates draft model generation and target model verification. However, directly applying speculative decoding to SSMs faces three key challenges: (1) hidden state backtracking difficulties, (2) tree-based parallel verification incompatibility, and (3) hardware workload mismatch. To address these challenges, we propose SpecMamba, the first FPGA-based accelerator for Mamba with speculative decoding, which features system, algorithm, and hardware co-design. At the system level, we present a memory-aware hybrid backtracking strategy to coordinate both models. At the algorithm level, we propose first-in-first-out (FIFO)-based tree verification with tiling to minimize memory access. At the hardware level, we customize a dataflow that computes linear layers in parallel and SSM layers in series to enable maximal overlapping. Implemented on AMD FPGA platforms (VHK158 and VCK190), SpecMamba achieves a 2.27x speedup over GPU baselines and a 2.85x improvement compared to prior FPGA solutions, while demonstrating 5.41x and 1.26x higher energy efficiency, respectively.
date: 2025-10-30
venue: "ICCAD 2025"
citation: 'Linfeng Zhong, Songqiang Xu, Huifeng Wen, <strong>Tong Xie</strong>, Qingyu Guo, Yuan Wang, and Meng Li. (2025). &quot;SpecMamba: Accelerating Mamba Inference on FPGA with Speculative Decoding.&quot; <i>ICCAD</i>.'
---

Publication entry.
