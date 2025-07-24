---
title: "Long Exposure: Accelerating Parameter-Efficient Fine-Tuning for LLMs under Shadowy Sparsity"
collection: publications
category: conferences
permalink: /publication/2024-11-01-sc-longexposure
excerpt: 'The adaptation of pre-trained large language models (LLMs) to diverse downstream tasks via fine-tuning is critical for numerous applications. However, the inefficiency of parameterefficient fine-tuning (PEFT) techniques presents significant challenges in terms of time investments and operational costs. In this paper, we first introduce a nuanced form of sparsity, termed Shadowy Sparsity, which is distinctive in fine-tuning and has not been adequately addressed for acceleration. Under Shadowy Sparsity, we propose Long Exposure 1, an efficient system to accelerate PEFT for LLMs. Long Exposure comprises three key components: Shadowy-sparsity Exposer employs a prolonged sensing range to capture more sparsity details under shadowy sparsity; Sequence-oriented Predictor provides efficient yet accurate predictions to handle large sequence inputs and constantly-evolving parameters; and Dynamic-aware Operator facilitates more structured computational patterns and coalesced memory accesses, addressing dynamic sparse operations. Extensive evaluations show that Long Exposure outperforms state-of-the-arts with up to a 2.49× speedup in end-to-end fine-tuning, offering promising advancements in accelerating PEFT for LLMs.1Long Exposure is available at https://github.com/HPHEX/LongExposure.'
date: 2024-11-01
venue: 'International Conference for High Performance Computing, Networking, Storage, and Analysis (SC’24)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10793187'
citation: 'Tuowei Wang, Kun Li, Zixu Hao, Donglin Bai, Ju Ren, Yaoxue Zhang, Ting Cao, Mao Yang. (2024). "Long Exposure: Accelerating Parameter-Efficient Fine-Tuning for LLMs under Shadowy Sparsity." <i>SC’24</i>.'
---