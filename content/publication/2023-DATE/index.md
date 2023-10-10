---
title: "OverlaPIM: Overlap Optimization for Processing In-Memory Neural Network Acceleration"
date: 2023-04-17
publishDate: 2023-04-17
authors: ["Minxuan Zhou@", "**Xuan Wang@**", "Tajana Rosing"]
publication_types: ["1"]
abstract: "Processing in-memory (PIM) can accelerate neural networks (NNs) for its extensive parallelism and data movement minimization. The performance of NN acceleration on PIM heav- ily depends on software-to-hardware mapping, which indicates the order and distribution of operations across the hardware resources. Previous works optimize the mapping problem by exploring the design space of per-layer and cross-layer data layout, achieving speedup over manually designed mappings. However, previous works do not consider computation overlapping across consecutive layers. By overlapping computation, we can process a layer before its preceding layer fully completes, decreasing the execution latency of the whole network. The mapping optimization without overlap analysis can result in sub-optimal performance. In this work, we propose OverlaPIM, a new framework that in- tegrates the overlap analysis with the DNN mapping optimization on PIM architectures. OverlaPIM adopts several techniques to enable efficient overlap analysis and optimization for the whole network mapping on PIM architectures. We test OverlaPIM on popular DNN networks and compare the results to non- overlap optimization. Our experiments show that OverlaPIM can efficiently produce mappings that are 2.10× to 4.11× faster than the state-of-the-art mapping optimization framework."
featured: true
publication: "DATE'2023. (@Co-first authors)"
links:
  - icon_pack: fas
    icon: scroll
    name: Link
    url: 'https://ieeexplore.ieee.org/abstract/document/10137223'
---