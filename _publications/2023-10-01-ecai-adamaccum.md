---
title: "Adam Accumulation to Reduce Memory Footprints of both Activations and Gradients for Large-scale DNN Training"
collection: publications
category: conferences
permalink: /publication/2023-10-01-ecai-adamaccum
excerpt: 'Running out of GPU memory has become a main bottleneck for large-scale DNN training. How to reduce the memory footprint during training has received intensive research attention. We find that previous gradient accumulation reduces activation memory but fails to be compatible with gradient memory reduction due to a contradiction between preserving gradients and releasing gradients. To address this issue, we propose a novel optimizer accumulation method for Adam, named Adam Accumulation (AdamA), which enables reducing both activation and gradient memory. Specifically, AdamA directly integrates gradients into optimizer states and accumulates optimizer states over micro-batches, so that gradients can be released immediately after use. We mathematically and experimentally demonstrate AdamA yields the same convergence properties as Adam. Evaluated on transformer-based models, AdamA achieves up to 23% memory reduction compared to gradient accumulation with less than 2% degradation in training throughput. Notably, AdamA can work together with memory reduction methods for optimizer states to fit 1.26x~3.14x larger models over PyTorch and DeepSpeed baseline on GPUs with different memory capacities.'
date: 2023-10-01
venue: '26th European Conference on Artificial Intelligence (ECAI)'
paperurl: 'https://arxiv.org/abs/2305.19982'
citation: 'Yijia Zhang, Yibo Han, Shijie Cao, Guohao Dai, Youshan Miao, Ting Cao, Fan Yang, Ningyi Xu. (2023). "Adam Accumulation to Reduce Memory Footprints of both Activations and Gradients for Large-scale DNN Training." <i>ECAI</i>.'
---
