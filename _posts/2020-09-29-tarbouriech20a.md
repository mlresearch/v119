---
title: No-Regret Exploration in Goal-Oriented Reinforcement Learning
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/tarbouriech20a/tarbouriech20a.pdf
url: http://proceedings.mlr.press/v119/tarbouriech20a.html
abstract: Many popular reinforcement learning problems (e.g., navigation in a maze,
  some Atari games, mountain car) are instances of the episodic setting under its
  stochastic shortest path (SSP) formulation, where an agent has to achieve a goal
  state while minimizing the cumulative cost. Despite the popularity of this setting,
  the exploration-exploitation dilemma has been sparsely studied in general SSP problems,
  with most of the theoretical literature focusing on different problems (i.e., fixed-horizon
  and infinite-horizon) or making the restrictive loop-free SSP assumption (i.e.,
  no state can be visited twice during an episode). In this paper, we study the general
  SSP problem with no assumption on its dynamics (some policies may actually never
  reach the goal). We introduce UC-SSP, the first no-regret algorithm in this setting,
  and prove a regret bound scaling as $\widetilde{\mathcal{O}}( D S \sqrt{ A D K})$
  after $K$ episodes for any unknown SSP with $S$ states, $A$ actions, positive costs
  and SSP-diameter $D$, defined as the smallest expected hitting time from any starting
  state to the goal. We achieve this result by crafting a novel stopping rule, such
  that UC-SSP may interrupt the current policy if it is taking too long to achieve
  the goal and switch to alternative policies that are designed to rapidly terminate
  the episode.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: tarbouriech20a
month: 0
tex_title: No-Regret Exploration in Goal-Oriented Reinforcement Learning
firstpage: 9428
lastpage: 9437
page: 9428-9437
order: 9428
cycles: false
bibtex_author: Tarbouriech, Jean and Garcelon, Evrard and Valko, Michal and Pirotta,
  Matteo and Lazaric, Alessandro
author:
- given: Jean
  family: Tarbouriech
- given: Evrard
  family: Garcelon
- given: Michal
  family: Valko
- given: Matteo
  family: Pirotta
- given: Alessandro
  family: Lazaric
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
  link: http://proceedings.mlr.press/v119/tarbouriech20a/tarbouriech20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
