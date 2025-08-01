---
title: "Romou: Rapidly Generate High-Performance Tensor Kernels for Mobile GPUs"
collection: publications
category: conferences
permalink: /publication/2022-10-01-mobicom-romou
excerpt: 'Mobile GPU, as a ubiquitous and powerful accelerator, plays an important role in accelerating on-device DNN (Deep Neural Network) inference. The frequent-upgrade and diversity of mobile GPUs require automatic kernel generation to empower fast DNN deployment. However, current generated kernels have poor performance. The goal of this paper is to rapidly generate high-performance kernels for diverse mobile GPUs. The major challenges are (1) it is unclear about what is the optimal kernel due to the lack of hardware knowledge; (2) how to rapidly generate it from a large space of candidates. For the first challenge, we propose a cross-platform profiling tool, the first to disclose and quantify mobile GPU architecture. The result demystifies the hardware bottleneck, and also directs the solution for the second challenge by exposing the unique hardware feature, identifying inefficient kernels against hardware constraints, and specifying performance bound for kernels. Directed by that, we propose a mobile-GPU-specific kernel compiler Romou. It supports the unique hardware feature in kernel implementation, and prunes inefficient ones against hardware resources. Romou can thus rapidly generate high-performance kernels. Compared to the state-of-the-art generated kernels, it achieves up-to 14.7X speedup on average for convolution. Up-to 99% search space is pruned. The performance is even up-to 1.2X faster on average than the state-of-the-art hand-optimized implementation.'
date: 2022-10-01
venue: 'Proceedings of the 28th Annual International Conference on Mobile Computing and Networking (MobiCom)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3495243.3517020'
citation: 'Rendong Liang, Ting Cao, Jicheng Wen, Manni Wang, Yang Wang, Jianhua Zou, Yunxin Liu. (2022). "Romou: Rapidly Generate High-Performance Tensor Kernels for Mobile GPUs." <i>Proceedings of the 28th Annual International Conference on Mobile Computing and Networking (MobiCom)</i>.'
---
