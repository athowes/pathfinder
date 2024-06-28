# Pathfinder

Discussion of the Pathfinder method for Bayesian inference for a  [CDC CFA](https://www.cdc.gov/forecast-outbreak-analytics/index.html) short-term forecasting lab meeting.

Slides available [here](athowes.github.io/pathfinder/pathfinder).

## Resources

* [Pathfinder: Parallel quasi-Newton variational inference](https://www.jmlr.org/papers/volume23/21-0889/21-0889.pdf) by Zhang, Carpenter, Gelman, and Vehtari
* [Talk by Bob Carpenter](https://www.youtube.com/watch?v=TPptuDp-w2E)
* [HMC fails when you initalize at the mode](https://statmodeling.stat.columbia.edu/2024/05/24/hmc-fails-when-you-initialize-at-the-mode/)
* [#90, Demystifying MCMC & Variational Inference, with Charles Margossian](https://www.youtube.com/watch?v=wEKqznbHHQw&t=10s)
* [Approximate inference vignette in `epidist`](https://github.com/epinowcast/epidist/pull/69) (a work in progress)
* [Using Pathfinder or other method to set initial values for sampling](https://discourse.mc-stan.org/t/using-pathfinder-or-other-method-to-set-initial-values-for-sampling/34960?page=2): a user documenting similar issues to those that I'm having using Pathfinder
