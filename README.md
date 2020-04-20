
<!-- README.md is generated from README.Rmd. Please edit that file -->
bnma (Bayesian network meta analysis)
=====================================

The package is now publicly available in CRAN. <https://CRAN.R-project.org/package=bnma>. Package is quite similar and has been inspired greatly by the gemtc packge (<https://cran.r-project.org/web/packages/gemtc/index.html>). Some features that bnma offers:

-   gemtc offers binomial, normal, and poisson outcomes; bnma has binomial, normal, and multinomial outcomes.
-   bnma adds modelling baseline risk (<https://onlinelibrary.wiley.com/doi/abs/10.1002/sim.5539>)
-   bnma automatically checks for convergence using gelman-rubin diagnostics before sampling full iteration amount
-   bnma generates reasonable initial values if left unspecified (dispersed initial values)
-   bnma has added new summary plots: rank plots, forest plot, etc

Thank you,
Michael Seo
