# Bayesian Analysis on Household Dietary Diversity (Tanzania)

## Summary
This project studies socio-economic determinants of household dietary diversity in Tanzania using Bayesian count models. I compare Poisson vs. Negative Binomial models and evaluate multiple prior specifications, selecting a Poisson model with a sparsity-inducing (Lasso) prior based on predictive criteria.

## Contents
- `dietary_diversity_bayes.Rmd` — reproducible analysis code
- `dietary_diversity_bayes.pdf` — full report with figures, diagnostics, and interpretation

## Methods (high level)
- Bayesian Poisson and Negative Binomial regression
- Model comparison via LOO/WAIC-style predictive evaluation
- Prior sensitivity comparison (Normal/Cauchy/non-informative/Lasso)
- Feature selection via sparsity-inducing prior

## How to run
Open `dietary_diversity_bayes.Rmd` in RStudio and knit to PDF (or run chunks interactively).
