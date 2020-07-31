---
title: Detecting and Correcting for Label Shift with Black Box Predictors
booktitle: Proceedings of the 35th International Conference on Machine Learning
year: '2018'
volume: '80'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v80/lipton18a/lipton18a.pdf
url: http://proceedings.mlr.press/v80/lipton2018a.html
abstract: Faced with distribution shift between training and test set, we wish to
  detect and quantify the shift, and to correct our classifiers without test set labels.
  Motivated by medical diagnosis, where diseases (targets), cause symptoms (observations),
  we focus on label shift, where the label marginal p(y) changes but the conditional
  p(x| y) does not. We propose Black Box Shift Estimation (BBSE) to estimate the test
  distribution p(y). BBSE exploits arbitrary black box predictors to reduce dimensionality
  prior to shift correction. While better predictors give tighter estimates, BBSE
  works even when predictors are biased, inaccurate, or uncalibrated, so long as their
  confusion matrices are invertible. We prove BBSE’s consistency, bound its error,
  and introduce a statistical test that uses BBSE to detect shift. We also leverage
  BBSE to correct classifiers. Experiments demonstrate accurate estimates and improved
  prediction, even on high-dimensional datasets of natural images.
layout: inproceedings
id: lipton18a
tex_title: Detecting and Correcting for Label Shift with Black Box Predictors
firstpage: 3122
lastpage: 3130
page: 3122-3130
order: 3122
cycles: false
bibtex_editor: Dy, Jennifer and Krause, Andreas
editor:
- given: Jennifer
  family: Dy
- given: Andreas
  family: Krause
bibtex_author: Lipton, Zachary and Wang, Yu-Xiang and Smola, Alexander
author:
- given: Zachary
  family: Lipton
- given: Yu-Xiang
  family: Wang
- given: Alexander
  family: Smola
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
  link: http://proceedings.mlr.press/v80/lipton18a/lipton18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
