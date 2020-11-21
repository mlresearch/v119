---
title: Circuit-Based Intrinsic Methods to Detect Overfitting
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/chatterjee20a/chatterjee20a.pdf
url: http://proceedings.mlr.press/v119/chatterjee20a.html
abstract: The focus of this paper is on intrinsic methods to detect overfitting. By
  intrinsic methods, we mean methods that rely only on the model and the training
  data, as opposed to traditional methods (we call them extrinsic methods) that rely
  on performance on a test set or on bounds from model complexity. We propose a family
  of intrinsic methods called Counterfactual Simulation (CFS) which analyze the flow
  of training examples through the model by identifying and perturbing rare patterns.
  By applying CFS to logic circuits we get a method that has no hyper-parameters and
  works uniformly across different types of models such as neural networks, random
  forests and lookup tables. Experimentally, CFS can separate models with different
  levels of overfit using only their logic circuit representations without any access
  to the high level structure. By comparing lookup tables, neural networks, and random
  forests using CFS, we get insight into why neural networks generalize. In particular,
  we find that stochastic gradient descent in neural nets does not lead to "brute
  force" memorization, but finds common patterns (whether we train with actual or
  randomized labels), and neural networks are not unlike forests in this regard. Finally,
  we identify a limitation with our proposal that makes it unsuitable in an adversarial
  setting, but points the way to future work on robust intrinsic methods.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chatterjee20a
month: 0
tex_title: Circuit-Based Intrinsic Methods to Detect Overfitting
firstpage: 1459
lastpage: 1468
page: 1459-1468
order: 1459
cycles: false
bibtex_author: Chatterjee, Satrajit and Mishchenko, Alan
author:
- given: Satrajit
  family: Chatterjee
- given: Alan
  family: Mishchenko
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
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
