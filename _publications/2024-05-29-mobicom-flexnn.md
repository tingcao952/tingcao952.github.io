---
title: "FlexNN: Efficient and Adaptive DNN Inference on Memory-Constrained Edge Devices"
collection: publications
category: conferences
permalink: /publication/2024-05-29-mobicom-flexnn
excerpt: 'Due to the popularity of deep neural networks (DNNs) and considerations over network overhead, data privacy, and inference latency, there is a growing interest in deploying DNNs to edge devices in recent years. However, the limited memory becomes a major bottleneck for on-device DNN deployment, making it crucial to reduce the memory footprint of DNN. The mainstream model customization solutions require intensive deployment efforts and may lead to severe accuracy degradation, and existing deep learning (DL) frameworks don not take memory as a priority. Besides, recent works to enhance the memory management scheme cannot be directly applied because of several challenges, including the unbalanced memory footprint across layers, the inevitable overhead of memory management, and the memory budget dynamicity. To tackle these challenges, we introduce FlexNN, an efficient and adaptive memory management framework for DNN inference on memory-constrained devices. FlexNN uses a slicing-loading-computing joint planning approach, to achieve optimal memory utilization and minimal memory management overhead. We implemented FlexNN atop NCNN, and conducted comprehensive evaluations with common model architectures on various devices. The results have shown that our approach is able to adapt to different memory constraints with optimal latency-memory trade-offs. For example, FlexNN can reduce the memory consumption by 93.81% with only a 3.64% increase in latency, as compared with the original NCNN on smartphones.'
date: 2024-05-29
venue: 'The 30th Annual International Conference On Mobile Computing And Networking (MobiCom)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3636534.3649391'
citation: 'Xiangyu Li, Yuanchun Li, Yuanzhe Li, Ting Cao, Yunxin Liu. (2024). "FlexNN: Efficient and Adaptive DNN Inference on Memory-Constrained Edge Devices." <i>MobiCom</i>.'
---
