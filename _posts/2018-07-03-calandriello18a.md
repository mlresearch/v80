---
title: Improved Large-Scale Graph Learning through Ridge Spectral Sparsification
booktitle: Proceedings of the 35th International Conference on Machine Learning
year: '2018'
volume: '80'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v80/calandriello18a/calandriello18a.pdf
url: http://proceedings.mlr.press/v80/calandriello2018a.html
abstract: The representation and learning benefits of methods based on graph Laplacians,
  such as Laplacian smoothing or harmonic function solution for semi-supervised learning
  (SSL), are empirically and theoretically well supported. Nonetheless, the exact
  versions of these methods scale poorly with the number of nodes $n$ of the graph.
  In this paper, we combine a spectral sparsification routine with Laplacian learning.
  Given a graph $G$ as input, our algorithm computes a sparsifier in a distributed
  way in $O(n\log^3(n))$ time, $O(m\log^3(n))$ work and $O(n\log(n))$ memory, using
  only $\log(n)$ rounds of communication. Furthermore, motivated by the regularization
  often employed in learning algorithms, we show that constructing sparsifiers that
  preserve the spectrum of the Laplacian only up to the regularization level may drastically
  reduce the size of the final graph. By constructing a spectrally-similar graph,
  we are able to bound the error induced by the sparsification for a variety of downstream
  tasks (e.g., SSL). We empirically validate the theoretical guarantees on Amazon
  co-purchase graph and compare to the state-of-the-art heuristics.
layout: inproceedings
id: calandriello18a
tex_title: Improved Large-Scale Graph Learning through Ridge Spectral Sparsification
firstpage: 687
lastpage: 696
page: 687-696
order: 687
cycles: false
bibtex_editor: Dy, Jennifer and Krause, Andreas
editor:
- given: Jennifer
  family: Dy
- given: Andreas
  family: Krause
bibtex_author: Calandriello, Daniele and Koutis, Ioannis and Lazaric, Alessandro and
  Valko, Michal
author:
- given: Daniele
  family: Calandriello
- given: Ioannis
  family: Koutis
- given: Alessandro
  family: Lazaric
- given: Michal
  family: Valko
date: 2018-07-03
container-title: Proceedings of the 35th International Conference on Machine Learning
genre: inproceedings
issued:
  date-parts:
  - 2018
  - 7
  - 3
extras:
- label: Supplementary ZIP
  link: http://proceedings.mlr.press/v80/calandriello18a/calandriello18a-supp.zip
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
