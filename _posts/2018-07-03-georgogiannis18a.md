---
title: The Generalization Error of Dictionary Learning with Moreau Envelopes
booktitle: Proceedings of the 35th International Conference on Machine Learning
year: '2018'
volume: '80'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v80/georgogiannis18a/georgogiannis18a.pdf
url: http://proceedings.mlr.press/v80/georgogiannis2018a.html
abstract: This is a theoretical study on the sample complexity of dictionary learning
  with a general type of reconstruction loss. The goal is to estimate a $m \times
  d$ matrix $D$ of unit-norm columns when the only available information is a set
  of training samples. Points $x$ in $\mathbb{R}^m$ are subsequently approximated
  by the linear combination $Da$ after solving the problem $\min_{a ∈\mathbb{R}^d} 
  Φ(x - Da) + g(a)$; function $g:\mathbb{R}^d \to [0,+∞)$ is either an indicator function
  or a sparsity promoting regularizer. Here is considered the case where $ Φ(x) =
  \inf_{z ∈\mathbb{R}^m} { ||x-z||_2^2 + h(||z||_2)}$ and $h$ is an even and univariate
  function on the real line. Connections are drawn between $Φ$ and the Moreau envelope
  of $h$. A new sample complexity result concerning the $k$-sparse dictionary problem
  removes the spurious condition on the coherence of $D$ appearing in previous works.
  Finally, comments are made on the approximation error of certain families of losses.
  The derived generalization bounds are of order $\mathcal{O}(\sqrt{\log n /n})$ and
  valid without any further restrictions on the set of dictionaries with unit-norm
  columns.
layout: inproceedings
id: georgogiannis18a
tex_title: The Generalization Error of Dictionary Learning with Moreau Envelopes
firstpage: 1710
lastpage: 1718
page: 1710-1718
order: 1710
cycles: false
bibtex_editor: Dy, Jennifer and Krause, Andreas
editor:
- given: Jennifer
  family: Dy
- given: Andreas
  family: Krause
bibtex_author: Georgogiannis, Alexandros
author:
- given: Alexandros
  family: Georgogiannis
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
  link: http://proceedings.mlr.press/v80/georgogiannis18a/georgogiannis18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
