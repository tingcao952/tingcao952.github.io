---
title: "MatXtract: Sparsity-Aware Matrix Transformation via Cascaded Compute Density EXtraction for SpMV"
collection: publications
category: journals
permalink: /publication/2026-01-01-matxtract
excerpt: 'Sparse Matrix-Vector multiplication (SpMV) is a fundamental kernel across scientific computing and graph analytics. Modern GPUs feature specialized processing units such as Tensor Core Units (TCUs) for accelerating dense matrix operations. While recent efforts leverage TCUs for SpMV acceleration, direct TCU-only mappings suffer from poor cache utilization and limited performance generalization across diverse sparse matrices. This paper presents MatXtract, a sparsity-aware matrix transformation framework that restructures sparse matrices through cascaded compute density extraction, enabling efficient TCU-accelerated SpMV. MatXtract introduces three key components: 1) Compute Density Extraction optimizes memory hierarchy utilization while creating Tensor Core- and CUDA core-friendly computation substrates to enhance TCU compute density and CUDA core load balancing; 2) Cascaded Execution Kernel employs a two-stage cascaded compression that systematically exploits hierarchical sparsity to maximize GPU computational throughput; and 3) Sparsity-Aware Predictor mitigates the mismatch between fixed TCU computation and diverse sparsity through Bayesian optimization for enhanced performance generalization. Extensive evaluations on 2,059 matrices show that MatXtract outperforms cuSPARSE, DASP, CSR5, and Merge-SpMV, achieving higher performance on 96.64% of matrices, with an average 1.98 × and up to 8.83 × speedup over cuSPARSE on NVIDIA A100 GPUs.'
date: 2026-01-27
venue: 'ACM Transactions on Architecture and Code Optimization (TACO)'
paperurl: 'https://dl.acm.org/doi/10.1145/3793864'
citation: 'Luhan Wang, Kun Li*, Yifeng Chen, Haipeng Jia, Yunquan Zhang, Ting Cao, Yunxin Liu. (2026). "MatXtract: Sparsity-Aware Matrix Transformation via Cascaded Compute Density EXtraction for SpMV." <i>TACO</i>.'
award: 'Selected for ACM Showcase'
awardurl: 'https://www.growkudos.com/publications/10.1145%25252F3793864/reader'
---
