---
layout: default
---

# School / Workshop

Tutorial on cross-package network analysis in Python using [igraph](https://python.igraph.org), [NetworkX](https://networkx.org) and [graph-tool](https://graph-tool.skewed.de/).

## Time and place

Location: **room 2104AB**

Time: **14:30 to 18:00** with a coffee break between 16:00–16:30.

## Instructors:

 - [Tamás Nepusz](http://github.com/ntamas/)
 - [Tiago Peixoto](https://skewed.de/tiago/)
 - [Matt Schwennesen](http://www.schwennesen.org/)

## Content

The workshop will be roughly broken up into three parts, one for each library.

### NetworkX

Time: 14:30 – 15:30

NetworkX is a pure-python library for network analysis which aims to be both
easy to install and easy to use while also being feature rich. Currently the
library features around 400 network analysis algorithms ranging from classics
like shortest path and spanning trees to approximate algorithms for problems
like graph isomorphism and the traveling salesperson problem. With the recent
addition of a backend system, NetworkX is now capable of utilizing faster
implementations of supported algorithms from other graph analysis libraries like
[Python GraphBLAS Algorithms](https://github.com/python-graphblas/graphblas-algorithms) and
[CuGraph](https://github.com/rapidsai/cugraph/tree/branch-24.04/python/nx-cugraph).
In this workshop, we'll cover how to get started with NetworkX as well as topics
like graph visualization, some classical algorithms, graph input/output, a
network analysis case study and finally the new dispatching system.

### graph-tool

Time: 15:30 to 17:00, with coffee break between 16:00 – 16:30

<style>
blockquote {
 color: inherit !important;
}
</style>

> In this <u>interactive</u> workshop we will briefly cover the basic and some
> of the more advanced functionalities of the `graph-tool` library. After an
> introduction, participants will be given some hands-on exercises, which will
> be discussed during the session.
>
> To participate in the interactive session, please create an account at:
>
>    [https://hub.skewed.de](https://hub.skewed.de)
>
> and open the notebook from [here](https://hub.skewed.de/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fcount0%2Fgt-nascol&urlpath=lab%2Ftree%2Fgt-nascol%2Fgt-workshop.ipynb&branch=master).

[Graph-tool](https://graph-tool.skewed.de) is an efficient
[Python](https://www.python.org) module for manipulation and statistical
analysis of [graphs](https://en.wikipedia.org/wiki/Graph_%28mathematics%29) and
[networks](https://en.wikipedia.org/wiki/Network_theory).

The core data structures and algorithms are implemented in
[C++](https://en.wikipedia.org/wiki/C%2B%2B), making extensive use of [template
metaprogramming](https://en.wikipedia.org/wiki/Template_metaprogramming), based
heavily on the [Boost Graph
Library](https://www.boost.org/doc/libs/release/libs/graph). This confers it a
level of [performance](https://graph_tool.skewed.de/performance.html) that is
comparable (both in memory usage and computation time) to that of a pure C/C++
library.

`graph-tool` can be orders of magnitude faster than pure Python alternatives,
and therefore it is specially suited for large-scale network analysis.

Some of the unique functionalities of `graph-tool` include:

1.  Comprehensive framework for [inferential community
    detection](https://graph-tool.skewed.de/static/doc/demos/inference/inference.html#inference-howto),
    build upon statistically principled approaches that avoid overfitting and
    are interpretable.

1.  Support for [network reconstruction from
    dynamics](https://graph-tool.skewed.de/static/doc/demos/reconstruction_indirect/reconstruction.html).

1.  Support for [uncertainty
    quantification](https://graph-tool.skewed.de/static/doc/demos/reconstruction_direct/reconstruction.html)
    in network data.

1.  Support for [OpenMP](https://en.wikipedia.org/wiki/OpenMP) shared memory
    [parallelism](https://graph-tool.skewed.de/static/doc/parallel.html) for several algorithms.
    
1.  High-quality [network visualization](https://graph-tool.skewed.de/static/doc/draw.html#draw), both
    static and interactive, supporting
    [animations](https://graph-tool.skewed.de/static/doc/demos/animation/animation.html#animation) and
    [matplotlib
    integration](https://graph-tool.skewed.de/static/doc/demos/matplotlib/matplotlib.html#matplotlib-sec).
    
1.  [Filtered graphs](https://graph-tool.skewed.de/static/doc/quickstart.html#sec-graph-filtering), i.e.
    graphs where nodes and edges are temporarily masked. These are first class
    citizens in the library, and are accepted by every function. Due to the use of
    C++ template metaprogramming, this functionality comes at no performance
    cost when filtering is not being used.
    
1.  Efficient and fully documented [binary
    format](https://graph-tool.skewed.de/static/doc/gt_format.html#sec-gt-format) for network files.
    
1.  Integration with the [Netzschleuder](https://networks.skewed.de) network
    data repository, enabling [easy loading](https://graph-tool.skewed.de/static/doc/collection.html#graph_tool.collection.ns) of network data.
    
1.  Support for writing custom [C++
extensions](https://graph-tool.skewed.de/static/doc/demos/cppextensions/cppextensions.html#cppextensions).

### igraph

Time: 17:00 – 18:00

[igraph](https://igraph.org) is a high-performance general-purpose library for
complex network analysis, designed to be used from high-level languages like R,
Python and Mathematica. The core library and data structures are implemented in
C and C++, making it suitable for the analysis of large networks consisting of
millions of vertices and even billions of edges given enough RAM.

In this workshop, we will cover the basics of getting started with igraph,
including the essential graph generation and graph analysis methods and the
attribute handling system. We will cover the creation of publication-quality
plots using [Cairo](https://www.cairographics.org/) or
[Matplotlib](https://matplotlib.org/) as backends, graph input/output,
in-memory conversion to other popular tools such as
[NetworkX](https://networkx.org) and
[graph-tool](https://graph-tool.skewed.de), and a few popular algoritms used in
network science like community detection algorithms and motif search.

