---
title: "nn-Meter: towards accurate latency prediction of DNN inference on diverse edge devices"
collection: publications
category: journals
permalink: /publication/2021-12-01-getmobile-nnmeter
excerpt: 'Inference latency has become a crucial metric in running Deep Neural Network (DNN) models on various mobile and edge devices. To this end, latency prediction of DNN inference is highly desirable for many tasks where measuring the latency on real devices is infeasible or too costly. Yet it is very challenging and existing approaches fail to achieve a high accuracy of prediction, due to the varying model-inference latency caused by the runtime optimizations on diverse edge devices. In this paper, we propose and develop nn-Meter, a novel and efficient system to accurately predict the DNN inference latency on diverse edge devices. The key idea of nn-Meter is dividing a whole model inference into kernels, i.e., the execution units on a device, and conducting kernel-level prediction. nn-Meter builds atop two key techniques: (i) kernel detection to automatically detect the execution unit of model inference via a set of well-designed test cases; and (ii) adaptive sampling to efficiently sample the most beneficial configurations from a large space to build accurate kernel-level latency predictors. nn-Meter achieves significant high prediction accuracy on four types of edge devices.'
date: 2021-12-01
venue: 'GetMobile: Mobile Computing and Communications, Research Highlights'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3529706.3529712'
citation: 'L. Zhang, S. Han, J. Wei, N. Zheng, T. Cao, Y. Yang, Y. Liu. (2021). "nn-Meter: towards accurate latency prediction of DNN inference on diverse edge devices." <i>GetMobile: Mobile Computing and Communications, Research Highlights</i>, 25(4): pp. 19-23.'
---
**ACM SigMobile Research Highlight**