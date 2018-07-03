---
title: 'Not All Samples Are Created Equal: Deep Learning with Importance Sampling'
booktitle: Proceedings of the 35th International Conference on Machine Learning
year: '2018'
volume: '80'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v80/katharopoulos18a/katharopoulos18a.pdf
url: http://proceedings.mlr.press/v80/katharopoulos2018a.html
abstract: 'Deep Neural Network training spends most of the computation on examples
  that are properly handled, and could be ignored. We propose to mitigate this phenomenon
  with a principled importance sampling scheme that focuses computation on "informative"
  examples, and reduces the variance of the stochastic gradients during training.
  Our contribution is twofold: first, we derive a tractable upper bound to the per-sample
  gradient norm, and second we derive an estimator of the variance reduction achieved
  with importance sampling, which enables us to switch it on when it will result in
  an actual speedup. The resulting scheme can be used by changing a few lines of code
  in a standard SGD procedure, and we demonstrate experimentally on image classification,
  CNN fine-tuning, and RNN training, that for a fixed wall-clock time budget, it provides
  a reduction of the train losses of up to an order of magnitude and a relative improvement
  of test errors between 5% and 17%.'
layout: inproceedings
id: katharopoulos18a
tex_title: 'Not All Samples Are Created Equal: Deep Learning with Importance Sampling'
firstpage: 2530
lastpage: 2539
page: 2530-2539
order: 2530
cycles: false
bibtex_editor: Dy, Jennifer and Krause, Andreas
editor:
- given: Jennifer
  family: Dy
- given: Andreas
  family: Krause
bibtex_author: Katharopoulos, Angelos and Fleuret, Francois
author:
- given: Angelos
  family: Katharopoulos
- given: Francois
  family: Fleuret
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
  link: http://proceedings.mlr.press/v80/katharopoulos18a/katharopoulos18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
