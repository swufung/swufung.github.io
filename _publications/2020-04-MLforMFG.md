---
title: "A Machine Learning Framework for Solving High-Dimensional Mean Field Game and Mean Field Control Problems"
collection: publications
permalink: /publication/2020-04-MLforMFG
excerpt: 'We create an ML framework for solving high-dimensional mean field games.'
date: 2020-04-28
venue: '<i> Proceedings of the National Academy of Sciences (PNAS) </i>'
paperurl: 
---
<i> Joint with Lars Ruthotto, Stanley Osher, Wuchen Li, and Levon Nurbekyan.</i>

Abstract
======
Mean field games (MFG) and mean field control (MFC) play central roles in a variety of scientific disciplines such as physics, economics, and data science. While the mathematical theory of MFGs has matured considerably, the development of numerical methods has not kept pace with growing problem sizes and massive datasets. Since MFGs, in general, do not admit closed-form solutions, effective numerical algorithms are critical. Most existing numerical methods use meshes and thus are prone to the curse of dimensionality. Our framework is mesh-free, since it combines Lagrangian PDE solvers and neural networks. By penalizing violations of the underlying Hamilton–Jacobi–Bellman equation, we increase accuracy and computational efficiency. Transforming MFGs into machine learning problems promises exciting opportunities to advance application and theory.
[arXiv](https://arxiv.org/abs/1912.01825)
[Journal](https://www.pnas.org/content/117/17/9183)
