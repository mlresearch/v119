---
title: Low-Rank Bottleneck in Multi-head Attention Models
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/bhojanapalli20a/bhojanapalli20a.pdf
url: http://proceedings.mlr.press/v119/bhojanapalli20a.html
abstract: Attention based Transformer architecture has enabled significant advances
  in the field of natural language processing. In addition to new pre-training techniques,
  recent improvements crucially rely on working with a relatively larger embedding
  dimension for tokens. Unfortunately, this leads to models that are prohibitively
  large to be employed in the downstream tasks. In this paper we identify one of the
  important factors contributing to the large embedding size requirement. In particular,
  our analysis highlights that the scaling between the number of heads and the size
  of each head in the current architecture gives rise to a low-rank bottleneck in
  attention heads, causing this limitation. We further validate this in our experiments.
  As a solution we propose to set the head size of an attention unit to input sequence
  length, and independent of the number of heads, resulting in multi-head attention
  layers with provably more expressive power. We empirically show that this allows
  us to train models with a relatively smaller embedding dimension and with better
  performance scaling.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhojanapalli20a
month: 0
tex_title: Low-Rank Bottleneck in Multi-head Attention Models
firstpage: 864
lastpage: 873
page: 864-873
order: 864
cycles: false
bibtex_author: Bhojanapalli, Srinadh and Yun, Chulhee and Rawat, Ankit Singh and Reddi,
  Sashank and Kumar, Sanjiv
author:
- given: Srinadh
  family: Bhojanapalli
- given: Chulhee
  family: Yun
- given: Ankit Singh
  family: Rawat
- given: Sashank
  family: Reddi
- given: Sanjiv
  family: Kumar
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
  link: http://proceedings.mlr.press/v119/bhojanapalli20a/bhojanapalli20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
