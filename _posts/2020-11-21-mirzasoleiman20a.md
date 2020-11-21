---
title: Coresets for Data-efficient Training of Machine Learning Models
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/mirzasoleiman20a/mirzasoleiman20a.pdf
url: http://proceedings.mlr.press/v119/mirzasoleiman20a.html
abstract: Incremental gradient (IG) methods, such as stochastic gradient descent and
  its variants are commonly used for large scale optimization in machine learning.
  Despite the sustained effort to make IG methods more data-efficient, it remains
  an open question how to select a training data subset that can theoretically and
  practically perform on par with the full dataset. Here we develop CRAIG, a method
  to select a weighted subset (or coreset) of training data that closely estimates
  the full gradient by maximizing a submodular function. We prove that applying IG
  to this subset is guaranteed to converge to the (near)optimal solution with the
  same convergence rate as that of IG for convex optimization. As a result, CRAIG
  achieves a speedup that is inversely proportional to the size of the subset. To
  our knowledge, this is the first rigorous method for data-efficient training of
  general machine learning models. Our extensive set of experiments show that CRAIG,
  while achieving practically the same solution, speeds up various IG methods by up
  to 6x for logistic regression and 3x for training deep neural networks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mirzasoleiman20a
month: 0
tex_title: Coresets for Data-efficient Training of Machine Learning Models
firstpage: 6950
lastpage: 6960
page: 6950-6960
order: 6950
cycles: false
bibtex_author: Mirzasoleiman, Baharan and Bilmes, Jeff and Leskovec, Jure
author:
- given: Baharan
  family: Mirzasoleiman
- given: Jeff
  family: Bilmes
- given: Jure
  family: Leskovec
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
  link: http://proceedings.mlr.press/v119/mirzasoleiman20a/mirzasoleiman20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
