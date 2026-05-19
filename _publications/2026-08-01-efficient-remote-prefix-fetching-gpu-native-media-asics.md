---
title: "Efficient Remote Prefix Fetching with GPU-native Media ASICs"
collection: publications
category: conferences
permalink: /publication/2026-08-01-efficient-remote-prefix-fetching-gpu-native-media-asics
excerpt: 'Remote KV cache reuse fetches KV cache for identical contexts from remote storage, avoiding recomputation and accelerating LLM inference. While it excels in high-speed networks, its performance degrades significantly in bandwidth-limited scenarios. Recent studies address this by transmitting KV caches in compressed form, but the associated heavyweight decompression counteracts the KV reuse benefits. In this paper, we propose an efficient and widely deployable remote KV cache reuse solution that leverages GPU-native video codecs. Our system, KVFetcher, enables effective KV cache coding with two techniques. The codec-friendly tensor layout compresses the KV cache in a highly compact video format, enabling fast transmission. The efficient KV fetcher orchestrates the transmission, decoding, and restoration of compressed KV caches in an efficient pipelined manner, eliminating resource contention, masking network fluctuations, and achieving minimum time-to-first-token (TTFT). We prototype KVFetcher on diverse GPUs from high- to low-end. Experiments reveal that it reduces TTFT by up to 3.51 times while maintaining lossless accuracy, compared to SOTA methods.'
date: 2026-08-01
venue: 'ACM SIGCOMM Conference'
paperurl: 'https://arxiv.org/abs/2602.09725'
citation: 'Liang Mi, Weijun Wang, Jinghan Chen, Ting Cao, Haipeng Dai, Yunxin Liu. (2026). "Efficient Remote Prefix Fetching with GPU-native Media ASICs." <i>SIGCOMM</i>.'
---