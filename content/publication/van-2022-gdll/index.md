---
abstract: Deep learning has recently been shown to be effective in uncovering hidden patterns in non-Euclidean space, where data is represented as graphs with complex object relationships and interdependencies. Because of the implicit data dependence in the big graphs with millions of nodes and billions of edges, it is hard for industrial communities to exploit these methods to address real-world challenges at scale. The skewness property of big graphs, distributed file system performance penalty on small k-hop neighborhood subgraphs, and varying size of subgraph makes Graph Neural Networks (GNNs) training further challenging in a distributed environment using parameter servers. To address such issues, we propose a scalable, layered, fault-tolerance, and in-memory distributed computing-based graph neural network framework called Graph Distributed Learning Library (GDLL). The base layer utilizes an optimized distributed file system and a scalable graph data store to reduce the performance penalty. The second layer provides distributed graph processing using in-memory graph programming models while optimizing and hiding the underlying complexity of information complete subgraph computation. In the third layer, GNN modules are deployed on top of the first two layers for efficient distributed training using parameter servers. Finally, we evaluate and compare GDLL with the state-of-the-art solutions and outperform it significantly in terms of efficiency while maintaining similar GNN convergence.
author_notes:
- 
- 
-
- "ORCID: 0000-0003-1659-6040"
authors:
- Doung Thi  Thu Van
- Muhammad Numan Khan
- Tariq Habib Afridi
- admin
- Aftab Alam
- Young-Koo Lee
date: "2022-01-31T00:00:00Z"
doi: ""
featured: false
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false
projects: []
publication: '*IEEE Access, IEEE*'
publication_short: "IEEE Access, IEEE"
publication_types:
- "2"
publishDate: "2022-01-31T00:00:00Z"
#slides: example
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus
#  ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
tags:
- Graph neural networks
- GNN
- Gig graph learning
- Distributed GNN 
- Large scale graph
- Graph learning
title: "GDLL: A Scalable and Share Nothing Architecture Based Distributed Graph Neural Networks Framework"
#url_code: https://github.com/wowchemy/wowchemy-hugo-themes
#url_dataset: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9698236
#url_poster: ""
#url_project: ""
#url_slides: ""
#url_source: ""
#url_video: ""
---
{{% callout note %}}
Click the *Cite* button above to download the Bibtex citation of the paper.
{{% /callout %}}

{{% callout note %}}
Click the *PDF* button above to download the paper.
{{% /callout %}}