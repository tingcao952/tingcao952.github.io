---
title: "ConvStencil: Transform Stencil Computation to Matrix Multiplication on Tensor Cores"
collection: publications
category: conferences
permalink: /publication/2024-03-05-ppopp-convstencil
excerpt: 'Tensor Core Unit (TCU) is increasingly integrated into modern high-performance processors to enhance matrix multiplication performance. However, constrained to its over-specification, its potential for improving other critical scientific operations like stencil computations remains untapped. This paper presents ConvStencil1, a novel stencil computing system designed to efficiently transform stencil computation to matrix multiplication on Tensor Cores. We first develop a performance model for ConvStencil to guide algorithm design and optimization on TCUs. Based on this model, we propose three techniques: (1) Memory-efficient Layout Transformation using the stencil2row method; (2) Computation-dense Compute Adaptation with Dual Tessellation and kernel fusion; and (3) Performance-boosting Conflict Removal using a Lookup Table and Dirty Bits Padding. ConvStencil outperforms other stencil optimization frameworks, achieving significant speedups compared to solutions like AMOS, cuDNN, Brick, DRStencil, and TCStencil. By transforming stencil computation on Tensor Cores, ConvStencil promises to improve the performance of various scientific and engineering applications.'
date: 2024-03-05
venue: 'ACM SIGPLAN Annual Symposium on Principles and Practice of Parallel Programming (PPoPP)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3627535.3638476'
citation: 'Yuetao Chen, Kun Li, Yuhao Wang, Donglin Bai, Lei Wang, Lingxiao Ma, Liang Yuan, Yunquan Zhang, Ting Cao, Mao Yang. (2024). "ConvStencil: Transform Stencil Computation to Matrix Multiplication on Tensor Cores." <i>PPoPP</i>.'
---
