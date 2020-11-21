---
title: 'Efficient Robustness Certificates for Discrete Data: Sparsity-Aware Randomized
  Smoothing for Graphs, Images and More'
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/bojchevski20a/bojchevski20a.pdf
url: http://proceedings.mlr.press/v119/bojchevski20a.html
abstract: Existing techniques for certifying the robustness of models for discrete
  data either work only for a small class of models or are general at the expense
  of efficiency or tightness. Moreover, they do not account for sparsity in the input
  which, as our findings show, is often essential for obtaining non-trivial guarantees.
  We propose a model-agnostic certificate based on the randomized smoothing framework
  which subsumes earlier work and is tight, efficient, and sparsity-aware. Its computational
  complexity does not depend on the number of discrete categories or the dimension
  of the input (e.g. the graph size), making it highly scalable. We show the effectiveness
  of our approach on a wide variety of models, datasets, and tasks – specifically
  highlighting its use for Graph Neural Networks. So far, obtaining provable guarantees
  for GNNs has been difficult due to the discrete and non-i.i.d. nature of graph data.
  Our method can certify any GNN and handles perturbations to both the graph structure
  and the node attributes.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bojchevski20a
month: 0
tex_title: 'Efficient Robustness Certificates for Discrete Data: Sparsity-Aware Randomized
  Smoothing for Graphs, Images and More'
firstpage: 1003
lastpage: 1013
page: 1003-1013
order: 1003
cycles: false
bibtex_author: Bojchevski, Aleksandar and Klicpera, Johannes and G{\"u}nnemann, Stephan
author:
- given: Aleksandar
  family: Bojchevski
- given: Johannes
  family: Klicpera
- given: Stephan
  family: Günnemann
date: 2020-09-29
address: 
container-title: Proceedings of the 37th International Conference on Machine Learning
volume: '119'
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 9
  - 29
software: https://www.daml.in.tum.de/sparse_smoothing
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/bojchevski20a/bojchevski20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
