---
title: Landscape Connectivity and Dropout Stability of SGD Solutions for Over-parameterized
  Neural Networks
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/shevchenko20a/shevchenko20a.pdf
url: http://proceedings.mlr.press/v119/shevchenko20a.html
abstract: 'The optimization of multilayer neural networks typically leads to a solution
  with zero training error, yet the landscape can exhibit spurious local minima and
  the minima can be disconnected. In this paper, we shed light on this phenomenon:
  we show that the combination of stochastic gradient descent (SGD) and over-parameterization
  makes the landscape of multilayer neural networks approximately connected and thus
  more favorable to optimization. More specifically, we prove that SGD solutions are
  connected via a piecewise linear path, and the increase in loss along this path
  vanishes as the number of neurons grows large. This result is a consequence of the
  fact that the parameters found by SGD are increasingly dropout stable as the network
  becomes wider. We show that, if we remove part of the neurons (and suitably rescale
  the remaining ones), the change in loss is independent of the total number of neurons,
  and it depends only on how many neurons are left. Our results exhibit a mild dependence
  on the input dimension: they are dimension-free for two-layer networks and require
  the number of neurons to scale linearly with the dimension for multilayer networks.
  We validate our theoretical findings with numerical experiments for different architectures
  and classification tasks.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shevchenko20a
month: 0
tex_title: Landscape Connectivity and Dropout Stability of {SGD} Solutions for Over-parameterized
  Neural Networks
firstpage: 8773
lastpage: 8784
page: 8773-8784
order: 8773
cycles: false
bibtex_author: Shevchenko, Alexander and Mondelli, Marco
author:
- given: Alexander
  family: Shevchenko
- given: Marco
  family: Mondelli
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
  link: http://proceedings.mlr.press/v119/shevchenko20a/shevchenko20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
