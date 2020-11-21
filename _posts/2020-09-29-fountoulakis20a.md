---
title: p-Norm Flow Diffusion for Local Graph Clustering
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/fountoulakis20a/fountoulakis20a.pdf
url: http://proceedings.mlr.press/v119/fountoulakis20a.html
abstract: Local graph clustering and the closely related seed set expansion problem
  are primitives on graphs that are central to a wide range of analytic and learning
  tasks such as local clustering, community detection, semi-supervised learning, nodes
  ranking and feature inference. Prior work on local graph clustering mostly falls
  into two categories with numerical and combinatorial roots respectively, in this
  work we draw inspiration from both fields and propose a family of convex optimization
  formulations based on the idea of diffusion with $p$-norm network flow for $p\in
  (1,\infty)$. In the context of local clustering, we characterize the optimal solutions
  for these optimization problems and show their usefulness in finding low conductance
  cuts around input seed set. In particular, we achieve quadratic approximation of
  conductance in the case of $p=2$ similar to the Cheeger-type bounds of spectral
  methods, constant factor approximation when $p\rightarrow\infty$ similar to max-flow
  based methods, and a smooth transition for general $p$ values in between. Thus,
  our optimization formulation can be viewed as bridging the numerical and combinatorial
  approaches, and we can achieve the best of both worlds in terms of speed and noise
  robustness. We show that the proposed problem can be solved in strongly local running
  time for $p\ge 2$ and conduct empirical evaluations on both synthetic and real-world
  graphs to illustrate our approach compares favorably with existing methods.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: fountoulakis20a
month: 0
tex_title: p-Norm Flow Diffusion for Local Graph Clustering
firstpage: 3222
lastpage: 3232
page: 3222-3232
order: 3222
cycles: false
bibtex_author: Fountoulakis, Kimon and Wang, Di and Yang, Shenghao
author:
- given: Kimon
  family: Fountoulakis
- given: Di
  family: Wang
- given: Shenghao
  family: Yang
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
software: https://github.com/s-h-yang/pNormFlowDiffusion
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/fountoulakis20a/fountoulakis20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
