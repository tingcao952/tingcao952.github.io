---
title: "Efficient GPU Kernels for N:M-SPARSE Weights in Deep Learning"
collection: publications
category: conferences
permalink: /publication/2023-06-01-mlsys-nm-sparse
excerpt: 'N:M sparsity is becoming increasingly popular due to its promise to achieve both high model accuracy and computational efficiency for deep learning. However, the real-world benefit of N:M sparsity is limited as there is a lack of dedicated GPU kernel implementations for general N:M sparsity with various sparsity ratios. In this work, we present nmSPARSE, a library of efficient GPU kernels for two fundamental operations in neural networks with N:M sparse weights: sparse matrix-vector multiplication (SpMV) and sparse matrix-matrix multiplication (SpMM). By leveraging the intrinsic balance characteristic of N:M sparsity, nmSPARSE kernels rearrange irregular computation and scattered memory accesses in sparse matrix multiplication into hardware-aligned regular computation and conflict-free memory accesses at runtime. Evaluated on NVIDIA A100 GPU, nmSPARSE kernels achieve up to 5.2× speedup on SpMV and 6.0× speedup on SpMM over the fastest baseline. End-to-end studies on transformer models demonstrate that using nmSPARSE outperforms other baselines.'
date: 2023-06-01
venue: 'Sixth Conference on Machine Learning and Systems (MLSys)'
paperurl: 'https://proceedings.mlsys.org/paper_files/paper/2023/hash/a10deb4d5227a8ea307ea8ff3cb712f4-Abstract-mlsys2023.html'
citation: 'Bin Lin, Ningxin Zheng, Lei Wang, Shijie Cao, Lingxiao Ma, Quanlu Zhang, Yi Zhu, Ting Cao, Jilong Xue, Yuqing Yang, Fan Yang. (2023). "Efficient GPU Kernels for N:M-SPARSE Weights in Deep Learning." <i>Sixth Conference on Machine Learning and Systems (MLSys)</i>.'
---
