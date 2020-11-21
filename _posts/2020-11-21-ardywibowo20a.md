---
title: 'NADS: Neural Architecture Distribution Search for Uncertainty Awareness'
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/ardywibowo20a/ardywibowo20a.pdf
url: http://proceedings.mlr.press/v119/ardywibowo20a.html
abstract: Machine learning (ML) systems often encounter Out-of-Distribution (OoD)
  errors when dealing with testing data coming from a distribution different from
  training data. It becomes important for ML systems in critical applications to accurately
  quantify its predictive uncertainty and screen out these anomalous inputs. However,
  existing OoD detection approaches are prone to errors and even sometimes assign
  higher likelihoods to OoD samples. Unlike standard learning tasks, there is currently
  no well established guiding principle for designing OoD detection architectures
  that can accurately quantify uncertainty. To address these problems, we first seek
  to identify guiding principles for designing uncertainty-aware architectures, by
  proposing Neural Architecture Distribution Search (NADS). NADS searches for a distribution
  of architectures that perform well on a given task, allowing us to identify common
  building blocks among all uncertainty-aware architectures. With this formulation,
  we are able to optimize a stochastic OoD detection objective and construct an ensemble
  of models to perform OoD detection. We perform multiple OoD detection experiments
  and observe that our NADS performs favorably, with up to 57% improvement in accuracy
  compared to state-of-the-art methods among 15 different testing configurations.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ardywibowo20a
month: 0
tex_title: "{NADS}: Neural Architecture Distribution Search for Uncertainty Awareness"
firstpage: 356
lastpage: 366
page: 356-366
order: 356
cycles: false
bibtex_author: Ardywibowo, Randy and Boluki, Shahin and Gong, Xinyu and Wang, Zhangyang
  and Qian, Xiaoning
author:
- given: Randy
  family: Ardywibowo
- given: Shahin
  family: Boluki
- given: Xinyu
  family: Gong
- given: Zhangyang
  family: Wang
- given: Xiaoning
  family: Qian
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
  link: http://proceedings.mlr.press/v119/ardywibowo20a/ardywibowo20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
