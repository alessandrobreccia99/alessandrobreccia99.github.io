---
title: "At the Edge of Laziness: Scaling Limits of Catastrophic Forgetting"
collection: publications
category: conferences
excerpt: 'Continual Learning, Neural Tangent Kernel, DMFT, Infinitely Wide NNs, lazy/rich regimes'
date: 2025-01-31
venue: 'Pre-print ICML 2025'
paperurl: 'https://openreview.net/forum?id=edhBkkYS8R'
---

Despite recent efforts, neural networks still struggle to learn in non-stationary environments, and our understanding of catastrophic forgetting is far from complete. In this work, we perform a systematic study on the impact of model scale and the degree of feature learning in continual learning. We reconcile existing contradictory observations on scale in the literature, by differentiating between lazy and rich training regimes through a variable parametrization of the architecture. We show that increasing model width is only beneficial when it reduces the amount of feature learning, yielding more laziness. Using the framework of dynamical mean field theory, we then study the infinite width dynamics of the model in the feature learning regime and characterize catastrophic forgetting, extending prior theoretical results limited to the lazy regime. We study the intricate relationship between feature learning, task non-stationarity, and forgetting, finding that high feature learning is only beneficial with highly similar tasks. Furthermore, we identify a transition - modulated by task similarity - where the model exits an effectively lazy regime with low forgetting to enter a rich regime with significant forgetting. We term this transition region Edge of Laziness. Finally, our findings reveal that neural networks achieve optimal performance at a critical level of feature learning, which depends on task non-stationarity and transfers across model scales. This work provides a unified perspective on the role of scale and feature learning in continual learning.