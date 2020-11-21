---
title: 'LazyIter: A Fast Algorithm for Counting Markov Equivalent DAGs and Designing
  Experiments'
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/ahmaditeshnizi20a/ahmaditeshnizi20a.pdf
url: http://proceedings.mlr.press/v119/ahmaditeshnizi20a.html
abstract: The causal relationships among a set of random variables are commonly represented
  by a Directed Acyclic Graph (DAG), where there is a directed edge from variable
  $X$ to variable $Y$ if $X$ is a direct cause of $Y$. From the purely observational
  data, the true causal graph can be identified up to a Markov Equivalence Class (MEC),
  which is a set of DAGs with the same conditional independencies between the variables.
  The size of an MEC is a measure of complexity for recovering the true causal graph
  by performing interventions. We propose a method for efficient iteration over possible
  MECs given intervention results. We utilize the proposed method for computing MEC
  sizes and experiment design in active and passive learning settings. Compared to
  previous work for computing the size of MEC, our proposed algorithm reduces the
  time complexity by a factor of $O(n)$ for sparse graphs where $n$ is the number
  of variables in the system. Additionally, integrating our approach with dynamic
  programming, we design an optimal algorithm for passive experiment design. Experimental
  results show that our proposed algorithms for both computing the size of MEC and
  experiment design outperform the state of the art.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ahmaditeshnizi20a
month: 0
tex_title: "{L}azy{I}ter: A Fast Algorithm for Counting {M}arkov Equivalent {DAG}s
  and Designing Experiments"
firstpage: 125
lastpage: 133
page: 125-133
order: 125
cycles: false
bibtex_author: Ahmaditeshnizi, Ali and Salehkaleybar, Saber and Kiyavash, Negar
author:
- given: Ali
  family: Ahmaditeshnizi
- given: Saber
  family: Salehkaleybar
- given: Negar
  family: Kiyavash
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
software: https://github.com/teshnizi/LazyIter
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/ahmaditeshnizi20a/ahmaditeshnizi20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
