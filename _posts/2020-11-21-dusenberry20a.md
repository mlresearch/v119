---
title: Efficient and Scalable Bayesian Neural Nets with Rank-1 Factors
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/dusenberry20a/dusenberry20a.pdf
url: http://proceedings.mlr.press/v119/dusenberry20a.html
abstract: Bayesian neural networks (BNNs) demonstrate promising success in improving
  the robustness and uncertainty quantification of modern deep learning. However,
  they generally struggle with underfitting at scale and parameter efficiency. On
  the other hand, deep ensembles have emerged as alternatives for uncertainty quantification
  that, while outperforming BNNs on certain problems, also suffer from efficiency
  issues. It remains unclear how to combine the strengths of these two approaches
  and remediate their common issues. To tackle this challenge, we propose a rank-1
  parameterization of BNNs, where each weight matrix involves only a distribution
  on a rank-1 subspace. We also revisit the use of mixture approximate posteriors
  to capture multiple modes, where unlike typical mixtures, this approach admits a
  significantly smaller memory increase (e.g., only a 0.4% increase for a ResNet-50
  mixture of size 10). We perform a systematic empirical study on the choices of prior,
  variational posterior, and methods to improve training. For ResNet-50 on ImageNet,
  Wide ResNet 28-10 on CIFAR-10/100, and an RNN on MIMIC-III, rank-1 BNNs achieve
  state-of-the-art performance across log-likelihood, accuracy, and calibration on
  the test sets and out-of-distribution variants.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dusenberry20a
month: 0
tex_title: Efficient and Scalable {B}ayesian Neural Nets with Rank-1 Factors
firstpage: 2782
lastpage: 2792
page: 2782-2792
order: 2782
cycles: false
bibtex_author: Dusenberry, Michael and Jerfel, Ghassen and Wen, Yeming and Ma, Yian
  and Snoek, Jasper and Heller, Katherine and Lakshminarayanan, Balaji and Tran, Dustin
author:
- given: Michael
  family: Dusenberry
- given: Ghassen
  family: Jerfel
- given: Yeming
  family: Wen
- given: Yian
  family: Ma
- given: Jasper
  family: Snoek
- given: Katherine
  family: Heller
- given: Balaji
  family: Lakshminarayanan
- given: Dustin
  family: Tran
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
software: https://github.com/google/edward2
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/dusenberry20a/dusenberry20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
