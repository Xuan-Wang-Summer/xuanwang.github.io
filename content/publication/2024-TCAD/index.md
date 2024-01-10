---
title: "Fast-OverlaPIM: A Fast Overlap-driven Mapping Framework for Processing In-Memory Neural Network Acceleration"
date: 2024
publishDate: 2024
authors: ["Xuan Wang", "Minxuan Zhou", "Tajana Rosing"]
publication_types: ["1"]
abstract: "Processing in-memory (PIM) is promising to accel-
erate neural networks (NNs) because it minimizes data movement
and provides large computational parallelism. Similar to machine
learning accelerators, application mapping, which determines the
operation scheduling and data layout, plays a critical role in the
NN acceleration on PIM. The mapping optimization of previous
NN accelerators focused on optimizing the latency of sequential
execution. However, PIM accelerators feature a distinct design
space of application mapping from conventional NN accelerators,
due to the spatial execution of NN layers across different memory
locations. This enables opportunities for overlapping execution
of consecutive NN layers to improve the latency, where the
succeeding layer can start execution before the preceding layer
fully completes the computation. In this paper, we propose
Fast-OverlaPIM framework that incorporates the computational
overlapping optimization into the DNN mapping exploration pro-
cess on PIM architectures. Fast-OverlaPIM includes analytical
algorithms for fast and accurate overlap analysis. Furthermore,
it proposes a novel mapping search strategy and a transformation
mechanism to enable efficient design space exploration on the
overlap-based mapping for the whole network. Our framework
demonstrates a significant improvement in runtime performance
from 3.4× to 323.1× compared to the previous state-of-the-
art overlap-based framework. Our experiments show that Fast-
OverlaPIM can efficiently produce mappings that are 4.6×
to 18.1× faster than the state-of-the-art mapping optimization
framework under the same architecture constraints."
featured: true
publication: "(in submission)"
links:
  - icon_pack: fas
    icon: scroll
    name: Link
---