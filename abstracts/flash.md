---
layout: default
---

## graph-tool

## Hypergraphx

**Speaker:** [Quintino Francesco Lotito](https://github.com/FraLotito)

**Website:** [https://github.com/HGX-Team/hypergraphx](https://github.com/HGX-Team/hypergraphx)

**Abstract:** In the last few decades, networks have emerged as the natural tool to model a wide variety of natural, social and man-made systems. Networks, collections of nodes and links, capture dyadic interactions only. However, in many real-world systems units interact in groups of three or more. Examples include cellular networks, brain networks, and collaboration networks. These higher-order interactions can be naturally described by hypergraphs, where hyperedges connect groups of nodes of arbitrary size. In parallel with theoretical and methodological progress, a crucial role in advancing network science has been played by developing efficient algorithms and computational tools to analyze networked data. Nowadays, widely used, community-based software such as NetworkX and igraph, and individual efforts such as graph-tool -- just to mention a few -- have enabled thousands of researchers to perform multi-faceted, large-scale network analysis of relational data.

Only recently, some early contributions have started to develop computational tools to match the explosion of interest in higher-order systems. Here, we provide our contribution by presenting hypergraphx (HGX), a multi-purpose, open-source python library for the analysis of networked systems with higher-order interactions. HGX aims to provide, as a single source, a comprehensive suite of tools and algorithms for constructing, storing, analysing and visualizing systems with higher-order interactions. The library includes different ways to convert data across distinct higher-order representations, a large variety of measures of higher-order organization at the local and the mesoscale, statistical filters to sparsify higher-order data, a wide array of static and dynamic generative models, an implementation of different dynamical processes, from epidemics to diffusion and synchronization, with higher-order interactions, and more. Our computational framework allows the analysis of hypergraphs with weighted, directed, signed, temporal and multiplex group interactions.  Moreover, we accompany our library with an easily accessible and well-curated data repository, functioning as a unifying source of datasets for the analysis of higher-order systems. The recent explosion of higher-order relational data has led to novel methodologies to study higher-order systems, which in turn require extensive datasets to be tested and validated.  A few of these data are inherently higher-order. Several others, instead, have originally been investigated with pairwise approaches, but have recently been re-explored under the new lens of higher-order network analysis. Beyond experts in the field, we hope that our library will make higher-order network analysis accessible to everyone interested in exploring the higher-order dimension of relational data, and invite the community to explore the library, and the related tutorials and contribute.

**Reference:**

* Lotito, Q. F., et al. (2023). Hypergraphx: a library for higher-order network analysis. Journal of Complex Networks, 11(3). https://doi.org/10.1093/comnet/cnad019


## igraph

## Raphtory: fast temporal network analysis in Python, powered by Rust

**Speaker:** [Chieck Ba](https://back7.github.io)

**Website:** [https://www.raphtory.com/](https://www.raphtory.com/)

**Abstract:** Temporal networks provide an essential framework for representing evolving or event-based systems ranging from financial transactions, social interactions to contact networks and the last decade has brought a variety of useful metrics and algorithms for understanding them. While there are now many actively-developed and feature-complete tools for working with static networks such as NetworkX, igraph and graph-tool, and for higher-order networks like PathPy, XGI and HypergraphX, no such equivalent has existed for temporal networks. In this presentation we introduce Raphtory, our multi-purpose library for analysis of large-scale temporal networks. Built by network scientists, Raphtory has been designed to represent as varied as possible notion of temporal network, from link-streams to edges with duration to sequences of network snapshots, and is equipped with an expressive API for querying the network over different times and timescales. As well as temporal attributes, nodes and edges can have properties/weights and edges can be part of a layer, allowing multi-layer, weighted and attributed networks to be represented easily. With large-scale networks in mind, the core of Raphtory is written in Rust which allows for fast and memory-efficient computation, whilst being wrapped in a fully-documented Python library so that no Rust knowledge is required of the user. Raphtory is equipped with a range of in-built algorithms, from static graph metrics that would be expected in a graph library to temporally focused ones such as δ-temporal motifs, topological-temporal reachability and temporal spreading simulations.

**Reference:**

* Steer et al., (2024). [Raphtory: The temporal graph engine for Rust and Python](https://doi.org/10.21105/joss.05940). Journal of Open Source Software, 9(95), 5940.


## CompleX Group Interactions (XGI)

**Speaker:** [Nicholas Landry](https://landry-lab.github.io)

**Website:** [https://xgi.readthedocs.io](https://xgi.readthedocs.io)

**Abstract:** CompleX Group Interactions (XGI) is a library for higher-order networks, which model interactions of arbitrary size between entities in a complex system. This library provides methods for building hypergraphs (undirected and directed) and simplicial complexes; algorithms to analyze their structure, visualize them, and simulate dynamical processes on them; and XGI-DATA, a collection of higher-order datasets. XGI is implemented in pure Python and integrates with the rest of the Python scientific stack. XGI is designed and developed by network scientists with the needs of network scientists in mind. We demonstrate this library's effectiveness by describing an example XGI workflow: first, choosing a higher-order dataset; second, extracting basic global statistics; third, calculating structural measures such as connectedness, assortativity, and centrality; third, converting higher-order datasets to different mathematical representations; fourth, leveraging the statistics module to filter the dataset; and lastly, visualizing the higher-order networks in various ways.

**Reference:**

* Landry et al., (2023). [XGI: A Python package for higher-order interaction networks](https://doi.org/10.21105/joss.05162). Journal of Open Source Software, 8(85), 5162.