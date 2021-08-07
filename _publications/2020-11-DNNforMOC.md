---
title: "A Neural Network Approach Applied to Multi-Agent Optimal Control"
collection: publications
permalink: /publication/2021-04-DNNforMOC
excerpt: 'We use DNNs to solve high-dimensional multi-agent control problems.'
date: 2020-11
venue: '<i> European Control Conference 2021 (ECC2021) </i>'
paperurl: 
---
<i> Joint with Derek Onken, Levon Nurbekyan, Xingjian Li, Stanley Osher, and Lars Ruthotto.</i>

Abstract
======
We propose a neural network approach for solving high-dimensional optimal control problems. In particular, we focus on multi-agent control problems with obstacle and collision avoidance. These problems immediately become high-dimensional, even for moderate phase-space dimensions per agent. Our approach fuses the Pontryagin Maximum Principle and Hamilton-Jacobi-Bellman (HJB) approaches and parameterizes the value function with a neural network. Our approach yields controls in a feedback form for quick calculation and robustness to moderate disturbances to the system. We train our model using the objective function and optimality conditions of the control problem. Therefore, our training algorithm neither involves a data generation phase nor solutions from another algorithm. Our model uses empirically effective HJB penalizers for efficient training. By training on a distribution of initial states, we ensure the controls' optimality is achieved on a large portion of the state-space. Our approach is grid-free and scales efficiently to dimensions where grids become impractical or infeasible. We demonstrate our approach's effectiveness on a 150-dimensional multi-agent problem with obstacles.
[arXiv](https://arxiv.org/abs/2011.04757)
