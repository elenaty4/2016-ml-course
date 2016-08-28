Week 2 Homework
--
Due Tuesday, September 6 (due to labor day).
While you'll get an extra day for this assignment, I don't recommend taking it, because you will have both (1) a project due and (2) another assignment due during that week.

This assignment is to be done in LaTeX.

* Exercise 10.1
 * (b) Suppose that instead of binary classes (> 60 or < 60), your data consists of a discrete set of ages, *A*, in [0,100] and probabilities *p* ∈ [0,1] for each age, respectively. Write an equation (with variables, not numbers) for the probability of people over age 60.  
* Exercise 10.5
* The Dirichlet distribution (Chapter 8) is a distribution over multinomial distributions.  In a typical probability distribution, you are sampling some value.  In a Dirichlet distribution, you are sampling a distribution, Q ~ Dir(**α**).  Here, α is a vector of parameters that determines how likely the distributions are to be sampled, akin to skewness in the two-dimensional case.  An α of [1,1,1] in the **R**<sup>3</sup> cae is uniform: all distributions are equally likely.   The Dirichlet distribution models the randomness within a set of distributions, which can be visualized as a *k-1*-dimensional simplex. (A simplex is a multi-dimensional shape in **R**<sup>n</sup>).  That is to say, the Dirichlet is a distribution over a *family* of distributions with some random perturbation, parameterized by α to make either enforce sparsity or clustering of the probability mass.  

Why might we want to sample a distribution itself?  Briefly explain your intuition.