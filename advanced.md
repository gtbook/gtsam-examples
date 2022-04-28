# Advanced Inference

All SLAM examples above only solve for the maximum-a-posteriori (MAP) solution, and provide a Gaussian approximation to the posterior. This section demos several techniques that go beyond that to get closer to the true posterior.

The following examples are provided

- PlanarSLAMExample_sampling: various sampling methods, incl. MCMC, to sample from the true posterior.
- PlanarSLAMExample_lbp: loopy belief propagation, contrasted with MCMC
- PlanarSLAMExample_gvi: a Variational Bayes inference approach due to Barfoot et al.

