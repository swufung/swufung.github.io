---
title: "An Uncertainty-Weighted Asynchronous ADMM Method for Parallel PDE Parameter Estimation"
collection: publications
permalink: /publication/2019-10-UQADMMPDE
excerpt: 'We develop a parallel ADMM method for multiphysics PDE parameter estimation problems.'
date: 2019-10-29
venue: '<i> SIAM Journal on Scientific Computing (SISC) </i>'
paperurl: 
---
<i> Joint with Lars Ruthotto.</i>

Abstract
======
We consider a global variable consensus alternating direction method of multipliers (ADMM) algorithm for estimating parameters of partial differential equations (PDEs) asynchronously and in parallel. Motivated by problems with many measurements, we partition the data and distribute the resulting subproblems among the available workers. Since each subproblem can be associated with different forward models and right-hand sides, this provides ample options for tailoring the method to different applications, including multisource and multiphysics PDE parameter estimation problems. We also consider an asynchronous variant of consensus ADMM to reduce communication and latency. Our key contribution is a novel weighting scheme that empirically increases the progress made in early iterations of the consensus ADMM scheme and is attractive when using a large number of subproblems. This makes consensus ADMM competitive for solving PDE parameter estimation, which incurs immense cost per iteration. The weights in our scheme are related to the uncertainty associated with the solutions of each subproblem. We exemplarily show that the weighting scheme combined with the asynchronous implementation reduces the time-to-solution and lowers the communication costs for a 3D single-physics and multiphysics PDE parameter estimation problems.

[Journal](https://epubs.siam.org/doi/abs/10.1137/18M119166X?journalCode=sjoce3)
