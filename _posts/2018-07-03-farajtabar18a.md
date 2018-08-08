---
title: More Robust Doubly Robust Off-policy Evaluation
booktitle: Proceedings of the 35th International Conference on Machine Learning
year: '2018'
volume: '80'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v80/farajtabar18a/farajtabar18a.pdf
url: http://proceedings.mlr.press/v80/farajtabar2018a.html
abstract: We study the problem of off-policy evaluation (OPE) in reinforcement learning
  (RL), where the goal is to estimate the performance of a policy from the data generated
  by another policy(ies). In particular, we focus on the doubly robust (DR) estimators
  that consist of an importance sampling (IS) component and a performance model, and
  utilize the low (or zero) bias of IS and low variance of the model at the same time.
  Although the accuracy of the model has a huge impact on the overall performance
  of DR, most of the work on using the DR estimators in OPE has been focused on improving
  the IS part, and not much on how to learn the model. In this paper, we propose alternative
  DR estimators, called more robust doubly robust (MRDR), that learn the model parameter
  by minimizing the variance of the DR estimator. We first present a formulation for
  learning the DR model in RL. We then derive formulas for the variance of the DR
  estimator in both contextual bandits and RL, such that their gradients w.r.t. the
  model parameters can be estimated from the samples, and propose methods to efficiently
  minimize the variance. We prove that the MRDR estimators are strongly consistent
  and asymptotically optimal. Finally, we evaluate MRDR in bandits and RL benchmark
  problems, and compare its performance with the existing methods.
layout: inproceedings
id: farajtabar18a
tex_title: More Robust Doubly Robust Off-policy Evaluation
firstpage: 1447
lastpage: 1456
page: 1447-1456
order: 1447
cycles: false
bibtex_editor: Dy, Jennifer and Krause, Andreas
editor:
- given: Jennifer
  family: Dy
- given: Andreas
  family: Krause
bibtex_author: Farajtabar, Mehrdad and Chow, Yinlam and Ghavamzadeh, Mohammad
author:
- given: Mehrdad
  family: Farajtabar
- given: Yinlam
  family: Chow
- given: Mohammad
  family: Ghavamzadeh
date: 2018-07-03
container-title: Proceedings of the 35th International Conference on Machine Learning
genre: inproceedings
issued:
  date-parts:
  - 2018
  - 7
  - 3
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v80/farajtabar18a/farajtabar18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
