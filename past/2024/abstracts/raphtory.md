---
layout: default
---

## Raphtory: fast temporal network analysis in Python, powered by Rust

**Speaker:** Naomi Arnold

**Website:** [https://www.raphtory.com/](https://www.raphtory.com/)

**Abstract:** Temporal networks provide an essential framework for representing evolving or event-based systems ranging from financial transactions, social interactions to contact networks and the last decade has brought a variety of useful metrics and algorithms for understanding them. While there are now many actively-developed and feature-complete tools for working with static networks such as NetworkX, igraph and graph-tool, and for higher-order networks like PathPy, XGI and HypergraphX, no such equivalent has existed for temporal networks. In this presentation we introduce Raphtory, our multi-purpose library for analysis of large-scale temporal networks. Built by network scientists, Raphtory has been designed to represent as varied as possible notion of temporal network, from link-streams to edges with duration to sequences of network snapshots, and is equipped with an expressive API for querying the network over different times and timescales. As well as temporal attributes, nodes and edges can have properties/weights and edges can be part of a layer, allowing multi-layer, weighted and attributed networks to be represented easily. With large-scale networks in mind, the core of Raphtory is written in Rust which allows for fast and memory-efficient computation, whilst being wrapped in a fully-documented Python library so that no Rust knowledge is required of the user. Raphtory is equipped with a range of in-built algorithms, from static graph metrics that would be expected in a graph library to temporally focused ones such as δ-temporal motifs, topological-temporal reachability and temporal spreading simulations.

**Reference:**

 - Steer, B, et al. [Raphtory: The temporal graph engine for Rust and Python](https://arxiv.org/abs/2306.16309). _arXiv preprint_.