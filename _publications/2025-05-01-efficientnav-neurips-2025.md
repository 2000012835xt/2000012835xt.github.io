---
title: "EfficientNav: Towards On-Device Object-Goal Navigation with Navigation Map Caching and Retrieval"
collection: publications
category: conferences
permalink: /publication/efficientnav-neurips-2025
excerpt: >-
  Object-goal navigation (ObjNav) tasks an agent with navigating to the location of a specific object in an unseen environment. Embodied agents equipped with large language models (LLMs) and online constructed navigation maps can perform ObjNav in a zero-shot manner. However, existing agents heavily rely on giant LLMs on the cloud, e.g., GPT-4, while directly switching to small LLMs, e.g., LLaMA3.2-11b, suffers from significant success rate drops due to limited model capacity for understanding complex navigation maps, which prevents deploying ObjNav on local devices. At the same time, the long prompt introduced by the navigation map description causes high planning latency on local devices. In this paper, we propose EfficientNav to enable on-device efficient LLM-based zero-shot ObjNav. To help the smaller LLMs better understand the environment, we propose semantics-aware memory retrieval to prune redundant information in navigation maps. To reduce planning latency, we propose discrete memory caching and attention-based memory clustering to efficiently save and re-use the KV cache. Extensive experimental results demonstrate that EfficientNav achieves 11.1% improvement in success rate on HM3D benchmark over GPT-4-based baselines, and demonstrates 6.7x real-time latency reduction and 4.7x end-to-end latency reduction over GPT-4 planner. Our code is available at https://github.com/PKU-SEC-Lab/EfficientNav.
date: 2025-12-07
venue: "NeurIPS 2025"
citation: 'Zebin Yang, Sunjian Zheng, <strong>Tong Xie</strong>, Tianshi Xu, Bo Yu, Fan Wang, Jie Tang, Shaoshan Liu, and Meng Li. (2025). &quot;EfficientNav: Towards On-Device Object-Goal Navigation with Navigation Map Caching and Retrieval.&quot; <i>NeurIPS</i>.'
---

Publication entry.
