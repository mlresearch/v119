---
title: How recurrent networks implement contextual processing in sentiment analysis
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/maheswaranathan20a/maheswaranathan20a.pdf
url: http://proceedings.mlr.press/v119/maheswaranathan20a.html
abstract: Neural networks have a remarkable capacity for contextual processing{—}using
  recent or nearby inputs to modify processing of current input. For example, in natural
  language, contextual processing is necessary to correctly interpret negation (e.g.
  phrases such as "not bad"). However, our ability to understand how networks process
  context is limited. Here, we propose general methods for reverse engineering recurrent
  neural networks (RNNs) to identify and elucidate contextual processing. We apply
  these methods to understand RNNs trained on sentiment classification. This analysis
  reveals inputs that induce contextual effects, quantifies the strength and timescale
  of these effects, and identifies sets of these inputs with similar properties. Additionally,
  we analyze contextual effects related to differential processing of the beginning
  and end of documents. Using the insights learned from the RNNs we improve baseline
  Bag-of-Words models with simple extensions that incorporate contextual modification,
  recovering greater than 90% of the RNN’s performance increase over the baseline.
  This work yields a new understanding of how RNNs process contextual information,
  and provides tools that should provide similar insight more broadly.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: maheswaranathan20a
month: 0
tex_title: How recurrent networks implement contextual processing in sentiment analysis
firstpage: 6608
lastpage: 6619
page: 6608-6619
order: 6608
cycles: false
bibtex_author: Maheswaranathan, Niru and Sussillo, David
author:
- given: Niru
  family: Maheswaranathan
- given: David
  family: Sussillo
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
  link: http://proceedings.mlr.press/v119/maheswaranathan20a/maheswaranathan20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
