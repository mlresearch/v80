---
title: Asynchronous Byzantine Machine Learning (the case of SGD)
booktitle: Proceedings of the 35th International Conference on Machine Learning
year: '2018'
volume: '80'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v80/damaskinos18a/damaskinos18a.pdf
url: http://proceedings.mlr.press/v80/damaskinos2018a.html
abstract: 'Asynchronous distributed machine learning solutions have proven very effective
  so far, but always assuming perfectly functioning workers. In practice, some of
  the workers can however exhibit Byzantine behavior, caused by hardware failures,
  software bugs, corrupt data, or even malicious attacks. We introduce Kardam, the
  first distributed asynchronous stochastic gradient descent (SGD) algorithm that
  copes with Byzantine workers. Kardam consists of two complementary components: a
  filtering and a dampening component. The first is scalar-based and ensures resilience
  against 1/3 Byzantine workers. Essentially, this filter leverages the Lipschitzness
  of cost functions and acts as a self-stabilizer against Byzantine workers that would
  attempt to corrupt the progress of SGD. The dampening component bounds the convergence
  rate by adjusting to stale information through a generic gradient weighting scheme.
  We prove that Kardam guarantees almost sure convergence in the presence of asynchrony
  and Byzantine behavior, and we derive its convergence rate. We evaluate Kardam on
  the CIFAR100 and EMNIST datasets and measure its overhead with respect to non Byzantine-resilient
  solutions. We empirically show that Kardam does not introduce additional noise to
  the learning procedure but does induce a slowdown (the cost of Byzantine resilience)
  that we both theoretically and empirically show to be less than f/n, where f is
  the number of Byzantine failures tolerated and n the total number of workers. Interestingly,
  we also empirically observe that the dampening component is interesting in its own
  right for it enables to build an SGD algorithm that outperforms alternative staleness-aware
  asynchronous competitors in environments with honest workers.'
layout: inproceedings
id: damaskinos18a
tex_title: Asynchronous {B}yzantine Machine Learning (the case of {SGD})
firstpage: 1153
lastpage: 1162
page: 1153-1162
order: 1153
cycles: false
bibtex_editor: Dy, Jennifer and Krause, Andreas
editor:
- given: Jennifer
  family: Dy
- given: Andreas
  family: Krause
bibtex_author: Damaskinos, Georgios and Mhamdi, El Mahdi El and Guerraoui, Rachid
  and Patra, Rhicheek and Taziki, Mahsa
author:
- given: Georgios
  family: Damaskinos
- given: El Mahdi El
  family: Mhamdi
- given: Rachid
  family: Guerraoui
- given: Rhicheek
  family: Patra
- given: Mahsa
  family: Taziki
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
  link: http://proceedings.mlr.press/v80/damaskinos18a/damaskinos18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
