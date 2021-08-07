---
title: "Alternating the Population and Control Neural Networks to Solve High-Dimensional Stochastic Mean-Field Games"
collection: publications
permalink: /publication/2021-08-APACNet
excerpt: 'We solve high-dimensional mean field games by leveraging their connections to GANs.'
date: 2021-08
venue: '<i> Proceedings of the National Academy of Sciences (PNAS) </i>'
paperurl: 
---
<i> Joint with Alex Tong Lin, Levon Nurbekyan, Wuchen Li, and Stanley Osher.</i>

Abstract
======
We present APAC-Net, an alternating population and agent control neural network for solving stochastic mean-field games (MFGs). Our algorithm is geared toward high-dimensional instances of MFGs that are not approachable with existing solution methods. We achieve this in two steps. First, we take advantage of the underlying variational primal-dual structure that MFGs exhibit and phrase it as a convex–concave saddle-point problem. Second, we parameterize the value and density functions by two neural networks, respectively. By phrasing the problem in this manner, solving the MFG can be interpreted as a special case of training a generative adversarial network (GAN). We show the potential of our method on up to 100-dimensional MFG problems.
[arXiv](https://arxiv.org/abs/2002.10113)
[Journal](https://www.pnas.org/content/118/31/e2024713118)
