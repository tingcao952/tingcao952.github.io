---
title: "Integer or Floating Point? New Outlooks for Low-Bit Quantization on Large Language Models"
collection: publications
category: conferences
permalink: /publication/2024-07-01-icme-intfloatllm
excerpt: 'Efficient deployment of Large Language Models (LLMs) requires low-bit quantization to reduce model size and inference cost. Besides low-bit integer formats (e.g., INT8/INT4) used in previous quantization works, emerging low-bit floating-point formats (e.g., FP8/FP4) supported by advanced hardware like NVIDIA’s H100 GPU offer an alternative. Our study finds that introducing floating-point formats significantly improves LLMs quantization. We also discover that the optimal quantization format varies across layers. Therefore, we select the optimal format for each layer, which we call the Mixture of Formats Quantization (MoFQ) method. Our MoFQ method achieves better or comparable results over current methods in weight-only (W-only) and weight-activation (WA) post-training quantization scenarios across various tasks, with no additional hardware overhead.'
date: 2024-07-01
venue: 'IEEE International Conference on Multimedia and Expo (ICME’24)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10688089'
citation: 'Yijia Zhang, Lingran Zhao, Shijie Cao, Wenqiang Wang, Ting Cao, Fan Yang, Mao Yang, Shanghang Zhang, Ningyi Xu. (2024). "Integer or Floating Point? New Outlooks for Low-Bit Quantization on Large Language Models." <i>ICME’24</i>.'
---