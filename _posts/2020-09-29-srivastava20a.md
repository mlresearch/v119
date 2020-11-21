---
title: Robustness to Spurious Correlations via Human Annotations
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/srivastava20a/srivastava20a.pdf
url: http://proceedings.mlr.press/v119/srivastava20a.html
abstract: The reliability of machine learning systems critically assumes that the
  associations between features and labels remain similar between training and test
  distributions. However, unmeasured variables, such as confounders, break this assumption—useful
  correlations between features and labels at training time can become useless or
  even harmful at test time. For example, high obesity is generally predictive for
  heart disease, but this relation may not hold for smokers who generally have lower
  rates of obesity and higher rates of heart disease. We present a framework for making
  models robust to spurious correlations by leveraging humans’ common sense knowledge
  of causality. Specifically, we use human annotation to augment each training example
  with a potential unmeasured variable (i.e. an underweight patient with heart disease
  may be a smoker), reducing the problem to a covariate shift problem. We then introduce
  a new distributionally robust optimization objective over unmeasured variables (UV-DRO)
  to control the worst-case loss over possible test- time shifts. Empirically, we
  show improvements of 5–10% on a digit recognition task confounded by rotation, and
  1.5–5% on the task of analyzing NYPD Police Stops confounded by location.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: srivastava20a
month: 0
tex_title: Robustness to Spurious Correlations via Human Annotations
firstpage: 9109
lastpage: 9119
page: 9109-9119
order: 9109
cycles: false
bibtex_author: Srivastava, Megha and Hashimoto, Tatsunori and Liang, Percy
author:
- given: Megha
  family: Srivastava
- given: Tatsunori
  family: Hashimoto
- given: Percy
  family: Liang
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
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/srivastava20a/srivastava20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
