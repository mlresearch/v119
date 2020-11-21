---
title: 'Beyond Signal Propagation: Is Feature Diversity Necessary in Deep Neural Network
  Initialization?'
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/blumenfeld20a/blumenfeld20a.pdf
url: http://proceedings.mlr.press/v119/blumenfeld20a.html
abstract: Deep neural networks are typically initialized with random weights, with
  variances chosen to facilitate signal propagation and stable gradients. It is also
  believed that diversity of features is an important property of these initializations.
  We construct a deep convolutional network with identical features by initializing
  almost all the weights to $0$. The architecture also enables perfect signal propagation
  and stable gradients, and achieves high accuracy on standard benchmarks. This indicates
  that random, diverse initializations are \emph{not} necessary for training neural
  networks. An essential element in training this network is a mechanism of symmetry
  breaking; we study this phenomenon and find that standard GPU operations, which
  are non-deterministic, can serve as a sufficient source of symmetry breaking to
  enable training.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: blumenfeld20a
month: 0
tex_title: 'Beyond Signal Propagation: Is Feature Diversity Necessary in Deep Neural
  Network Initialization?'
firstpage: 960
lastpage: 969
page: 960-969
order: 960
cycles: false
bibtex_author: Blumenfeld, Yaniv and Gilboa, Dar and Soudry, Daniel
author:
- given: Yaniv
  family: Blumenfeld
- given: Dar
  family: Gilboa
- given: Daniel
  family: Soudry
date: 2020-11-21
address: 
container-title: Proceedings of the 37th International Conference on Machine Learning
volume: '119'
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 11
  - 21
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/blumenfeld20a/blumenfeld20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
