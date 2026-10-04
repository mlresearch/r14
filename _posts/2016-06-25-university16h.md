---
abstract: The Hamiltonian Monte Carlo (HMC) method has become significantly popular
  in recent years.It is the state-of-the-art MCMC sampler due to its more efficient
  exploration to the parameter space than the standard random-walk based proposal.The
  key idea behind HMC is that it makes use of first-order gradient information about
  the target distribution. In this paper, we propose a novel dynamics.The new dynamics
  uses second-order geometric information about the desired distribution.The second-order
  information is estimated by using a quasi-Newton method (say, the BFGS method),
  so it does not bring heavy computational burden.Moreover, our theoretical analysis
  guarantees that this dynamics remains the target distribution invariant.As a result,
  the proposed quasi-Newton Hamiltonian Monte Carlo (QNHMC) algorithm traverses the
  parameter space more efficiently than the standard HMC and produces a less correlated
  series of samples.Finally, empirical evaluation on simulated data verifies the effectiveness
  and efficiency of our approach.We also conduct applications of QNHMC in Bayesian
  logistic regression and online Bayesian matrix factorization problems.
title: Quasi-Newton Hamiltonian Monte Carlo
year: '2016'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university16h
month: 0
tex_title: Quasi-{N}ewton {H}amiltonian {M}onte {C}arlo
firstpage: 306
lastpage: 315
page: 306-315
order: 306
cycles: false
bibtex_author: University, Tianfan Fu Shanghai Jiao Tong and University, Luo Luo Shanghai
  Jiao Tong and University, Zhihua Zhang Shanghai Jiao Tong
author:
- given: Tianfan Fu Shanghai Jiao Tong
  family: University
- given: Luo Luo Shanghai Jiao Tong
  family: University
- given: Zhihua Zhang Shanghai Jiao Tong
  family: University
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
pdf: https://raw.githubusercontent.com/mlresearch/r14/main/assets/university16h/university16h.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
