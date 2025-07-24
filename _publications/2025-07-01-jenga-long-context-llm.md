---
title: "Jenga: Enhancing Long-Context Fine-tuning of LLMs with Contextual Token Sparsity"
collection: publications
category: conferences
permalink: /publication/2025-07-01-jenga-long-context-llm
excerpt: 'The escalating demand for long-context applications has intensified the necessity of extending the LLM context windows. Despite recent fine-tuning approaches successfully expanding context lengths, their high memory footprints, especially for activations, present a critical practical limitation. Current parameter-efficient fine-tuning methods prioritize reducing parameter update overhead over addressing activation memory constraints. Similarly, existing sparsity mechanisms improve computational efficiency but overlook activation memory optimization due to the phenomenon of Shadowy Activation. In this paper, we propose JENGA, the first LLM fine-tuning system that explores and exploits a new token-level sparsity mechanism inherent in long-context scenarios, termed Contextual Token Sparsity. JENGA minimizes redundant token involvement by assessing the informativeness of token embeddings while preserving model accuracy. Specifically, JENGA introduces three key techniques: (1) Token Elimination, dynamically identifying and excluding redundant tokens across varying inputs and layers. (2) Pattern Prediction, utilizing well-trained predictors to approximate token sparsity patterns with minimal overhead. (3) Kernel Optimization, employing permutation-free and segment-based strategies to boost system performance. We implement JENGA as an end-to-end fine-tuning system compatible with various LLM architectures and other optimization techniques. Comprehensive evaluations demonstrate that JENGA reduces memory consumption by up to 1.93× and achieves up to 1.36× speedups, outperforming state-of-the-art fine-tuning systems.'
date: 2025-07-01
venue: "USENIX Annual Technical Conference (ATC'25)"
paperurl: 'https://www.usenix.org/conference/atc25/presentation/wang-tuowei'
slideurl: 'https://www.usenix.org/sites/default/files/conference/protected-files/atc25_slides_wang_tuowei.pdf'
citation: 'Tuowei Wang, Xingyu Chen, Kun Li, Ting Cao, Ju Ren, Yaoxue Zhang. (2025). "Jenga: Enhancing Long-Context Fine-tuning of LLMs with Contextual Token Sparsity." <i>ATC</i>.'
---
