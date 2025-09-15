# Geometry and factorization of multivariate Markov chains with applications to the swapping algorithm

**Authors:** Michael C.H. Choi, Youjia Wang and Geoffrey Wolfer

**arXiv:** [https://arxiv.org/abs/2404.12589](https://arxiv.org/abs/2404.12589)

This repository contains the code for the experiments in the paper *Geometry and factorization of multivariate Markov chains with applications to the swapping algorithm*. We compare original samplers such as lifted Metropolis-Hastings or swapping algorithm with projection samplers:

## Example: discrete V-shaped bimodal distribution

Consider a discrete bimodal distribution with two modes at -20, +20. The 3-temperature swapping algorithm (blue), initialized at -20, is unable to traverse to the other mode. On the other hand, the projection sampler (orange) is able to mix well.

![animation](swapping_trajectories.gif)
