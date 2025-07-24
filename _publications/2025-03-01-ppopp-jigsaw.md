---
title: "Jigsaw: Toward Conflict-free Vectorized Stencil Computation by Tessellating Swizzled Registers"
collection: publications
category: conferences
permalink: /publication/2025-03-01-ppopp-jigsaw
excerpt: 'Stencil computation plays a pivotal role in numerous scientific and engineering applications. Previous studies have extensively investigated vectorization techniques to enhance in-core parallelism; however, the performance bottleneck caused by data alignment conflicts (DAC) has not been effectively resolved in all dimensions. This paper proposes Jigsaw, a conflict-free vectorization method to reduce DAC across all dimensions by tessellating swizzled finest-grained lanes. Jigsaw comprises three key components: Lane-based Butterfly Vectorization, SVD-based Dimension Flattening, and Iteration-based Temporal Merging. These components effectively address DAC across spatial and temporal dimensions. Experimental results on different machines demonstrate that Jigsaw could achieve a significant improvement compared to the state-of-the-art techniques, with an average speedup of 2.31x on various stencil kernels.'
date: 2025-03-01
venue: '30th ACM SIGPLAN Annual Symposium on Principles and Practice of Parallel Programming (PPoPP)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3710848.3710886'
citation: 'Yiwei Zhang, Kun Li, Liang Yuan, Yunquan Zhang, Ting Cao, Mao Yang. (2025). "Jigsaw: Toward Conflict-free Vectorized Stencil Computation by Tessellating Swizzled Registers." <i>PPoPP</i>.'
---
