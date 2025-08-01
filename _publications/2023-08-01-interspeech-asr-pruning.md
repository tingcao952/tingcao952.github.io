---
title: "Accurate and Structured Pruning for Efficient Automatic Speech Recognition"
collection: publications
category: conferences
permalink: /publication/2023-08-01-interspeech-asr-pruning
excerpt: 'Automatic Speech Recognition (ASR) has seen remarkable advancements with deep neural networks, such as Transformer and Conformer. However, these models typically have large model sizes and high inference costs, posing a challenge to deploy on resource-limited devices. In this paper, we propose a novel compression strategy that leverages structured pruning and knowledge distillation to reduce the model size and inference cost of the Conformer model while preserving high recognition performance. Our approach utilizes a set of binary masks to indicate whether to retain or prune each Conformer module, and employs L0 regularization to learn the optimal mask values. To further enhance pruning performance, we use a layerwise distillation strategy to transfer knowledge from unpruned to pruned models. Our method outperforms all pruning baselines on the widely used LibriSpeech benchmark, achieving a 50% reduction in model size and a 28% reduction in inference cost with minimal performance loss.'
date: 2023-08-01
venue: 'Conference of the International Speech Communication Association (INTERSPEECH)'
paperurl: 'https://arxiv.org/abs/2305.19549'
citation: 'Huiqiang Jiang, Li Lyna Zhang, Yuang Li, Yu Wu, Shijie Cao, Ting Cao, Yuqing Yang, Jinyu Li, Mao Yang, Lili Qiu. (2023). "Accurate and Structured Pruning for Efficient Automatic Speech Recognition." <i>Conference of the International Speech Communication Association (INTERSPEECH)</i>.'
---
