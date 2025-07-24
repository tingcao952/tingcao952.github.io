---
title: "StreamMind: Unlocking Full Frame Rate Streaming Video Dialogue through Event-Gated Cognition"
collection: publications
category: manuscripts
permalink: /publication/2025-10-01-streammind-video-dialogue
excerpt: 'With the rise of real-world human-AI interaction applications, such as AI assistants, the need for Streaming Video Dialogue is critical. To address this need, we introduce StreamMind, a video LLM framework that achieves ultra-FPS streaming video processing (100 fps on a single A100) and enables proactive, always-on responses in real time, without explicit user intervention. To solve the key challenge of the contradiction between linear video streaming speed and quadratic transformer computation cost, we propose a novel perception-cognition interleaving paradigm named ''event-gated LLM invocation'', in contrast to the existing per-time-step LLM invocation. By introducing a Cognition Gate network between the video encoder and the LLM, LLM is only invoked when relevant events occur. To realize the event feature extraction with constant cost, we propose Event-Preserving Feature Extractor (EPFE) based on state-space method, generating a single perception token for spatiotemporal features. These techniques enable the video LLM with full-FPS perception and real-time cognition response. Experiments on Ego4D and SoccerNet streaming tasks, as well as standard offline benchmarks, demonstrate state-of-the-art performance in both model capability and real-time efficiency, paving the way for ultra-high-FPS applications, such as Game AI and interactive media. The code and data is available at this https URL.'
date: 2025-10
venue: "International Conference on Computer Vision (ICCV'25)"
paperurl: ''
citation: 'Xin Ding, Hao Wu, Yifan Yang, Shiqi Jiang, Qianxi Zhang, Donglin Bai, Zhibo Chen, Ting Cao. (2025). "StreamMind: Unlocking Full Frame Rate Streaming Video Dialogue through Event-Gated Cognition." <i>ICCV</i>.'
---