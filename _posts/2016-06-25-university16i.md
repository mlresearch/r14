---
abstract: To address the scalability issue of kernel methods, random features are
  commonly used for kernel approximation (Rahimi and Recht, 2007). They map the input
  data to a randomized low-dimensional feature space and apply fast linear learning
  algorithms on it. However, to achieve high precision results, one might still need
  large number of random features, which is infeasible in large-scale applications.
  Dai et al. (2014) address this issue by recomputing the random features of small
  batches in each iteration instead of pre-generating for the whole dataset and keeping
  them in the memory. The algorithm increases the number of random features linearly
  with iterations, which can reduce the approximation error to arbitrarily small.
  A drawback of this approach is that the large number of random features slows down
  the prediction and gradient evaluation after several iterations. We propose two
  algorithms to remedy this situation by "utilizing" old random features instead of
  adding new features in certain iterations. By checking the expected descent amount,
  the proposed algorithm selects "important" old features to update. The resulting
  procedure is surprisingly simple without enhancing the complexity of the original
  algorithm but effective in practice. We conduct empirical studies on both medium
  and large-scale datasets, such as ImageNet, to demonstrate the power of the proposed
  algorithms.
title: 'Utilize Old Coordinates: Faster Doubly Stochastic Gradients for Kernel Methods'
year: '2016'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university16i
month: 0
tex_title: 'Utilize Old Coordinates: Faster Doubly Stochastic Gradients for Kernel
  Methods'
firstpage: 316
lastpage: 325
page: 316-325
order: 316
cycles: false
bibtex_author: University, Chun-Liang Li Carnegie Mellon and University, Barnabas
  Poczos Carnegie Mellon
author:
- given: Chun-Liang Li Carnegie Mellon
  family: University
- given: Barnabas Poczos Carnegie Mellon
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
pdf: https://raw.githubusercontent.com/mlresearch/r14/main/assets/university16i/university16i.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
