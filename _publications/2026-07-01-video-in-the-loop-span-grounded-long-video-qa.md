---
title: "Video-in-the-Loop: Span-Grounded Long Video QA with Interleaved Reasoning"
collection: publications
category: conferences
permalink: /publication/2026-05-01-video-in-the-loop-span-grounded-long-video-qa
excerpt: 'We present Video-in-the-Loop (ViTL), a two-stage long-video QA framework that preserves a fixed token budget by first localizing question-relevant interval(s) with a low-fps skim and then answering via span-aware reallocation of visual tokens at higher effective frame rate, emitting an interleaved output with both spans and the final option for direct attribution. We also introduce VGrounding-QA, which converts description-based event graphs into span-grounded multiple-choice QA by pairing each question with ground-truth time span(s) and related reasoning. ViTL is trained end-to-end with an interleaved group-relative objective that couples temporal IoU for localization with answer correctness, allowing credit to flow from answers back to spans without increasing compute. Under fixed token budgets, ViTL attains up to 8.6% gain with 50% less frame input on long-video QA and temporal grounding (e.g., Charades-STA, ActivityNet-Captions), and ablations show that span-aware token reallocation consistently surpasses uniform sampling. Together, VGrounding-QA and ViTL provide an interpretable, compute-efficient recipe for scalable long-video QA.'
date: 2026-07-01
venue: 'International Conference on Machine Learning (ICML)'
paperurl: 'https://arxiv.org/abs/2510.04022'
citation: 'Chendong Wang, Donglin Bai, Yifan Yang, Xiao Jin, Anlan Zhang, Rui Wang, Shiqi Jiang, Yuqing Yang, Hao Wu, Qi Dai, Chong Luo, Ting Cao, Lili Qiu, Suman Banerjee. (2026). "Video-in-the-Loop: Span-Grounded Long Video QA with Interleaved Reasoning." <i>ICML</i>.'
---