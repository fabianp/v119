---
title: Naive Exploration is Optimal for Online LQR
booktitle: Proceedings of the 37th International Conference on Machine Learning
year: '2020'
pdf: http://proceedings.mlr.press/v119/simchowitz20a/simchowitz20a.pdf
url: http://proceedings.mlr.press/v119/simchowitz20a.html
abstract: We consider the problem of online adaptive control of the linear quadratic
  regulator, where the true system parameters are unknown. We prove new upper and
  lower bounds demonstrating that the optimal regret scales as $\tilde{\Theta} (\sqrt{d_{\mathbf{u}}^2
  d_{\mathbf{x}} T})$, where $T$ is the number of time steps, $d_{\mathbf{u}}$ is
  the dimension of the input space, and $d_{\mathbf{x}}$ is the dimension of the system
  state. Notably, our lower bounds rule out the possibility of a $\mathrm{poly}(\log{T})$-regret
  algorithm, which had been conjectured due to the apparent strong convexity of the
  problem. Our upper bound is attained by a simple variant of certainty equivalent
  control, where the learner selects control inputs according to the optimal controller
  for their estimate of the system while injecting exploratory random noise. While
  this approach was shown to achieve $\sqrt{T}$ regret by Mania et al. (2019), we
  show that if the learner continually refines their estimates of the system matrices,
  the method attains optimal dimension dependence as well. Central to our upper and
  lower bounds is a new approach for controlling perturbations of Riccati equations
  called the self-bounding ODE method, which we use to derive suboptimality bounds
  for the certainty equivalent controller synthesized from estimated system dynamics.
  This in turn enables regret upper bounds which hold for any stabilizable instance
  and scale with natural control-theoretic quantities.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: simchowitz20a
month: 0
tex_title: Naive Exploration is Optimal for Online {LQR}
firstpage: 8937
lastpage: 8948
page: 8937-8948
order: 8937
cycles: false
bibtex_author: Simchowitz, Max and Foster, Dylan
author:
- given: Max
  family: Simchowitz
- given: Dylan
  family: Foster
date: 2020-11-21
address: 
container-title: Proceedings of the 37th International Conference on Machine Learning
volume: '119'
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 11
  - 21
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v119/simchowitz20a/simchowitz20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
