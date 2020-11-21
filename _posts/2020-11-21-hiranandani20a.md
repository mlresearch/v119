---
title: Optimization and Analysis of the pAp@k Metric for Recommender Systems
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/hiranandani20a/hiranandani20a.pdf
url: http://proceedings.mlr.press/v119/hiranandani20a.html
abstract: Modern recommendation and notification systems must be robust to data imbalance,
  limitations on the number of recommendations/notifications, and heterogeneous engagement
  profiles across users. The pAp@k metric, which combines the partial-AUC and the
  precision@k metrics, was recently proposed to evaluate such recommendation systems
  and has been used in real-world deployments. Conceptually, pAp@k measures the probability
  of correctly ranking a top-ranked positive instance over top-ranked negative instances.
  Due to the combinatorial aspect surfaced by top-ranked points, little is known about
  the characteristics and optimization methods of pAp@k. In this paper, we analyze
  the learning-theoretic properties of pAp@k, particularly its benefits in evaluating
  modern recommender systems, and propose novel surrogates that are consistent under
  certain data regularity conditions. We then provide gradient descent based algorithms
  to optimize the surrogates directly. Our analysis and experimental evaluation suggest
  that pAp@k indeed exhibits a certain dual behavior with respect to partial-AUC and
  precision@k. Moreover, the proposed methods outperform all the baselines in various
  applications. Taken together, our results motivate the use of pAp@k for large-scale
  recommender systems with heterogeneous user-engagement.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hiranandani20a
month: 0
tex_title: Optimization and Analysis of the p{A}p@k Metric for Recommender Systems
firstpage: 4260
lastpage: 4270
page: 4260-4270
order: 4260
cycles: false
bibtex_author: Hiranandani, Gaurush and Vijitbenjaronk, Warut and Koyejo, Sanmi and
  Jain, Prateek
author:
- given: Gaurush
  family: Hiranandani
- given: Warut
  family: Vijitbenjaronk
- given: Sanmi
  family: Koyejo
- given: Prateek
  family: Jain
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
software: https://github.com/gaurush-hiranandani/pap-k
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/hiranandani20a/hiranandani20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
