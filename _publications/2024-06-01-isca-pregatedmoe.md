---
title: "Pre-gated MoE: An Algorithm-System Co-Design for Fast and Scalable Mixture-of-Expert Inference"
collection: publications
category: conferences
permalink: /publication/2024-06-01-isca-pregatedmoe
excerpt: 'Large language models (LLMs) based on transformers have made significant strides in recent years, the success of which is driven by scaling up their model size. Despite their high algorithmic performance, the computational and memory requirements of LLMs present unprecedented challenges. To tackle the high compute requirements of LLMs, the Mixture-ofExperts (MoE) architecture was introduced which is able to scale its model size without proportionally scaling up its computational requirements. Unfortunately, MoE’s high memory demands and dynamic activation of sparse experts restrict its applicability to real-world problems. Previous solutions that offload MoE’s memory-hungry expert parameters to CPU memory fall short because the latency to migrate activated experts from CPU to GPU incurs high performance overhead. Our proposed Pre-gated MoE system effectively tackles the compute and memory challenges of conventional MoE architectures using our algorithm-system codesign. Pre-gated MoE employs our novel pre-gating function which alleviates the dynamic nature of sparse expert activation, allowing our proposed system to address the large memory footprint of MoEs while also achieving high performance. We demonstrate that Pre-gated MoE is able to improve performance, reduce GPU memory consumption, while also maintaining the same level of model quality. These features allow our Pre-gated MoE system to cost-effectively deploy large-scale LLMs using just a single GPU with high performance.'
date: 2024-06-01
venue: 'The 51st Annual International Symposium on Computer Architecture 2024 (ISCA’24)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10609634'
citation: 'R. Hwang, J. Wei, S. Cao, C. Hwang, X. Tang, Ting Cao, M. Yang. (2024). "Pre-gated MoE: An Algorithm-System Co-Design for Fast and Scalable Mixture-of-Expert Inference." <i>ISCA’24</i>.'
award: 'Microsoft Research Focus 2024'
awardurl: 'https://www.microsoft.com/en-us/research/blog/research-focus-week-of-july-15-2024/'
---