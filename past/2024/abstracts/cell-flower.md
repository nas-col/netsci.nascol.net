---
layout: default
---

## Cell FLOWer

**Speaker:** Josef Hoppe

**Website:** [https://github.com/josefhoppe/cell-flower](https://github.com/josefhoppe/cell-flower)

**Abstract:** Obtaining sparse, interpretable representations of observable data is crucial in many machine learning and signal processing tasks. For data representing flows along the edges of a graph, an intuitively interpretable way to obtain such representations is to lift the graph structure to a cell complex: As a generalization of simplicial complexes, the eigenvectors of the associated Hodge-Laplacian also induce a Hodge decomposition, which can be used to represent the observed data in terms of gradient, curl, and harmonic flows. From this basis, we can topologically filter (i.e., denoise) these flows. Moreover, the cells of a cell complex that results in a representation which is both accurate and sparse capture an inherent structure of the observed flows which may lead to further insights.

CellFlower implements the efficient approximate algorithm for this flow representation problem presented in Hoppe and Schaub (2024). It is a lightweight and easy-to-use python package, designed to work as a standalone library. For convenience, it also includes utility methods for easy interoperability with NetworkX.

**Reference:**

 - Hoppe, J., & Schaub, M. (2024). [Representing Edge Flows on Graphs via Sparse Cell Complexes](https://proceedings.mlr.press/v231/hoppe24a.html). In Proceedings of the Second Learning on Graphs Conference (pp. 1:1–1:22).
