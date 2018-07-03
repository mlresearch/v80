---
title: A Spline Theory of Deep Networks
booktitle: Proceedings of the 35th International Conference on Machine Learning
year: '2018'
volume: '80'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v80/balestriero18b/balestriero18b.pdf
url: http://proceedings.mlr.press/v80/balestriero2018b.html
abstract: We build a rigorous bridge between deep networks (DNs) and approximation
  theory via spline functions and operators.Our key result is that a large class of
  DNs can be written as a composition of <em>max-affine spline operators</em> (MASOs),
  which provide a powerful portal through which to view and analyze their inner workings.For
  instance, conditioned on the input signal, the output of a MASO DN can be written
  as a simple affine transformation of the input.This implies that a DN constructs
  a set of signal-dependent, class-specific templates against which the signal is
  compared via a simple inner product; we explore the links to the classical theory
  of optimal classification via matched filters and the effects of data memorization.Going
  further, we propose a simple penalty term that can be added to the cost function
  of any DN learning algorithm to force the templates to be orthogonal with each other;
  this leads to significantly improved classification performance and reduced overfitting
  with no change to the DN architecture. The spline partition of the input signal
  space opens up a new geometric avenue to study how DNs organize signals in a hierarchical
  fashion.As an application, we develop and validate a new distance metric for signals
  that quantifies the difference between their partition encodings.
layout: inproceedings
id: balestriero18b
tex_title: A Spline Theory of Deep Networks
firstpage: 383
lastpage: 392
page: 383-392
order: 383
cycles: false
bibtex_editor: Dy, Jennifer and Krause, Andreas
editor:
- given: Jennifer
  family: Dy
- given: Andreas
  family: Krause
bibtex_author: Balestriero, Randall and richard baraniuk
author:
- given: Randall
  family: Balestriero
- given: ''
  family: baraniuk
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
  link: http://proceedings.mlr.press/v80/balestriero18b/balestriero18b-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
