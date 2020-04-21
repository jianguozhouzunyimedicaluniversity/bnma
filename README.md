
<!-- README.md is generated from README.Rmd. Please edit that file -->
bnma (Bayesian network meta analysis)
=====================================

Package is quite similar and has been inspired greatly by a popular Bayesian NMA package gemtc. Some additional features of bnma include:

-   bnma has binomial, normal, and multinomial outcomes.
-   bnma adds modelling baseline risk
-   bnma automatically checks for convergence using gelman-rubin diagnostics before sampling full iteration amount
-   bnma generates reasonable initial values if left unspecified (dispersed initial values)
-   bnma defaults to reporting odds ratio as the summary measure for binomial outcome; bnma adds an option to report instead relative risk and risk difference using external placebo event rate
-   bnma adds new summary plots: rank plots, forest plot, etc

Please see the vignette for detailed examples of using this package.
