
<!-- README.md is generated from README.Rmd. Please edit that file -->
bnma (Bayesian network meta analysis)
=====================================

Package is quite similar and has been inspired greatly by another popular Bayesian NMA package, gemtc package (<https://cran.r-project.org/web/packages/gemtc/index.html>). Some features of bnma include:

-   bnma has binomial, normal, and multinomial outcomes.
-   bnma adds modelling baseline risk (<https://onlinelibrary.wiley.com/doi/abs/10.1002/sim.5539>)
-   bnma automatically checks for convergence using gelman-rubin diagnostics before sampling full iteration amount
-   bnma generates reasonable initial values if left unspecified (dispersed initial values)
-   bnma has added new summary plots: rank plots, forest plot, etc

Please see the vignette for detailed examples of using this package.
