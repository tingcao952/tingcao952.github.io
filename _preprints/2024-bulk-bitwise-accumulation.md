---
title: "Bulk Bitwise Accumulation in Commercial DRAM"
collection: preprints
permalink: /preprints/2024-bulk-bitwise-accumulation
excerpt: 'Processing-in-memory (PIM) is a promising paradigm for addressing data transfer bottlenecks in data-intensive workloads, particularly in machine learning. Among PIM techniques, Processing-using-Commercial-DRAM (PuCD) offers a practical approach for enabling in-memory computing by employing widely available DRAM modules without hardware modifications. With its massive bit-level parallelisms, PuCD has a high-performance capability of bulk bit logic operation. However, implementing 
 operations, crucial for machine learning tasks, remains challenging in PuCD. The need for multiple consecutive operations in accumulation leads to increased latency and error propagation. To address these challenges, we propose a novel method for bulk bitwise accumulation using PuCD. As a fundamental building block for our accumulation method, we introduce a novel implementation of the population count of 3 (POPCNT3) operation tailored for commercial DRAM. On top of this, we present a POPCNT3-based bitwise accumulation method that efficiently handles large input sizes, enabling scalable bitwise accumulation for various input sizes. We evaluate the throughput and errors of our approach using commercial DDR4 DRAM modules with an FPGA. The experiments indicate that the throughput improvement is up to 348 times over A100 GPU across various input sizes with negligible errors to maintain the accuracy of machine learning applications. These results demonstrate that PuCD can provide a practical pathway for accelerating machine learning tasks without requiring specialized memory chips.'
date: 2024-12-01
venue: 'NeurIPS 2024 Workshop Machine Learning with new Compute Paradigms'
paperurl: 'https://openreview.net/forum?id=5b4sUxqIqp'
citation: 'Tatsuya Kubo, Masayuki Usui, Tomoya Nagatani, Daichi Tokuda, Lei Qu, Ting Cao, Shinya Takamaeda-Yamazaki. (2024). "Bulk Bitwise Accumulation in Commercial DRAM." <i>NeurIPS 2024 Workshop Machine Learning with new Compute Paradigms</i>.'
---
