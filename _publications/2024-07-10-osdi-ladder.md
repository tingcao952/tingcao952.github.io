---
title: "Ladder: Enabling Efficient Low-Precision Deep Learning Computing through Hardware-aware Tensor Transformation"
collection: publications
category: conferences
permalink: /publication/2024-07-10-osdi-ladder
excerpt: 'The increasing demand for improving deep learning model performance has led to a paradigm shift in supporting low-precision computation to harness the robustness of deep learning to errors. Despite the emergence of new low-precision data types and optimization approaches, existing hardware and software have insufficient and inefficient support for those evolving data types, making it challenging to achieve real performance gains through low-precision computing. This paper introduces Ladder, a novel compiler designed to bridge the gap between evolving custom data types and the fixed precision formats supported by current hardware. Leveraging a general type system, tType, and an extended tensor expression, Ladder transforms deep neural network (DNN) computations into optimized computing pipelines with custom data types as the first-class citizen, exposing an optimization space for efficiently handling data storage, accesses, and type conversions. Ladder employs a new set of tensor scheduling primitives and a hardware-aware optimization policy to navigate the complex transformation space, ensuring optimal performance across different memory layers and DNN operators.'
date: 2024-07-10
venue: 'The 18th USENIX Symposium on Operating Systems Design and Implementation (OSDI)'
paperurl: 'https://www.usenix.org/system/files/osdi24-wang-lei.pdf'
citation: 'L. Wang, L. Ma, S. Cao, Q. Zhang, J. Xue, Y. Shi, N. Zheng, Z. Miao, F. Yang, Ting Cao, Y. Yang, M. Yang. (2024). "Ladder: Enabling Efficient Low-Precision Deep Learning Computing through Hardware-aware Tensor Transformation." <i>OSDI</i>.'
---
