---
title: "Efficient and Adaptive Diffusion Model Inference Through Lookup Table on Mobile Devices"
collection: publications
category: conferences
permalink: /publication/2025-04-04-tmc-lut-diffusion
excerpt: 'Diffusion models have revolutionized image synthesis applications. Many studies focus on using approximate computation such as model quantization to reduce inference costs on mobile devices. However, due to their extensive model parameters and autoregressive inference fashion, the overhead of diffusion models remains high, which is challenging for mobile devices to handle. To reduce the inference overhead of diffusion models on mobile devices, we propose LUT-Diff, an algorithm-system co-design specifically tailored for mobile device diffusion model inference optimization. LUT-Diff optimizes using lookup tables and can efficiently generate a series of lookup table candidates for diffusion models without end-to-end training. During inference, LUT-Diff adaptively selects the best inference strategy based on the application/user latency budget. Additionally, LUT-Diff includes a parallel inference engine that rapidly completes model inference through CPU-GPU co-scheduling. Extensive experiments demonstrate that LUT-Diff can generate images comparable to the original model, with an up to 0.012 MSE in generated images. LUT-Diff can also achieve up to 9.1× inference acceleration and reduce the inference memory footprint by up to 70.9% compared to baseline methods. Moreover, LUT-Diff can save at least 3281× the learning cost of lookup tables.'
date: 2025-04-04
venue: 'IEEE Transactions on Mobile Computing (TMC)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10949846'
citation: 'Qipeng Wang, Shiqi Jiang, Yifan Yang, Ruiqi Liu, Yuanchun Li, Ting Cao, Xuanzhe Liu. (2025). "Efficient and Adaptive Diffusion Model Inference Through Lookup Table on Mobile Devices." <i>IEEE Transactions on Mobile Computing (TMC)</i>.'
---
