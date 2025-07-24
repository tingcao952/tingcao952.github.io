---
title: "BitDistiller: Unleashing the Potential of Sub-4-Bit LLMs via Self-Distillation"
collection: publications
category: conferences
permalink: /publication/2024-08-01-acl-bitdistiller
excerpt: 'The upscaling of Large Language Models (LLMs) has yielded impressive advances in natural language processing, yet it also poses significant deployment challenges. Weight quantization has emerged as a widely embraced solution to reduce memory and computational demands. This paper introduces BitDistiller, a framework that synergizes Quantization-Aware Training (QAT) with Knowledge Distillation (KD) to boost the performance of LLMs at ultra-low precisions (sub-4-bit). Specifically, BitDistiller first incorporates a tailored asymmetric quantization and clipping technique to maximally preserve the fidelity of quantized weights, and then proposes a novel Confidence-Aware Kullback-Leibler Divergence (CAKLD) objective, which is employed in a self-distillation manner to enable faster convergence and superior model performance. Empirical evaluations demonstrate that BitDistiller significantly surpasses existing methods in both 3-bit and 2-bit configurations on general language understanding and complex reasoning benchmarks. Notably, BitDistiller is shown to be more cost-effective, demanding fewer data and training resources. The code is available at https://github.com/DD-DuDa/BitDistiller.'
date: 2024-08-01
venue: '62nd Annual Meeting of the Association for Computational Linguistics (ACL 2024 Main Conference, Long paper)'
paperurl: 'https://aclanthology.org/2024.acl-long.7/'
citation: 'DaYou Du, Yijia Zhang, Shijie Cao, Jiaqi Guo, Ting Cao, Xiaowen Chu, Ningyi Xu. (2024). "BitDistiller: Unleashing the Potential of Sub-4-Bit LLMs via Self-Distillation." <i>ACL</i>.'
---