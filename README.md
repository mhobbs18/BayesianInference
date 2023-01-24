# BayesianInference

> THIS IS A WORK IN PROGRESS :hourglass:

---

### A tutorial on Bayesian inference to identify material parameters in solid mechanics

This repository contains Jupyter Notebooks to recreate the examples published in the following paper ([link](https://doi.org/10.1007/s11831-018-09311-x)):

>Rappel, H., Beex, L. A., Hale, J. S., Noels, L., & Bordas, S. P. A. (2020). A tutorial on Bayesian inference to identify material parameters in solid mechanics. *Archives of Computational Methods in Engineering*, 27(2), 361-385.

The reader might also be interested in the following paper ([link](https://doi.org/10.1016/j.probengmech.2018.08.004)):

>Rappel, H., Beex, L. A., Noels, L., & Bordas, S. P. A. (2019). Identifying elastoplastic parameters with Bayes’ theorem considering output error, input error and model uncertainty. *Probabilistic Engineering Mechanics*, 55, 28-41.

Additional resources that the reader might find useful are listed below

>Hogg, D. W., Bovy, J., & Lang, D. (2010). Data analysis recipes: Fitting a model to data. arXiv preprint [arXiv:1008.4686](https://doi.org/10.48550/arXiv.1008.4686).

>Hogg, D. W., & Foreman-Mackey, D. (2018). Data analysis recipes: Using markov chain monte carlo. *The Astrophysical Journal Supplement Series*, 236(1), 11. [doi.org/10.3847/1538-4365/aab76e](https://doi.org/10.3847/1538-4365/aab76e)

---

### Paper abstract

The aim of this contribution is to explain in a straightforward manner how Bayesian inference can be used to identify material parameters of material models for solids. Bayesian approaches have already been used for this purpose, but most of the literature is not necessarily easy to understand for those new to the field. The reason for this is that most literature focuses either on complex statistical and machine learning concepts and/or on relatively complex mechanical models. In order to introduce the approach as gently as possible, we only focus on stress–strain measurements coming from uniaxial tensile tests and we only treat elastic and elastoplastic material models. Furthermore, the stress–strain measurements are created artificially in order to allow a one-to-one comparison between the true parameter values and the identified parameter distributions.

---

### Example problems

There are four examples:

1) [Linear Elasticity](1_linear_elasticity.ipynb)
2) [Linear Elasticity-Perfect Plasticity](2_linear_elasticity_perfect_plasticity.ipynb)
3) [Linear Elasticity-Linear Hardening](3_linear_elasticity_linear_hardening.ipynb)
4) Linear Elasticity-Nonlinear Hardening

There are two further examples that explain more advanced concepts: 

1) Noise in both stress and strain
2) Model uncertainty

---

### Core concepts

There are a number of notebooks to explain the core concepts required to understand the example problems.

1) Bayesian inference
2) Markov Chain Monte Carlo (MCMC)
    - Standard Metropolis-Hastings algorithm
    - The adaptive Metropolis-Hastings algorithm
3) Posterior Predictive Distribution (PPD)

---

### Contact

If you spot any mistakes then please raise an issue or if you would prefer you can contact me using the following email address:

mhobbs@turing.ac.uk 


