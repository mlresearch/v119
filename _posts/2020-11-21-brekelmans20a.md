---
title: 'All in the Exponential Family: Bregman Duality in Thermodynamic Variational
  Inference'
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/brekelmans20a/brekelmans20a.pdf
url: http://proceedings.mlr.press/v119/brekelmans20a.html
abstract: The recently proposed Thermodynamic Variational Objective (TVO) leverages
  thermodynamic integration to provide a family of variational inference objectives,
  which both tighten and generalize the ubiquitous Evidence Lower Bound (ELBO). However,
  the tightness of TVO bounds was not previously known, an expensive grid search was
  used to choose a “schedule” of intermediate distributions, and model learning suffered
  with ostensibly tighter bounds. In this work, we propose an exponential family interpretation
  of the geometric mixture curve underlying the TVO and various path sampling methods,
  which allows us to characterize the gap in TVO likelihood bounds as a sum of KL
  divergences. We propose to choose intermediate distributions using equal spacing
  in the moment parameters of our exponential family, which matches grid search performance
  and allows the schedule to adaptively update over the course of training. Finally,
  we derive a doubly reparameterized gradient estimator which improves model learning
  and allows the TVO to benefit from more refined bounds. To further contextualize
  our contributions, we provide a unified framework for understanding thermodynamic
  integration and the TVO using Taylor series remainders.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: brekelmans20a
month: 0
tex_title: 'All in the Exponential Family: {B}regman Duality in Thermodynamic Variational
  Inference'
firstpage: 1111
lastpage: 1122
page: 1111-1122
order: 1111
cycles: false
bibtex_author: Brekelmans, Rob and Masrani, Vaden and Wood, Frank and Steeg, Greg
  Ver and Galstyan, Aram
author:
- given: Rob
  family: Brekelmans
- given: Vaden
  family: Masrani
- given: Frank
  family: Wood
- given: Greg Ver
  family: Steeg
- given: Aram
  family: Galstyan
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
software: https://media.icml.cc/Conferences/ICML2020/v119/brekelmans20a-supp.zip
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/brekelmans20a/brekelmans20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
