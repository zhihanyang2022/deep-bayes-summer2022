# Slides on Bayesian + Deep Learning

- Week 1: an overview of Bayesian deep learning, summarizing Part 1 and 3 of 2020 ICML tutorial on Bayesian deep learning by Andrew Wilson
  - Lingering questions:
    - Relationship between generalization, inductive bias, marginal likelihood and bias-and-variance
    - How to interpret MC dropout?
- Week 2: deep ensembles as approximate Bayesian inference
  - Very interesting perspective alongside MCMC and deterministic methods (e.g., variational inference)
- Week 3: weight uncertainty in neural networks
  - Fully factorized approximate posterior obtained via variational inference
  - Connection to Thompson Sampling for contextual multi-armed bandit
- Week 4: subspace inference & mode connectivity of deep neural networks
- Week 5: an introduction to the auto-encoding variational bayes algorithm
- Week 6: Gaussian Mixture VAE and Variational RNN; some interesting thoughts:
  - VAE + mixed-effect (who wrote this digit)
  - VRNN with bidirectional LSTM to summarize observations both earlier and later
  - Connection between VRNN and Hidden Markov Model
  - Discrete latent variables might allow for tight ELBO? But is this better? See [Tighter Variational Bounds are Not Necessarily Better](https://proceedings.mlr.press/v80/rainforth18b.html)
  - VRNN + random variable that takes the same value across time
  
Potential papers:
- Rethinking parameter counting in deep models: effective dimensionality revisited (https://arxiv.org/pdf/2003.02139.pdf)
- A scalable laplace approximation for neural networks (https://openreview.net/pdf?id=Skdvd2xAZ)
- Bayesian learning via stochastic gradient langevin dynamics 
- Gradient Estimation Using Stochastic Computation Graph
