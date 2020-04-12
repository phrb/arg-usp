

# Concepts for Autotuning

This  is a  list  of concepts  useful  for  autotuning in  the  context of  this
project. This is a living list, with  links for resources and new items added as
needed. The  purpose of this list  is to provide an  easily accessible reference
for the concepts involved in autotuning.

The list below summarizes available methods for autotuning, and is based on [this
tree](res/tree/tree.pdf):

1.  Search Heuristics
    -   Does not estimate surrogate function
    -   Examples: Simulated Annealing, Gradient Descent,
        Genetic Algorithms
2.  Statistical Learning
    -   Estimates surrogate function
    -   Parametric Learning
        -   Higher biases, simpler models, focus on finding relationships between
            parameters and response
        -   Examples: Optimal Design, Linear Model, Bandit Algorithms
    -   Nonparametric Learning
        -   Lower biases, more complex models, focus on function minimization
        -   Examples: Gaussian Process Regression, Decision Trees, Neural Networks

List of useful tools and concepts:

1.  Statistics: Modeling and Inference
    -   Linear model
    -   Bayesian model
    -   Regression
    -   Analysis of Variance (ANOVA)
    -   Akaike Information Criterion (AIC)
    -   Bayesian Information Criterion (BIC)
2.  Experimental Design
    -   Screening
        -   An example on [ExperimentalDesign](https://github.com/phrb/ExperimentalDesign.jl/blob/master/examples/Screening%20with%20Plackett-Burman%20Designs.ipynb)
    -   Fractional Factorial Designs
    -   Optimal Design Theory
3.  Sampling
    -   Uniform Random Sampling
    -   Low-discrepancy Sampling
