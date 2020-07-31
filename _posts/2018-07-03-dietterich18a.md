---
title: Discovering and Removing Exogenous State Variables and Rewards for Reinforcement
  Learning
booktitle: Proceedings of the 35th International Conference on Machine Learning
year: '2018'
volume: '80'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v80/dietterich18a/dietterich18a.pdf
url: http://proceedings.mlr.press/v80/dietterich2018a.html
abstract: Exogenous state variables and rewards can slow down reinforcement learning
  by injecting uncontrolled variation into the reward signal. We formalize exogenous
  state variables and rewards and identify conditions under which an MDP with exogenous
  state can be decomposed into an exogenous Markov Reward Process involving only the
  exogenous state+reward and an endogenous Markov Decision Process defined with respect
  to only the endogenous rewards. We also derive a variance-covariance condition under
  which Monte Carlo policy evaluation on the endogenous MDP is accelerated compared
  to using the full MDP. Similar speedups are likely to carry over to all RL algorithms.
  We develop two algorithms for discovering the exogenous variables and test them
  on several MDPs. Results show that the algorithms are practical and can significantly
  speed up reinforcement learning.
layout: inproceedings
id: dietterich18a
tex_title: Discovering and Removing Exogenous State Variables and Rewards for Reinforcement
  Learning
firstpage: 1262
lastpage: 1270
page: 1262-1270
order: 1262
cycles: false
bibtex_editor: Dy, Jennifer and Krause, Andreas
editor:
- given: Jennifer
  family: Dy
- given: Andreas
  family: Krause
bibtex_author: Dietterich, Thomas and Trimponias, George and Chen, Zhitang
author:
- given: Thomas
  family: Dietterich
- given: George
  family: Trimponias
- given: Zhitang
  family: Chen
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
  link: http://proceedings.mlr.press/v80/dietterich18a/dietterich18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
