---
title: "nn-Meter: towards accurate latency prediction of deep-learning model inference on diverse edge devices"
collection: publications
category: conferences
permalink: /publication/2021-06-01-mobisys-nnmeter
excerpt: 'With the recent trend of on-device deep learning, inference latency has become a crucial metric in running Deep Neural Network (DNN) models on various mobile and edge devices. To this end, latency prediction of DNN model inference is highly desirable for many tasks where measuring the latency on real devices is infeasible or too costly, such as searching for efficient DNN models with latency constraints from a huge model-design space. Yet it is very challenging and existing approaches fail to achieve a high accuracy of prediction, due to the varying model-inference latency caused by the runtime optimizations on diverse edge devices. In this paper, we propose and develop nn-Meter, a novel and efficient system to accurately predict the inference latency of DNN models on diverse edge devices. The key idea of nn-Meter is dividing a whole model inference into kernels, i.e., the execution units on a device, and conducting kernel-level prediction. nn-Meter builds atop two key techniques: (i) kernel detection to automatically detect the execution unit of model inference via a set of well-designed test cases; and (ii) adaptive sampling to efficiently sample the most beneficial configurations from a large space to build accurate kernel-level latency predictors. Implemented on three popular platforms of edge hardware (mobile CPU, mobile GPU, and Intel VPU) and evaluated using a large dataset of 26,000 models, nn-Meter significantly outperforms the prior state-of-the-art.'
date: 2021-06-01
venue: '19th International Conference on Mobile Systems, Applications, and Services (MobiSys)'
paperurl: 'https://dl.acm.org/doi/10.1145/3458864.3467882'
citation: 'L. Zhang, S. Han, J. Wei, N. Zheng, T. Cao, Y. Yang, Y. Liu. (2021). "nn-Meter: towards accurate latency prediction of deep-learning model inference on diverse edge devices." <i>19th International Conference on Mobile Systems, Applications, and Services (MobiSys)</i>.'
award: 'Best Paper Award'
---
