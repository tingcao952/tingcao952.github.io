---
title: "V-Droid: Advancing Mobile GUI Agent Through Generative Verifiers"
collection: publications
category: preprints
permalink: /publication/2026-10-26-mobile-gui-agents
excerpt: 'We propose V-Droid, a mobile GUI task automation agent. Unlike previous mobile agents that utilize Large Language Models (LLMs) as generators to directly generate actions at each step, V-Droid employs LLMs as verifiers to evaluate candidate actions before making final decisions. To realize this novel paradigm, we introduce a comprehensive framework for constructing verifier-driven mobile agents: the discretized action space construction coupled with the prefilling-only workflow to accelerate the verification process, the pair-wise progress preference training to significantly enhance the verifier  decision-making capabilities, and the scalable human-agent joint annotation scheme to efficiently collect the necessary data at scale. V-Droid obtains a substantial task success rate across several public mobile task automation benchmarks: 59.5% on AndroidWorld, 38.3% on AndroidLab, and 49% on MobileAgentBench, surpassing existing agents by 5.2%, 2.1%, and 9%, respectively. Furthermore, V-Droid achieves a remarkably low latency of 4.3s per step, which is 6.1x faster compared with existing mobile agents.'
date: 2026-10-26
venue: 'The 32nd Annual International Conference On Mobile Computing And Networking (MobiCom)'
paperurl: 'https://arxiv.org/abs/2503.15937'
citation: 'Gaole Dai, Shiqi Jiang, Ting Cao, Yuanchun Li, Yuqing Yang, Rui Tan, Mo Li, Lili Qiu. (2025). "V-Droid: Advancing Mobile GUI Agent Through Generative Verifiers." <i>MobiCom</i>.'
---
---
title: "Anatomizing Deep Learning Inference in Web Browsers"
collection: publications
category: conferences
permalink: /publication/2025-01-21-tosem-browser-inference
excerpt: 'Web applications have increasingly adopted Deep Learning (DL) through in-browser inference, wherein DL inference performs directly within Web browsers. The actual performance of in-browser inference and its impacts on the Quality of Experience (QoE) remain unexplored, and urgently require new QoE measurements beyond traditional ones, e.g., mainly focusing on page load time. To bridge this gap, we make the first comprehensive performance measurement of in-browser inference to date. Our approach proposes new metrics to measure in-browser inference: responsiveness, smoothness, and inference accuracy. Our extensive analysis involves 9 representative DL models across Web browsers of 50 popular PC devices and 20 mobile devices. The results reveal that in-browser inference exhibits a substantial latency gap, averaging 16.9 times slower on CPU and 4.9 times slower on GPU compared to native inference on PC devices. The gap on mobile CPU and mobile GPU is 15.8 times and 7.8 times, respectively. Furthermore, we identify contributing factors to such latency gap, including underutilized hardware instruction sets, inherent overhead in the runtime environment, resource contention within the browser, and inefficiencies in software libraries and GPU abstractions. Additionally, in-browser inference imposes significant memory demands, at times exceeding 334.6 times the size of the DL models themselves, partly attributable to suboptimal memory management. We also observe that in-browser inference leads to a significant 67.2% increase in the time it takes for GUI components to render within Web browsers, significantly affecting the overall user QoE of Web applications reliant on this technology.'
date: 2025-01-21
venue: 'ACM Transactions on Software Engineering and Methodology (TOSEM)'
paperurl: 'https://dl.acm.org/doi/full/10.1145/3688843'
citation: 'Qipeng Wang, Shiqi Jiang, Zhenpeng Chen, Xu Cao, Yuanchun Li, Aoyu Li, Yun Ma, Ting Cao, Xuanzhe Liu. (2025). "Anatomizing Deep Learning Inference in Web Browsers." <i>TOSEM</i>.'
---