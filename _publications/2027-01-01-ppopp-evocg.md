---
title: "EvoCG: Self-Evolving Precision Control for Faster Conjugate Gradient"
collection: publications
category: conferences
permalink: /publication/2027-01-01-ppopp-evocg
excerpt: 'Modern GPUs offer far higher throughput in low precision than in FP64, but exploiting this in conjugate gradient (CG) solvers is difficult because tolerance to reduced precision evolves with the Krylov state. We present EvoCG, a mixed-precision CG solver that treats tile-wise precision as an online control action rather than a fixed setting: a reinforcement-learning policy in the iteration loop selects per-tile precision from the evolving solver state, made profitable by co-design with a Tile-CSC unified mixed-precision SpMV kernel and a low-overhead in-loop runtime. Across 47 SPD matrices from eight scientific domains, EvoCG is the fastest solver overall, with average speedups of 2.52×, 3.06×, 2.48×, 1.93×, and 6.99× over cuSPARSE, PETSc, Ginkgo, Mille, and Mille-mixed. On the same substrate, it improves time-to-solution over EvoCG-FP64 by 1.28× at only 11.4% more iterations and 1.09% overhead, with FP64-recomputed final true-residual norms nearly identical to those of FP64, and extends to Jacobi-preconditioned CG without retraining for a further 1.15× speedup.'
date: 2027-01-01
venue: 'ACM SIGPLAN Symposium on Principles and Practice of Parallel Programming (PPoPP)'
citation: 'Jiaqi Zhai, Haozhi Han, Kaiyi Huang, Wenju Zhao, Yifeng Chen, Yunquan Zhang, Ting Cao, Yunxin Liu, Hai Jin, Xuanhua Shi*, Kun Li*. (2027). "EvoCG: Self-Evolving Precision Control for Faster Conjugate Gradient." <i>PPoPP</i>.'
---
