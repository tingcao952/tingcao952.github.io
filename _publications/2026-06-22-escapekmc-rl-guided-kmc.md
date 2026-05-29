---
title: "Pushing a Single GPU to Its Limits and Scaling to Tens of Thousands: RL-Guided, Physically Consistent KMC for Nuclear Materials Simulation"
collection: publications
category: conferences
permalink: /publication/2026-06-22-escapekmc-rl-guided-kmc
excerpt: 'Kinetic Monte Carlo is a cornerstone for rare-event dynamics in materials, but its strict sequentiality and super basin trapping create a scalability deadlock: massive computation advances physical time only marginally, throttling both spatial and temporal scalability. We present EscapeKMC, the first reinforcement learning–guided KMC framework that resolves the scalability deadlock under strict physical alignment. EscapeKMC introduces three techniques: (1) Poisson Clock Alignment anchors event timing to the Poisson law and enables O(1) escape-time estimation; (2) Adaptive Swarm Reasoning distributes decision-making across lightweight atomic agents coordinated by a centralized critic, yielding system-size-invariant policies transferable across scales; and (3) Sparse Dynamics Regularization restructures irregular dynamics into batched, accelerator-friendly execution efficiently. On reactor-pressure-vessel benchmarks, EscapeKMC achieves 17.5× over OpenKMC while maintaining physical fidelity. At extreme scale, it simulates 5.8 × 10^10 atoms on a single NVIDIA A100 GPU with a 500× improvement in memory efficiency. Beyond single-GPU execution, EscapeKMC scales efficiently to large GPU clusters, sustaining 91% parallel efficiency on up to 16,384 GPUs and enabling KMC simulations of up to 1.7×10^14 atoms.'
date: 2026-06-22
venue: 'ISC High Performance 2026'
paperurl: 'https://www.likun.tech/pdf/pap136s3.pdf'
citation: 'Haozhi Han, Qi Li, Ruge Zhang, Haipeng Jia, Yunquan Zhang, Yifeng Chen, Ting Cao, Yunxin Liu, and Kun Li (2026). "Pushing a Single GPU to Its Limits and Scaling to Tens of Thousands: RL-Guided, Physically Consistent KMC for Nuclear Materials Simulation." <i>ISC High Performance 2026</i>.'
---
