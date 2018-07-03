---
title: Learning a Mixture of Two Multinomial Logits
booktitle: Proceedings of the 35th International Conference on Machine Learning
year: '2018'
volume: '80'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v80/chierichetti18a/chierichetti18a.pdf
url: http://proceedings.mlr.press/v80/chierichetti2018a.html
abstract: The classical Multinomial Logit (MNL) is a behavioral model for user choice.
  In this model, a user is offered a slate of choices (a subset of a finite universe
  of $n$ items), and selects exactly one item from the slate, each with probability
  proportional to its (positive) weight. Given a set of observed slates and choices,
  the likelihood-maximizing item weights are easy to learn at scale, and easy to interpret.
  However, the model fails to represent common real-world behavior. As a result, researchers
  in user choice often turn to mixtures of MNLs, which are known to approximate a
  large class of models of rational user behavior. Unfortunately, the only known algorithms
  for this problem have been heuristic in nature. In this paper we give the first
  polynomial-time algorithms for exact learning of uniform mixtures of two MNLs. Interestingly,
  the parameters of the model can be learned for any $n$ by sampling the behavior
  of random users only on slates of sizes 2 and 3; in contrast, we show that slates
  of size 2 are insufficient by themselves.
layout: inproceedings
id: chierichetti18a
tex_title: Learning a Mixture of Two Multinomial Logits
firstpage: 960
lastpage: 968
page: 960-968
order: 960
cycles: false
bibtex_editor: Dy, Jennifer and Krause, Andreas
editor:
- given: Jennifer
  family: Dy
- given: Andreas
  family: Krause
bibtex_author: Chierichetti, Flavio and Kumar, Ravi and Tomkins, Andrew
author:
- given: Flavio
  family: Chierichetti
- given: Ravi
  family: Kumar
- given: Andrew
  family: Tomkins
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
  link: http://proceedings.mlr.press/v80/chierichetti18a/chierichetti18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
