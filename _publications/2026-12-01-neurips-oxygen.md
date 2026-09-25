---
title: "OxyGen: Unified KV Cache Management for VLA Inference under Multi-Task Parallelism"
collection: publications
category: conferences
permalink: /publication/2026-12-01-neurips-oxygen
excerpt: 'Embodied AI agents increasingly execute multiple tasks in parallel from shared observations, but existing VLA inference systems suffer from redundant computation and resource contention caused by isolated KV cache management. OxyGen treats the KV cache as a shared resource across tasks and time, enabling cross-task KV sharing and cross-frame continuous batching. Implemented for pi-0.5 and evaluated on NVIDIA RTX 4090 and Jetson AGX Thor platforms, OxyGen achieves up to 3.7x speedup while simultaneously delivering over 200 tokens/s language throughput and 70 Hz action frequency without degrading action quality.'
date: 2026-12-01
venue: 'Conference on Neural Information Processing Systems (NeurIPS)'
paperurl: 'https://arxiv.org/abs/2603.14371'
citation: 'Xiangyu Li, Huaizhi Tang, Xin Ding, Weijun Wang, Ting Cao, Yunxin Liu. (2026). "OxyGen: Unified KV Cache Management for VLA Inference under Multi-Task Parallelism." <i>NeurIPS</i>.'
---
