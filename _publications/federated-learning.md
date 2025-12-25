---
title: "Gradient-free Federated Learning Methods with l1 and l2-randomization for Non-smooth Convex Stochastic Optimization Problems"
collection: publications
category: manuscripts
permalink: /publication/federated-learning
excerpt: 'This paper studies non-smooth problems of convex stochastic optimization.'
date: 2023-05-21
venue: 'Computational Mathematics and Mathematical Physics'
citation: 'Alashqar, B. A., et al. "Gradient-free federated learning methods with l 1 and l 2-randomization for non-smooth convex stochastic optimization problems." Computational Mathematics and Mathematical Physics 63.9 (2023): 1600-1653.'
---
This paper studies non-smooth problems of convex stochastic optimization. Using the smoothing technique based on the replacement of the function value at the considered point by the averaged function value over a ball (in l1-norm or l2-norm) of a small radius centered at this point, and then the original problem is reduced to a smooth problem (whose Lipschitz constant of the gradient is inversely proportional to the radius of the ball). An essential property of the smoothing used is the possibility of calculating an unbiased estimation of the gradient of a smoothed function based only on realizations of the original function. The obtained smooth stochastic optimization problem is proposed to be solved in a distributed federated learning architecture (the problem is solved in parallel: nodes make local steps, e.g. stochastic gradient descent, then communicate—all with all, then all this is repeated). The goal of the article is to build on the basis of modern achievements in the field of gradient–free non-smooth optimization and in the field of federated learning gradient-free methods for solving problems of non-smooth stochastic optimization in the architecture of federated learning.
