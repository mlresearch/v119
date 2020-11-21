---
title: Efficient nonparametric statistical inference on population feature importance
  using Shapley values
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/williamson20a/williamson20a.pdf
url: http://proceedings.mlr.press/v119/williamson20a.html
abstract: The true population-level importance of a variable in a prediction task
  provides useful knowledge about the underlying data-generating mechanism and can
  help in deciding which measurements to collect in subsequent experiments. Valid
  statistical inference on this importance is a key component in understanding the
  population of interest. We present a computationally efficient procedure for estimating
  and obtaining valid statistical inference on the \textbf{S}hapley \textbf{P}opulation
  \textbf{V}ariable \textbf{I}mportance \textbf{M}easure (SPVIM). Although the computational
  complexity of the true SPVIM scales exponentially with the number of variables,
  we propose an estimator based on randomly sampling only $\Theta(n)$ feature subsets
  given $n$ observations. We prove that our estimator converges at an asymptotically
  optimal rate. Moreover, by deriving the asymptotic distribution of our estimator,
  we construct valid confidence intervals and hypothesis tests. Our procedure has
  good finite-sample performance in simulations, and for an in-hospital mortality
  prediction task produces similar variable importance estimates when different machine
  learning algorithms are applied.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: williamson20a
month: 0
tex_title: Efficient nonparametric statistical inference on population feature importance
  using Shapley values
firstpage: 10282
lastpage: 10291
page: 10282-10291
order: 10282
cycles: false
bibtex_author: Williamson, Brian and Feng, Jean
author:
- given: Brian
  family: Williamson
- given: Jean
  family: Feng
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
software: https://github.com/bdwilliamson/spvim_supplementary
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/williamson20a/williamson20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
