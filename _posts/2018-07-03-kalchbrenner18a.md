---
title: Efficient Neural Audio Synthesis
booktitle: Proceedings of the 35th International Conference on Machine Learning
year: '2018'
volume: '80'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v80/kalchbrenner18a/kalchbrenner18a.pdf
url: http://proceedings.mlr.press/v80/kalchbrenner2018a.html
abstract: Sequential models achieve state-of-the-art results in audio, visual and
  textual domains with respect to both estimating the data distribution and generating
  desired samples. Efficient sampling for this class of models at the cost of little
  to no loss in quality has however remained an elusive problem. With a focus on text-to-speech
  synthesis, we describe a set of general techniques for reducing sampling time while
  maintaining high output quality. We first describe a single-layer recurrent neural
  network, the WaveRNN, with a dual softmax layer that matches the quality of the
  state-of-the-art WaveNet model. The compact form of the network makes it possible
  to generate 24 kHz 16-bit audio 4 times faster than real time on a GPU. Secondly,
  we apply a weight pruning technique to reduce the number of weights in the WaveRNN.
  We find that, for a constant number of parameters, large sparse networks perform
  better than small dense networks and this relationship holds past sparsity levels
  of more than 96%. The small number of weights in a Sparse WaveRNN makes it possible
  to sample high-fidelity audio on a mobile phone CPU in real time. Finally, we describe
  a new dependency scheme for sampling that lets us trade a constant number of non-local,
  distant dependencies for the ability to generate samples in batches. The Batch WaveRNN
  produces 8 samples per step without loss of quality and offers orthogonal ways of
  further increasing sampling efficiency.
layout: inproceedings
id: kalchbrenner18a
tex_title: Efficient Neural Audio Synthesis
firstpage: 2410
lastpage: 2419
page: 2410-2419
order: 2410
cycles: false
bibtex_editor: Dy, Jennifer and Krause, Andreas
editor:
- given: Jennifer
  family: Dy
- given: Andreas
  family: Krause
bibtex_author: Kalchbrenner, Nal and Elsen, Erich and Simonyan, Karen and Noury, Seb
  and Casagrande, Norman and Lockhart, Edward and Stimberg, Florian and van den Oord,
  Aaron and Dieleman, Sander and Kavukcuoglu, Koray
author:
- given: Nal
  family: Kalchbrenner
- given: Erich
  family: Elsen
- given: Karen
  family: Simonyan
- given: Seb
  family: Noury
- given: Norman
  family: Casagrande
- given: Edward
  family: Lockhart
- given: Florian
  family: Stimberg
- given: Aaron
  family: Oord
- given: Sander
  family: Dieleman
- given: Koray
  family: Kavukcuoglu
date: 2018-07-03
container-title: Proceedings of the 35th International Conference on Machine Learning
genre: inproceedings
issued:
  date-parts:
  - 2018
  - 7
  - 3
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
