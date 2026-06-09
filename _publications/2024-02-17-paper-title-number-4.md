---
title: "DRIFT: Harnessing Inherent Fault Tolerance for Efficient and Reliable Diffusion Model Inference"
collection: publications
category: conferences
permalink: /publication/drift-dac-2026
excerpt: >-
  Diffusion model deployment has been suffering from high energy consumption and inference latency despite its superior performance in visual generation tasks. Dynamic voltage and frequency scaling (DVFS) offers a promising solution to exploit the potential of the underlying accelerators. However, existing approaches often lead to either limited efficiency gains or degraded output quality because they overlook the inherent fault tolerance of the diffusion model. Therefore, in this paper, we propose DRIFT, a novel algorithm-architecture co-optimization framework that harnesses the fault tolerance for efficient and reliable diffusion model inference. We first perform a comprehensive resilience analysis on representative diffusion models. Building on these observations, we introduce a fine-grained, resilience-aware DVFS strategy that selectively protects error-sensitive network blocks and timesteps, and a rollback algorithm-based fault tolerance (ABFT) mechanism that adaptively corrects only critical errors by reverting to previous timesteps. We further optimize offloading intervals and reorganize data layouts to reduce memory overhead. Experiments across diverse models and datasets show that DRIFT can achieve on average 36% energy savings through voltage underscaling or 1.7x speedup via overclocking while maintaining generation quality.
date: 2026-07-26
venue: "DAC 2026"
paperurl: "https://doi.org/10.1145/3770743.3804042"
citation: 'Jinqi Wen*, <strong>Tong Xie*</strong>, Runsheng Wang, and Meng Li. (2026). &quot;DRIFT: Harnessing Inherent Fault Tolerance for Efficient and Reliable Diffusion Model Inference.&quot; <i>DAC</i>.'
---

Co-first-author publication.
