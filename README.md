# JustKnowStuff

Taking a page out of Patrick Kidger's blog and blogging about topics included in (https://kidger.site/thoughts/just-know-stuff/). Implementations and links will be placed here. 

## Table of Contents ##
- What are the necessary elements of Deep Learning?
  + https://github.com/nicholicaron/JustKnowStuff/tree/main/dl_sys
- Know both forward- and reverse-mode autodifferentiation
  + https://www.nicholi.me/autodiff
- What is Strassen's Algorithm? How are matrix multiplies actually done in practice? Write your own implementation of multihead attention
  + https://www.nicholi.me/take-heed-of-the-hydra/
- What are Winograd Convolutions? Write your own implementation of a convolutional layer
  + https://www.nicholi.me/convolutions/
- Know the universal approximation theorem
- Learn the basics of Graph Neural Networks (E.g. what is oversmoothing?) How do these generalize CNNs?
- Learn modern Transformer architectures. Build a toy implementation.
- Learn U-Nets. Build a toy implementation.
- Know how residual networks are discretized ordinary differential equations
- Know how Gated Recurrent Units (GRUs) are also discretized differential equations
- Know how stochastic gradient descent is also a discretized differential equation too! (Yes, including the "stochastic": that's a Monte-Carlo discretization of an expectation.) These are gradient flows
- Know what is meant by the manifold hypothesis
- Learn the basics of policy gradients. Implement PPO to solve cart-pole.
- Learn KL divergence, Wasserstein distance, MMD distance
- Learn normalizing flows, VAEs, WGANs, score-based diffusion models. Implement a basic score-based diffusion from scratch
- Try the basics of distributes training of a model. (Over multiple GPUs; multiple computers)
- Know how to do hyperparameter optimization via Bayesian optimization. [Optional: Try doing this in a distributed fashion, with a main thread sending hyperparameter jobs to different machines, and receiving results back]
- Learn the formulae for Adadelta, Adam, etc. What were the innovations for each optimizer? (Momentum, second moments, ...) What are some of the newer ones that are now being used (Adabelief, RAdam, NAdamW, etc. -- this is a flavor of the month kinda field)
- Learn why we use first-order optimization techniques (SGD and friends) rather than anything else. (Why not Gauss-Newton? Why not Newton-Raphson? Why not Levenberg-Marquardt?) 
