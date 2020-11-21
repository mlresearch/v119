---
title: Self-Concordant Analysis of Frank-Wolfe Algorithms
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/dvurechensky20a/dvurechensky20a.pdf
url: http://proceedings.mlr.press/v119/dvurechensky20a.html
abstract: Projection-free optimization via different variants of the Frank-Wolfe (FW),
  a.k.a. Conditional Gradient method has become one of the cornerstones in optimization
  for machine learning since in many cases the linear minimization oracle is much
  cheaper to implement than projections and some sparsity needs to be preserved. In
  a number of applications, e.g. Poisson inverse problems or quantum state tomography,
  the loss is given by a self-concordant (SC) function having unbounded curvature,
  implying absence of theoretical guarantees for the existing FW methods. We use the
  theory of SC functions to provide a new adaptive step size for FW methods and prove
  global convergence rate O(1/k) after k iterations. If the problem admits a stronger
  local linear minimization oracle, we construct a novel FW method with linear convergence
  rate for SC functions.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dvurechensky20a
month: 0
tex_title: Self-Concordant Analysis of Frank-{W}olfe Algorithms
firstpage: 2814
lastpage: 2824
page: 2814-2824
order: 2814
cycles: false
bibtex_author: Dvurechensky, Pavel and Ostroukhov, Petr and Safin, Kamil and Shtern,
  Shimrit and Staudigl, Mathias
author:
- given: Pavel
  family: Dvurechensky
- given: Petr
  family: Ostroukhov
- given: Kamil
  family: Safin
- given: Shimrit
  family: Shtern
- given: Mathias
  family: Staudigl
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
software: https://github.com/kamil-safin/SCFW
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/dvurechensky20a/dvurechensky20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
