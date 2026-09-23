---
title: "FluidGPU: Fine-Grained Kernel Disaggregation for Large Model Inference on Heterogeneous GPUs"
collection: publications
category: conferences
permalink: /publication/2026-11-15-sc-fluidgpu
excerpt: 'Disaggregation provides a way to utilize heterogeneous GPU clusters, but existing solutions operate at a coarse granularity and are tightly coupled to specific model architectures. FluidGPU is the first kernel disaggregation system designed to improve the performance and cost efficiency of large-model inference on heterogeneous GPUs. It combines offline analysis with online adaptation, extracts precise inter-kernel dependencies from PTX, overlaps communication with computation through pipelined execution, and applies workload-aware scheduling with lightweight runtime adaptation. Across five heterogeneous GPUs and four model architectures, scaling to 16 GPUs, FluidGPU achieves up to 2.3x the serving throughput and 1.6x the cost efficiency of existing disaggregation methods.'
date: 2026-11-15
venue: 'International Conference for High Performance Computing, Networking, Storage, and Analysis (SC)'
paperurl: '/files/FluidGPU.pdf'
citation: 'Tiancheng Hu, Jin Qin, Lei Chen, Junhao Hu, Yuzheng Wang, Mingxing Zhang, Chunwei Xia, Yizhou Shan, Huimin Cui, Ting Cao, Zheng Wang, Tao Xie, Chenxi Wang. (2026). "FluidGPU: Fine-Grained Kernel Disaggregation for Large Model Inference on Heterogeneous GPUs." <i>SC</i>.'
---
