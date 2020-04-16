

# Autotuning Methods

This page  contains lists of concepts,  methods and key ideas  for autotuning in
the context of  this project. This is  a living page, where  links for resources
and new items are added as the  project progresses.  The purpose of this page is
to provide an easily accessible reference for the concepts and tools involved in
autotuning.


## Overview

The list below summarizes available methods for autotuning, and is based on [this
tree](res/tree/tree.pdf):

1.  Search Heuristics
    -   Does not estimate a surrogate function
    -   There is no model, underlying hypotheses guide exploration
    -   Examples: Simulated Annealing, Gradient Descent,
        Genetic Algorithms
    -   Introductory book: [Stochastic Local Search: Foundations & Applications](https://www.amazon.fr/Stochastic-Local-Search-Foundations-Applications/dp/1558608729)
        -   [Free chapters](https://www.cs.ubc.ca/~hoos/SLS-Internal/)
2.  Statistical Learning
    -   Estimates a surrogate function
    -   Introductory book: [An Introduction to Statistical Learning](https://link.springer.com/book/10.1007/978-1-4614-7138-7) (**free during COVID-19**)
        -   [Online course by the authors](https://www.edx.org/course/statistical-learning) (**free during COVID-19**)
    -   More in depth: [The Elements of Statistical Learning](https://link.springer.com/book/10.1007/978-0-387-84858-7) (**free during COVID-19**)
    -   Parametric Learning
        -   Higher biases, simpler models, focus on finding relationships between
            parameters and response
        -   Examples: Optimal Design, Linear Model, Bandit Algorithms
        -   DoE Book: [Design and Analysis of Experiments](https://link.springer.com/book/10.1007/978-3-319-52250-0) (**free during COVID-19**)
        -   DoE Book: [Statistics for Experimenters](https://www.wiley.com/en-us/Statistics+for+Experimenters%3A+Design%2C+Innovation%2C+and+Discovery%2C+2nd+Edition-p-9780471718130)
        -   Classic DoE Book: [The Art of Computer Systems Performance Analysis](https://www.cse.wustl.edu/~jain/books/perfbook.htm)
    -   Nonparametric Learning
        -   Lower biases, more complex models, focus on function minimization
        -   Examples: Gaussian Process Regression, Decision Trees, Neural Networks
        -   GPR Book: [Gaussian Processes for Machine Learning](http://www.gaussianprocess.org/gpml/chapters/RW.pdf) (**free**)


## Tools


### Statistical Learning

-   The [R Project](https://www.r-project.org/): standard library with powerful statistical functions
-   The [Julia language](https://julialang.org/)

1.  R packages

    -   [tidyverse](https://www.tidyverse.org/packages/): Data plotting and manipulation
    -   [randtoolbox](https://cran.r-project.org/web/packages/randtoolbox/index.html): Quasi random, low discrepancy sampling
    -   [DiceKriging](https://cran.r-project.org/web/packages/DiceKriging/DiceKriging.pdf): Gaussian Process Regression
    -   [DiceOptim](https://cran.r-project.org/web/packages/DiceOptim/DiceOptim.pdf): Efficient Global Optimization
    -   [DoE.base](https://cran.r-project.org/web/packages/DoE.base/DoE.base.pdf): Design of Experiments
    -   [AlgDesign](https://cran.r-project.org/web/packages/AlgDesign/index.html): Optimal Design Construction
    -   [quantreg](https://cran.r-project.org/web/packages/quantreg/quantreg.pdf): Quantile Regression
