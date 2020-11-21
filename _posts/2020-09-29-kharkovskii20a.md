---
title: Private Outsourced Bayesian Optimization
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/kharkovskii20a/kharkovskii20a.pdf
url: http://proceedings.mlr.press/v119/kharkovskii20a.html
abstract: This paper presents the private-outsourced-Gaussian process-upper confidence
  bound (PO-GP-UCB) algorithm, which is the first algorithm for privacy-preserving
  Bayesian optimization (BO) in the outsourced setting with a provable performance
  guarantee. We consider the outsourced setting where the entity holding the dataset
  and the entity performing BO are represented by different parties, and the dataset
  cannot be released non-privately. For example, a hospital holds a dataset of sensitive
  medical records and outsources the BO task on this dataset to an industrial AI company.
  The key idea of our approach is to make the BO performance of our algorithm similar
  to that of non-private GP-UCB run using the original dataset, which is achieved
  by using a random projection-based transformation that preserves both privacy and
  the pairwise distances between inputs. Our main theoretical contribution is to show
  that a regret bound similar to that of the standard GP-UCB algorithm can be established
  for our PO-GP-UCB algorithm. We empirically evaluate the performance of our PO-GP-UCB
  algorithm with synthetic and real-world datasets.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kharkovskii20a
month: 0
tex_title: Private Outsourced {B}ayesian Optimization
firstpage: 5231
lastpage: 5242
page: 5231-5242
order: 5231
cycles: false
bibtex_author: Kharkovskii, Dmitrii and Dai, Zhongxiang and Low, Bryan Kian Hsiang
author:
- given: Dmitrii
  family: Kharkovskii
- given: Zhongxiang
  family: Dai
- given: Bryan Kian Hsiang
  family: Low
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
software: https://github.com/Mitan/po-gp-ucb
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/kharkovskii20a/kharkovskii20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
