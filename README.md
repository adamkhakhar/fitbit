# Analysis of FitBit Data for Causal Inference and Feature Importance
## Data
- 2 months of minute level FitBit tracking data for 30 participants.
	- Includes steps walked, intense exercise, calories consumed, sleep, weight, etc.
- Target: Intense exercise minutes.

## Feature Importance
- Recursive Feature Elimination on regularized linear regression
- Shapley Values on linear regression
- Random Forest via mean decrease in impurity

## Causal Inference
- Potential outcomes framework, estimating the Average Treatment Effect
