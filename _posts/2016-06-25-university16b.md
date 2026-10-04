---
abstract: We introduce overdispersed black-box variational inference, a method to
  reduce the variance of the Monte Carlo estimator of the gradient in black-box variational
  inference. Instead of taking samples from the variational distribution, we use importance
  sampling to take samples from an overdispersed distribution in the same exponential
  family as the variational approximation. Our approach is general since it can be
  readily applied to any exponential family distribution, which is the typical choice
  for the variational approximation. We run experiments on two non-conjugate probabilistic
  models to show that our method effectively reduces the variance, and the overhead
  introduced by the computation of the proposal parameters and the importance weights
  is negligible. We find that our overdispersed importance sampling scheme provides
  lower variance than black-box variational inference, even when the latter uses twice
  the number of samples. This results in faster convergence of the black-box inference
  procedure.
title: Overdispersed Black-Box Variational Inference
year: '2016'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university16b
month: 0
tex_title: Overdispersed Black-Box Variational Inference
firstpage: 68
lastpage: 77
page: 68-77
order: 68
cycles: false
bibtex_author: University, Francisco Ruiz Columbia and Business, Michalis Titsias
  Athens University of Economics and and University, david Blei Columbia
author:
- given: Francisco Ruiz Columbia
  family: University
- given: Michalis Titsias Athens University of Economics
  family: Business
- given: david Blei Columbia
  family: University
  prefix: and
date: 2016-06-25
note: Reissued by PMLR on 04 October 2026.
address:
container-title: Proceedings of the 32nd Conference on Uncertainty in Artificial Intelligence
volume: R14
genre: inproceedings
issued:
  date-parts:
  - 2016
  - 6
  - 25
pdf: https://raw.githubusercontent.com/mlresearch/r14/main/assets/university16b/university16b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
