# Awesome PPL [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of **Probabilistic Programming Languages (PPLs)**, inference libraries, and learning resources.

Probabilistic programming integrates **probabilistic models** and **code** into a unified paradigm.  
Instead of coding “how” to compute, you specify *what* your model is, and the PPL system automatically performs inference — from Bayesian statistical models to deep probabilistic programs.

---

## Contents
- [Python](#python)
- [Julia](#julia)
- [R](#r)
- [Scala](#scala)
- [JavaScript](#javascript)
- [Logic & Specialized](#logic--specialized)
- [Contributing](#contributing)

---

## Python
- [**PyMC**](https://www.pymc.io/) – Declarative, graph-based PPL for applied Bayesian statistics. Supports NUTS, ADVI, SMC.
  *Tutorial*: [PyMC Examples](https://www.pymc.io/projects/examples/en/stable/)
- [**Pyro**](https://pyro.ai/) – Universal (generative) PPL built on PyTorch. Strong in deep probabilistic modeling, VI, and HMC/NUTS.  
  *Tutorial*: [Pyro Tutorials](https://pyro.ai/examples/)
- [**NumPyro**](https://num.pyro.ai/en/0.8.0/index.html) – JAX-based Pyro, offering major speedups via JIT compilation.  
  *Tutorial*: [NumPyro Tutorials](https://num.pyro.ai/en/0.8.0/tutorials/)
- [**TensorFlow Probability**](https://www.tensorflow.org/probability) – Library of probabilistic building blocks in TensorFlow/JAX. Supports HMC, VI, and optimizers.  
  *Tutorial*: [TFP Examples](https://www.tensorflow.org/probability/examples)
- [**Stan**](https://mc-stan.org/) (via CmdStanPy/PyStan) – Declarative, static-graph language with gold-standard NUTS implementation.  
  *Tutorial*: [Stan User’s Guide](https://mc-stan.org/users/documentation/)
- [**Bean Machine**](https://beanmachine.org/) – Meta’s research PPL for programmable inference using PyTorch.  
  *Tutorial*: [Bean Machine Tutorials](https://beanmachine.org/tutorials/)
- [**Edward2**](https://github.com/google/edward2) – A lightweight, low-level probabilistic programming library built on TensorFlow, JAX, or NumPy, emphasizing flexibility via a single abstraction (“random variable”) and tracing-based model manipulation :contentReference[oaicite:0]{index=0}.  
  *Tutorial*: [Edward Tutorials](https://edwardlib.org/tutorials/) :contentReference[oaicite:1]{index=1}
- [**GenJAX**](http://genjax.gen.dev/) – JAX-based implementation of Gen with programmable variational inference.  
  *Tutorial*: [GenJAX Documentation](https://genjax.gen.dev/cookbook/active/intro.html)
- [**BlackJAX**](https://blackjax-devs.github.io/blackjax/) – Sampling algorithms for JAX (HMC, NUTS, Riemannian HMC, SMC) designed for composability with other JAX-based PPLs.  
  *Tutorial*: [BlackJAX Examples](https://blackjax-devs.github.io/blackjax/examples.html)

## Julia
- [**Turing.jl**](https://turinglang.org/) – General-purpose, high-performance PPL supporting NUTS, HMC, PMCMC, Gibbs, VI.  
  *Tutorial*: [Turing.jl Getting Started](https://turinglang.org/docs/getting-started/)
- [**Gen.jl**](https://www.gen.dev/) – Research-oriented PPL with programmable inference, hybrid MCMC/VI/SMC algorithms.  
  *Tutorial*: [Gen.jl Documentation](https://www.gen.dev/docs/)

## R
- [**Stan**](https://mc-stan.org/) (via rstan, cmdstanr) – Seamless integration with R workflows.  
  *Tutorial*: [Stan User’s Guide](https://mc-stan.org/users/documentation/)
- [**greta**](https://greta-stats.org/) – Write models in R syntax, backed by TensorFlow for CPU/GPU execution.  
  *Tutorial*: [greta Getting Started](https://greta-stats.org/articles/get_started.html)
- [**JAGS/BUGS**](https://sourceforge.net/projects/mcmc-jags/) – Pioneering declarative PPLs using Gibbs sampling.  
  *Tutorial*: [JAGS Documentation](https://mcmc-jags.sourceforge.io/)

## Scala
- [**Figaro**](https://cra.com/blog/figaro/) – Expressive Scala PPL with broad algorithm support (MCMC, SMC, exact inference).  
  *Tutorial*: [Figaro Guide](https://cra.com/wp-content/uploads/2018/08/FigaroUserGuide.pdf)
- [**Rainier**](https://rainier.fit/) – High-performance, static-graph Scala PPL inspired by Stan/PyMC.  
  *Tutorial*: [Rainier Examples](https://github.com/stripe/rainier/tree/master/examples)

## JavaScript
- [**WebPPL**](http://webppl.org/) – Universal PPL for the web. Runs in-browser or Node.js, popular in cognitive science.  
  *Tutorial*: [WebPPL Web Book](http://probmods.org/)

## Logic & Specialized
- [**ProbLog**](https://dtai.cs.kuleuven.be/problog) – Probabilistic logic programming over large, uncertain knowledge bases.  
  *Tutorial*: [ProbLog Tutorials](https://dtai.cs.kuleuven.be/problog/tutorial.html)
- [**Dice**](http://dicelang.cs.ucla.edu/) – High-speed exact inference for discrete probabilistic programs via WMC.  
  *Tutorial*: [Dice Documentation](http://dicelang.cs.ucla.edu/about/)
 

---

## Contributing
Contributions are welcome! Please ensure:
- Each entry has a link, short description, and follows the existing format.
- Include an official tutorial link when available.
- Keep descriptions objective and concise.

---

_Last updated: 2025-08-14_
