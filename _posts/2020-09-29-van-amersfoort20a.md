---
title: Uncertainty Estimation Using a Single Deep Deterministic Neural Network
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/van-amersfoort20a/van-amersfoort20a.pdf
url: http://proceedings.mlr.press/v119/vanamersfoort20a.html
abstract: We propose a method for training a deterministic deep model that can find
  and reject out of distribution data points at test time with a single forward pass.
  Our approach, deterministic uncertainty quantification (DUQ), builds upon ideas
  of RBF networks. We scale training in these with a novel loss function and centroid
  updating scheme and match the accuracy of softmax models. By enforcing detectability
  of changes in the input using a gradient penalty, we are able to reliably detect
  out of distribution data. Our uncertainty quantification scales well to large datasets,
  and using a single model, we improve upon or match Deep Ensembles in out of distribution
  detection on notable difficult dataset pairs such as FashionMNIST vs. MNIST, and
  CIFAR-10 vs. SVHN.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: van-amersfoort20a
month: 0
tex_title: Uncertainty Estimation Using a Single Deep Deterministic Neural Network
firstpage: 9690
lastpage: 9700
page: 9690-9700
order: 9690
cycles: false
bibtex_author: Van Amersfoort, Joost and Smith, Lewis and Teh, Yee Whye and Gal, Yarin
author:
- given: Joost
  family: Van Amersfoort
- given: Lewis
  family: Smith
- given: Yee Whye
  family: Teh
- given: Yarin
  family: Gal
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
software: https://github.com/y0ast/deterministic-uncertainty-quantification
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/van-amersfoort20a/van-amersfoort20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
