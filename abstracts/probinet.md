---
layout: default
---

## ProbINet: A Unified Python Package for Probabilistic Network Analysis

**Speaker:** [Diego Baptista Theuerkauf](https://diegoabt.github.io/)

**Website:** [https://github.com/MPI-IS/probinet](https://github.com/MPI-IS/probinet)

**Abstract:** Recent advances in network analysis have focused on the development of probabilistic generative models aimed at uncovering hidden community structures, capturing reciprocity, and identifying anomalies within networks. These approaches introduce a key innovation by loosening the common assumption of conditional independence in network generative models, explicitly modeling edges between the same pairs of nodes. This relaxation has led to enhanced performance across various tasks, including edge prediction and network reconstruction, while also offering deeper insights into the mechanisms underlying edge formation. Beyond serving as tools for network inference, they also act as benchmark models, capable of generating synthetic data that align with the foundational assumptions of each model. Consequently, these methods are highly effective in tackling real-world challenges in network analysis. Despite their potential, the practical adoption of these  methods is constrained by fragmented implementations. The software tools that come with these models often require different dependencies and feature inconsistent interfaces. This not only reduces their accessibility but also complicates comparisons among them, limiting their impact on both research and real-world applications. To address these issues, we present ProbINet, a comprehensive Python package that integrates implementations from the above works into a unified framework. ProbINet standardizes interfaces, improves usability, and provides clear documentation that links theoretical principles with practical implementations. The framework supports essential network analysis tasks, including node clustering, anomaly detection, link prediction and synthetic data generation from latent variables, providing a robust and versatile tool for practitioners and researchers as well.
