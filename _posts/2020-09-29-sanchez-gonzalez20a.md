---
title: Learning to Simulate Complex Physics with Graph Networks
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/sanchez-gonzalez20a/sanchez-gonzalez20a.pdf
url: http://proceedings.mlr.press/v119/sanchezgonzalez20a.html
abstract: 'Here we present a machine learning framework and model implementation that
  can learn to simulate a wide variety of challenging physical domains, involving
  fluids, rigid solids, and deformable materials interacting with one another. Our
  framework—which we term "Graph Network-based Simulators" (GNS)—represents the state
  of a physical system with particles, expressed as nodes in a graph, and computes
  dynamics via learned message-passing. Our results show that our model can generalize
  from single-timestep predictions with thousands of particles during training, to
  different initial conditions, thousands of timesteps, and at least an order of magnitude
  more particles at test time. Our model was robust to hyperparameter choices across
  various evaluation metrics: the main determinants of long-term performance were
  the number of message-passing steps, and mitigating the accumulation of error by
  corrupting the training data with noise. Our GNS framework advances the state-of-the-art
  in learned physical simulation, and holds promise for solving a wide range of complex
  forward and inverse problems.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sanchez-gonzalez20a
month: 0
tex_title: Learning to Simulate Complex Physics with Graph Networks
firstpage: 8459
lastpage: 8468
page: 8459-8468
order: 8459
cycles: false
bibtex_author: Sanchez-Gonzalez, Alvaro and Godwin, Jonathan and Pfaff, Tobias and
  Ying, Rex and Leskovec, Jure and Battaglia, Peter
author:
- given: Alvaro
  family: Sanchez-Gonzalez
- given: Jonathan
  family: Godwin
- given: Tobias
  family: Pfaff
- given: Rex
  family: Ying
- given: Jure
  family: Leskovec
- given: Peter
  family: Battaglia
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
software: https://github.com/deepmind/deepmind-research/tree/master/learning_to_simulate
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/sanchez-gonzalez20a/sanchez-gonzalez20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
