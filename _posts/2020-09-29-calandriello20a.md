---
title: Near-linear time Gaussian process optimization with adaptive batching and resparsification
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/calandriello20a/calandriello20a.pdf
url: http://proceedings.mlr.press/v119/calandriello20a.html
abstract: Gaussian processes (GP) are one of the most successful frameworks to model
  uncertainty. However, GP optimization (e.g., GP-UCB) suffers from major scalability
  issues. Experimental time grows linearly with the number of evaluations, unless
  candidates are selected in batches (e.g., using GP-BUCB) and evaluated in parallel.
  Furthermore, computational cost is often prohibitive since algorithms such as GP-BUCB
  require a time at least quadratic in the number of dimensions and iterations to
  select each batch. In this paper, we introduce BBKB (Batch Budgeted Kernel Bandits),
  the first no-regret GP optimization algorithm that provably runs in near-linear
  time and selects candidates in batches. This is obtained with a new guarantee for
  the tracking of the posterior variances that allows BBKB to choose increasingly
  larger batches, improving over GP-BUCB. Moreover, we show that the same bound can
  be used to adaptively delay costly updates to the sparse GP approximation used by
  BBKB, achieving a near-constant per-step amortized cost. These findings are then
  confirmed in several experiments, where BBKB is much faster than state-of-the-art
  methods.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: calandriello20a
month: 0
tex_title: Near-linear time {G}aussian process optimization with adaptive batching
  and resparsification
firstpage: 1295
lastpage: 1305
page: 1295-1305
order: 1295
cycles: false
bibtex_author: Calandriello, Daniele and Carratino, Luigi and Lazaric, Alessandro
  and Valko, Michal and Rosasco, Lorenzo
author:
- given: Daniele
  family: Calandriello
- given: Luigi
  family: Carratino
- given: Alessandro
  family: Lazaric
- given: Michal
  family: Valko
- given: Lorenzo
  family: Rosasco
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
software: https://github.com/luigicarratino/batch-bkb
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/calandriello20a/calandriello20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
