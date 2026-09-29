---
title: "PyramidFFT: Rearchitecting FFT with Matrix-Aligned Nested-Radix for Hierarchical Scratchpad Memory on AI Accelerators"
collection: publications
category: journals
permalink: /publication/2026-07-24-taco-pyramidfft
excerpt: 'Emerging AI accelerators offer high compute throughput and large scratchpad memories, but hierarchical scratchpad organization is poorly utilized by memory-bound FFT workloads. PyramidFFT is a memory-efficient FFT system co-designed for AI accelerators with large-capacity scratchpad memory. It combines a Memory-Aware Nested Network Design that reduces memory access frequency, Matrix-Aligned Butterfly Layout Optimization that adapts butterfly parallelism and data layout for Tensor Core Units, and Symmetry-Driven Real FFT Compression that removes conjugate-symmetric components. PyramidFFT achieves up to an 8.2x efficiency improvement over a baseline without memory-hierarchy mapping, bridging FFT memory behavior with the compute-dense design of modern AI accelerators.'
date: 2026-07-24
venue: 'ACM Transactions on Architecture and Code Optimization (TACO)'
paperurl: 'https://dl.acm.org/doi/full/10.1145/3819240'
citation: 'Xiang Zhao, Ruge Zhang, Haipeng Jia, Kun Li, Jianliang Xu, Ting Cao, Yunxin Liu, Yunquan Zhang. (2026). "PyramidFFT: Rearchitecting FFT with Matrix-Aligned Nested-Radix for Hierarchical Scratchpad Memory on AI Accelerators." <i>ACM Transactions on Architecture and Code Optimization</i>.'
---
