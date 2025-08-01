---
title: "Constraint-aware and Ranking-distilled Token Pruning for Efficient Transformer Inference"
collection: publications
category: conferences
permalink: /publication/2023-10-01-kdd-tokenpruning
excerpt: 'Deploying pre-trained transformer models like BERT on downstream tasks in resource-constrained scenarios is challenging due to their high inference cost, which grows rapidly with input sequence length. In this work, we propose a constraint-aware and ranking-distilled token pruning method ToP, which selectively removes unnecessary tokens as input sequence passes through layers, allowing the model to improve online inference speed while preserving accuracy. ToP overcomes the limitation of inaccurate token importance ranking in the conventional self-attention mechanism through a ranking-distilled token distillation technique, which distills effective token rankings from the final layer of unpruned models to early layers of pruned models. Then, ToP introduces a coarse-to-fine pruning approach that automatically selects the optimal subset of transformer layers and optimizes token pruning decisions within these layers through improved L0 regularization. Extensive experiments on GLUE benchmark and SQuAD tasks demonstrate that ToP outperforms state-of-the-art token pruning and model compression methods with improved accuracy and speedups. ToP reduces the average FLOPs of BERT by 8.1X while achieving competitive accuracy on GLUE, and provides a real latency speedup of up to 7.4X on an Intel CPU. Code is available at https://github.com/microsoft/Moonlit/tree/main/ToP'
date: 2023-10-01
venue: 'ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3580305.3599284'
citation: 'Junyan Li, Li Lyna Zhang, Jiahang Xu, Yujing Wang, Shaoguang Yan, Yunqing Xia, Yuqing Yang, Ting Cao, Hao Sun, Weiwei Deng, Qi Zhang, Mao Yang. (2023). "Constraint-aware and Ranking-distilled Token Pruning for Efficient Transformer Inference." <i>ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD)</i>.'
---
