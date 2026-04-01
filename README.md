# Premature Convergence Detection

A computational framework for detecting premature accountability convergence 
in regulatory investigations.

## Research Question
Can we detect when a reasoning process closes too early on a single 
explanation, despite available alternatives?

## Key Findings
- Commitment level is the strongest predictor of premature convergence (ablation ΔF1 = 0.060)
- All three classifiers achieve AUC > 0.97 (LR: 0.973, RF: 0.975, SVM: 0.974)
- Synthetic dataset (n=500) closely approximates FDA corpus diversity (1.584 vs 1.601)
- 12 of 50 FDA Warning Letter cases exceed convergence risk threshold

## Methods
- Entropy-based explanatory diversity score
- Probabilistic labeling with Gaussian noise
- Logistic Regression / Random Forest / SVM comparison
- 5-fold cross-validation
- SHAP analysis for interpretability
- FDA Warning Letter corpus validation (N=50, 2016–2025)

## Dataset
- Synthetic reasoning logs (n=500, balanced)
- FDA Warning Letters corpus (N=50, 21 CFR 210/211)

## Reference
Kim, S. (2026). Premature Accountability Convergence. SSRN Preprint.
