---
title: 'Phylogenomics'
date: 2020-08-02
permalink: /posts/2020/08/phylogenomics/
tags:
  - phylogenomics
  - phylogenetic trees
---

## Evolution at the genome scale

### Coordinator: Leonardo de Oliveira Martins

Phylogenetics, the study of the evolutionary relations between organisms through their genes, is treated as an afterthought in many bioinformatics courses, with input and output taken for granted. However, phylogenetic inference is in fact a branch of statistics ―on graphs or, more frequently, trees― and the evolutionary models available are very dependent on assumptions regarding the input data and the biological conditions.
Phylogenomics arises from the realisation that the evolution of populations cannot be properly represented (much less inferred) by the evolution of any single gene, and thus this module will explore how to integrate the distinct genome biological phenomena into a single model, providing support for the microbial genomics module.

Genomic data, together with other (phenotypic and environmental) information, can help inform, expand, and contextualise evolutionary analyses. This leads to phylogeography and divergence times estimation ―where and when evolutionary events took place―, but also to the comparative method, which are the models describing how phenotypes (antimicrobial resistance, antigenic escape) evolve along the tree.This module will bring all these biological and statistical assumptions to the forefront of the discussion, aiming at a large-scale interpretation of microbial evolution.
It will therefore also explore phylogenetic visualisation: on the different interpretations of trees and associated phenotypic data; on how we represent evolutionary differences between genes across the genome at large scale; and how do we summarise such differences (borrowing knowledge from the statistics module). In practice this module will be composed of:
* Manipulation and interpretation of phylogenetic data: how to programmatically inspect, modify, and reformat sequences, alignments, and trees.
* Simple and complex models: from clustering algorithms to partitioned Bayesian models, and how to incorporate extra information into the trees.
* Adding more data: how to update evolutionary inference with novel data, and how to scale up analyses.
* Supertree, supermatrix, supergenes: how to merge information from distinct genomic regions, including gene and species tree reconciliation.
* Scaling up to the tree of life: Explore additional pipelines (e.g. alignment-free methods), and how to integrate distinct analyses into a common evolutionary framework.

Each component will include a discussion on the theory, software and pipelines, and visualisation. Notice that the complex data visualisation techniques go beyond use cases explored here and can be translated to many other essential fields, from public health reporting to high-throughput economic analysis. This module will also provide theoretical background for other modules, facilitating the training of the next generation of data scientists.
