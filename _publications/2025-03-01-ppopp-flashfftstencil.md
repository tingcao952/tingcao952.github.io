---
title: "FlashFFTStencil: Bridging Fast Fourier Transforms to Memory-Efficient Stencil Computations on Tensor Core Units"
collection: publications
category: conferences
permalink: /publication/2025-03-01-ppopp-flashfftstencil
excerpt: 'While Tensor Core Units (TCUs) excel in AI tasks, their application to HPC algorithms like stencil computations faces significant challenges due to sparsity, which leads to underutilization and exacerbates memory-bound limitations. This paper introduces FlashFFTStencil1, a memory-efficient stencil computing system designed to bridge FFT to fully-dense stencil computations on TCUs. Aimed at bound shifting, FlashFFTStencil comprises three key techniques: Kernel Tailoring on HBM fuses distinct kernels to enhance parallelism while reducing memory transfer and footprint; Architecture Aligning on SMEM restructures FFT-based stencil computations into dense matrix multiplications tailored for shared memory architecture; Computation Streamlining on TCU optimizes TCU utilization and thread parallelism by minimizing pipeline stalls and maximizing register reuse. Notably, a distinctive extension is FlashFFTStencil ability to enable theoretically unrestricted temporal fusion by FFT. Results show that FlashFFTStencil achieves effective sparsity-free bound shifting, with an average speedup of 2.57x over the state-of-the-art. FlashFFTStencil pioneers a new era in unifying computational patterns within the HPC landscape and bridges them with cutting-edge AI-driven hardware innovations like TCUs.'
date: 2025-03-01
venue: '30th ACM SIGPLAN Annual Symposium on Principles and Practice of Parallel Programming (PPoPP)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3710848.3710897'
citation: 'Haozhi Han, Kun Li, Wei Cui, Donglin Bai, Yifeng Chen, Ting Cao, Mao Yang. (2025). "FlashFFTStencil: Bridging Fast Fourier Transforms to Memory-Efficient Stencil Computations on Tensor Core Units." <i>PPoPP</i>.'
---
