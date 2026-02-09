---
title: "SparStencil: Retargeting Sparse Tensor Cores to Scientific Stencil Computations via Structured Sparsity Transformation"
collection: publications
category: conferences
permalink: /publication/2025-11-03-sc-sparstencil
excerpt: 'Sparse Tensor Cores offer exceptional performance gains for AI workloads by exploiting structured 2:4 sparsity. However, their potential remains untapped for core scientific workloads such as stencil computations, which exhibit irregular sparsity patterns. This paper presents SparStencil, the first system to retarget sparse TCUs for scientific stencil computations through structured sparsity transformation. SparStencil introduces three key techniques: (1) Adaptive Layout Morphing, which restructures stencil patterns into staircase-aligned sparse matrices via a flatten-and-crush pipeline; (2) Structured Sparsity Conversion, which formulates transformation as a graph matching problem to ensure compatibility with 2:4 sparsity constraints; (3) Automatic Kernel Generation, which compiles transformed stencils into optimized sparse MMA kernels via layout search and table-driven memory mapping. Evaluated on 79 stencil kernels spanning diverse scientific domains, SparStencil achieves up to 7.1x speedup (3.1x on average) over state-of-the-art framework while reducing code complexity and matching or exceeding expert-tuned performance in both compute throughput and memory efficiency.'
date: 2025-11-03
venue: "International Conference for High Performance Computing, Networking, Storage, and Analysis (SC)"
paperurl: 'https://dl.acm.org/doi/10.1145/3712285.3759820'
citation: 'Qi Li, Kun Li, Liang Yuan, Junshi Chen, Hong An, Yunquan Zhang, Ting Cao, Mao Yang. (2025). "SparStencil: Retargeting Sparse Tensor Cores to Scientific Stencil Computations via Structured Sparsity Transformation." <i>SC</i>.'
award: 'SC 2025 Best Student Paper Award Finalist'
---
