# U.S. Presidential Election Voting Predictors (Applied ML)

## Summary
This project analyzes demographic and socio-economic predictors of voting outcomes using supervised machine learning. The goal is to compare a range of modeling approaches and assess whether ensemble methods can improve predictive performance in a real-world, tabular setting.

## Data
- Public U.S. county-level election outcomes and demographic covariates (compiled from publicly available sources).
- Target: voting outcome / vote-share–based label derived from election results.

## Methods
- Feature preprocessing and engineering (including handling missingness and scaling where appropriate)
- Models evaluated: Random Forest, KNN, SVM, XGBoost, LightGBM
- Ensemble learning via model stacking to improve robustness and reduce overfitting
- Evaluation using cross-validation and standard predictive metrics

## Results (high level)
Stacking improved overall performance relative to individual base models, highlighting the practical value of combining complementary learners in noisy, high-dimensional demographic data.

## Files
- `presidential_election_report.pdf` — full report (methods, results, discussion; code included in appendix)

## Notes on reproducibility
Code is included in the report appendix. If needed, I can also export the appendix into a standalone script (`modeling_pipeline.R`) and replace any local file paths with relative paths for easier reproduction.
