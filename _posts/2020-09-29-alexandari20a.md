---
title: Maximum Likelihood with Bias-Corrected Calibration is Hard-To-Beat at Label
  Shift Adaptation
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/alexandari20a/alexandari20a.pdf
url: http://proceedings.mlr.press/v119/alexandari20a.html
abstract: 'Label shift refers to the phenomenon where the prior class probability
  p(y) changes between the training and test distributions, while the conditional
  probability p(x|y) stays fixed. Label shift arises in settings like medical diagnosis,
  where a classifier trained to predict disease given symptoms must be adapted to
  scenarios where the baseline prevalence of the disease is different. Given estimates
  of p(y|x) from a predictive model, Saerens et al. proposed an efficient maximum
  likelihood algorithm to correct for label shift that does not require model retraining,
  but a limiting assumption of this algorithm is that p(y|x) is calibrated, which
  is not true of modern neural networks. Recently, Black Box Shift Learning (BBSL)
  and Regularized Learning under Label Shifts (RLLS) have emerged as state-of-the-art
  techniques to cope with label shift when a classifier does not output calibrated
  probabilities, but both methods require model retraining with importance weights
  and neither has been benchmarked against maximum likelihood. Here we (1) show that
  combining maximum likelihood with a type of calibration we call bias-corrected calibration
  outperforms both BBSL and RLLS across diverse datasets and distribution shifts,
  (2) prove that the maximum likelihood objective is concave, and (3) introduce a
  principled strategy for estimating source-domain priors that improves robustness
  to poor calibration. This work demonstrates that the maximum likelihood with appropriate
  calibration is a formidable and efficient baseline for label shift adaptation; notebooks
  reproducing experiments available at https://github.com/kundajelab/labelshiftexperiments
  , video: https://youtu.be/ZBXjE9QTruE , blogpost: https://bit.ly/3kTds7J'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: alexandari20a
month: 0
tex_title: Maximum Likelihood with Bias-Corrected Calibration is Hard-To-Beat at Label
  Shift Adaptation
firstpage: 222
lastpage: 232
page: 222-232
order: 222
cycles: false
bibtex_author: Alexandari, Amr and Kundaje, Anshul and Shrikumar, Avanti
author:
- given: Amr
  family: Alexandari
- given: Anshul
  family: Kundaje
- given: Avanti
  family: Shrikumar
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
software: https://github.com/kundajelab/labelshiftexperiments
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/alexandari20a/alexandari20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
