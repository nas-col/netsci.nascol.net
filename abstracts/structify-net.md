---
layout: default
---

## Structify-Net

**Speaker:** Rémy Cazabet

**Website:** [https://structify-net.readthedocs.io/](https://structify-net.readthedocs.io/)

**Abstract:** Structify-Net is a Python library to generate random graphs with custom structures, fixed number of nodes and edges. While most network libraries include network generators with block/community structure (e.g., Stochastic Block Models, SBM) and spatial/geometric structure (e.g., Random Geometric Graphs, RGG), generating graphs with other types of structures is typically not straightforward.

With Structify-Net, one can define a structure by defining a **ranking/scoring function**, i.e., a function that, given two nodes characterized by their IDs and/or properties (coordinates in a space, attributes, category, etc.), return a score allowing to rank pair of nodes from most likely to be connected to less likely. By providing only:

* This ranking function
* A set of nodes
* An expected number of edges
* An amount of randomness ε ∈ [0,1]

Structify-net returns a network generator, allowing the exploration of classic (blocks, geometric, nested, hierarchic, ...) and unconventional network structures, in a common framework.

Typical applications of this library include (1) the study of network properties (clustering coefficient, average shortest path, ...), (2) the impact of network structure on diffusion processes, and (3) benchmarks for tasks such as community detection or link prediction.

**Reference:**

 - Cazabet, R., Citraro, S., & Rossetti, G. (2023). [Structify-Net: Random Graph generation with controlled size and customized structure](https://doi.org/10.24072/pcjournal.335)s. Peer Community Journal, 3. 
