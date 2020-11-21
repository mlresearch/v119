---
title: Learning and Sampling of Atomic Interventions from Observations
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/bhattacharyya20a/bhattacharyya20a.pdf
url: http://proceedings.mlr.press/v119/bhattacharyya20a.html
abstract: "We study the problem of efficiently estimating the effect of an intervention
  on a single variable using observational samples. Our goal is to give algorithms
  with polynomial time and sample complexity in a non-parametric setting. Tian and
  Pearl (AAAI ’02) have exactly characterized the class of causal graphs for which
  causal effects of atomic interventions can be identified from observational data.
  We make their result quantitative. Suppose \U0001D4AB is a causal model on a set
  V of n observable variables with respect to a given causal graph G, and let do(x)
  be an identifiable intervention on a variable X. We show that assuming that G has
  bounded in-degree and bounded c-components (k) and that the observational distribution
  satisfies a strong positivity condition: (i) [Evaluation] There is an algorithm
  that outputs with probability 2/3 an evaluator for a distribution P^ that satisfies
  TV(P(V | do(x)), P^(V)) < eps using m=O (n/eps^2) samples from P and O(mn) time.
  The evaluator can return in O(n) time the probability P^(v) for any assignment v
  to V. (ii) [Sampling] There is an algorithm that outputs with probability 2/3 a
  sampler for a distribution P^ that satisfies TV(P(V | do(x)), P^(V)) < eps using
  m=O (n/eps^2) samples from P and O(mn) time. The sampler returns an iid sample from
  P^ with probability 1 in O(n) time. We extend our techniques to estimate P(Y | do(x))
  for a subset Y of variables of interest. We also show lower bounds for the sample
  complexity, demonstrating that our sample complexity has optimal dependence on the
  parameters n and eps, as well as if k=1 on the strong positivity parameter."
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattacharyya20a
month: 0
tex_title: Learning and Sampling of Atomic Interventions from Observations
firstpage: 842
lastpage: 853
page: 842-853
order: 842
cycles: false
bibtex_author: Bhattacharyya, Arnab and Gayen, Sutanu and Kandasamy, Saravanan and
  Maran, Ashwin and Variyam, Vinodchandran N.
author:
- given: Arnab
  family: Bhattacharyya
- given: Sutanu
  family: Gayen
- given: Saravanan
  family: Kandasamy
- given: Ashwin
  family: Maran
- given: Vinodchandran N.
  family: Variyam
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
  link: http://proceedings.mlr.press/v119/bhattacharyya20a/bhattacharyya20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
