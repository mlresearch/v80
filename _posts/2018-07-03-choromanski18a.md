---
title: Structured Evolution with Compact Architectures for Scalable Policy Optimization
booktitle: Proceedings of the 35th International Conference on Machine Learning
year: '2018'
volume: '80'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v80/choromanski18a/choromanski18a.pdf
url: http://proceedings.mlr.press/v80/choromanski2018a.html
abstract: We present a new method of blackbox optimization via gradient approximation
  with the use of structured random orthogonal matrices, providing more accurate estimators
  than baselines and with provable theoretical guarantees. We show that this algorithm
  can be successfully applied to learn better quality compact policies than those
  using standard gradient estimation techniques. The compact policies we learn have
  several advantages over unstructured ones, including faster training algorithms
  and faster inference. These benefits are important when the policy is deployed on
  real hardware with limited resources. Further, compact policies provide more scalable
  architectures for derivative-free optimization (DFO) in high-dimensional spaces.
  We show that most robotics tasks from the OpenAI Gym can be solved using neural
  networks with less than 300 parameters, with almost linear time complexity of the
  inference phase, with up to 13x fewer parameters relative to the Evolution Strategies
  (ES) algorithm introduced by Salimans et al. (2017). We do not need heuristics such
  as fitness shaping to learn good quality policies, resulting in a simple and theoretically
  motivated training mechanism.
layout: inproceedings
id: choromanski18a
tex_title: Structured Evolution with Compact Architectures for Scalable Policy Optimization
firstpage: 969
lastpage: 977
page: 969-977
order: 969
cycles: false
bibtex_editor: Dy, Jennifer and Krause, Andreas
editor:
- given: Jennifer
  family: Dy
- given: Andreas
  family: Krause
bibtex_author: Choromanski, Krzysztof and Rowland, Mark and Sindhwani, Vikas and Turner,
  Richard E. and Weller, Adrian
author:
- given: Krzysztof
  family: Choromanski
- given: Mark
  family: Rowland
- given: Vikas
  family: Sindhwani
- given: Richard E.
  family: Turner
- given: Adrian
  family: Weller
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
  link: http://proceedings.mlr.press/v80/choromanski18a/choromanski18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
