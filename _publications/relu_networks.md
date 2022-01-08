---
title: "Initializing ReLU networks in an expressive subspace of weights"
collection: publications
authors: 'Dayal Singh and G J Sreejith'
permalink: /publication/relu_networks
excerpt: 'We analyze signal propagation in ReLU networks with anti-correlated weights and demonstrate that it has an order-to-chaos phase transition, unlike the uncorrelated case. Furthermore, we demonstrate that ReLU networks initialized at this criticality train faster.'
date: 2022-01-07
venue: 'Under review'
paperurl: 'https://arxiv.org/abs/2103.12499'
---
Using a mean-field theory of signal propagation, we analyze the evolution of correlations between two signals propagating forward through a deep ReLU network with correlated weights. Signals become highly correlated in deep ReLU networks with uncorrelated weights. We show that ReLU networks with anti-correlated weights can avoid this fate and have a chaotic phase where the signal correlations saturate below unity. Consistent with this analysis, we find that networks initialized with anti-correlated weights can train faster (in a teacher-student setting) by taking advantage of the increased expressivity in the chaotic phase. Combining this with a previously proposed strategy of using an asymmetric initialization to reduce dead node probability, we propose an initialization scheme that allows faster training and learning than the best-known initializations.
[arXiv](https://arxiv.org/abs/2103.12499)
