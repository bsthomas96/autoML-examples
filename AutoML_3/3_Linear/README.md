# Summary of 3_Linear

[<< Go back](../README.md)


## Linear Regression (Linear)
- **n_jobs**: -1
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True

## Optimized metric
rmse

## Training time

7.3 seconds

### Metric details:
| Metric   |     Score |
|:---------|----------:|
| MAE      |  3.12708  |
| MSE      | 22.0988   |
| RMSE     |  4.70093  |
| R2       |  0.685169 |
| MAPE     |  0.155219 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature   |   Learner_1 |
|:----------|------------:|
| RAD       |   0.311601  |
| RM        |   0.302121  |
| CHAS      |   0.17426   |
| B         |   0.116811  |
| ZN        |   0.110596  |
| INDUS     |   0.0167694 |
| intercept |  -0.0129081 |
| AGE       |  -0.0271939 |
| CRIM      |  -0.107225  |
| NOX       |  -0.20729   |
| PTRATIO   |  -0.227906  |
| TAX       |  -0.266835  |
| DIS       |  -0.344102  |
| LSTAT     |  -0.380662  |


## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## True vs Predicted

![True vs Predicted](true_vs_predicted.png)


## Predicted vs Residuals

![Predicted vs Residuals](predicted_vs_residuals.png)



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots

### Dependence (Fold 1)
![SHAP Dependence from Fold 1](learner_fold_0_shap_dependence.png)

## SHAP Decision plots

### Top-10 Worst decisions (Fold 1)
![SHAP worst decisions from fold 1](learner_fold_0_shap_worst_decisions.png)
### Top-10 Best decisions (Fold 1)
![SHAP best decisions from fold 1](learner_fold_0_shap_best_decisions.png)

[<< Go back](../README.md)
