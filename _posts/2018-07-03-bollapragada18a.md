---
title: A Progressive Batching L-BFGS Method for Machine Learning
booktitle: Proceedings of the 35th International Conference on Machine Learning
year: '2018'
volume: '80'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v80/bollapragada18a/bollapragada18a.pdf
url: http://proceedings.mlr.press/v80/bollapragada2018a.html
abstract: The standard L-BFGS method relies on gradient approximations that are not
  dominated by noise, so that search directions are descent directions, the line search
  is reliable, and quasi-Newton updating yields useful quadratic models of the objective
  function. All of this appears to call for a full batch approach, but since small
  batch sizes give rise to faster algorithms with better generalization properties,
  L-BFGS is currently not considered an algorithm of choice for large-scale machine
  learning applications. One need not, however, choose between the two extremes represented
  by the full batch or highly stochastic regimes, and may instead follow a progressive
  batching approach in which the sample size increases during the course of the optimization.
  In this paper, we present a new version of the L-BFGS algorithm that combines three
  basic components - progressive batching, a stochastic line search, and stable quasi-Newton
  updating - and that performs well on training logistic regression and deep neural
  networks. We provide supporting convergence theory for the method.
layout: inproceedings
id: bollapragada18a
tex_title: A Progressive Batching L-{BFGS} Method for Machine Learning
firstpage: 620
lastpage: 629
page: 620-629
order: 620
cycles: false
bibtex_editor: Dy, Jennifer and Krause, Andreas
editor:
- given: Jennifer
  family: Dy
- given: Andreas
  family: Krause
bibtex_author: Bollapragada, Raghu and Nocedal, Jorge and Mudigere, Dheevatsa and
  Shi, Hao-Jun and Tang, Ping Tak Peter
author:
- given: Raghu
  family: Bollapragada
- given: Jorge
  family: Nocedal
- given: Dheevatsa
  family: Mudigere
- given: Hao-Jun
  family: Shi
- given: Ping Tak Peter
  family: Tang
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
  link: http://proceedings.mlr.press/v80/bollapragada18a/bollapragada18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
