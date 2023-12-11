# Summary of 75_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: squared_error
- **max_features**: 0.9
- **min_samples_split**: 30
- **max_depth**: 7
- **eval_metric_name**: rmse
- **explain_level**: 2

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **k_folds**: 10

## Optimized metric
rmse

## Training time

244.9 seconds

### Metric details:
| Metric   |     Score |
|:---------|----------:|
| MAE      | 0.353371  |
| MSE      | 0.198327  |
| RMSE     | 0.445339  |
| R2       | 0.0329607 |
| MAPE     | 0.250434  |



## Learning curves
![Learning curves](learning_curves.png)

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
### Dependence (Fold 2)
![SHAP Dependence from Fold 2](learner_fold_1_shap_dependence.png)
### Dependence (Fold 3)
![SHAP Dependence from Fold 3](learner_fold_2_shap_dependence.png)
### Dependence (Fold 4)
![SHAP Dependence from Fold 4](learner_fold_3_shap_dependence.png)
### Dependence (Fold 5)
![SHAP Dependence from Fold 5](learner_fold_4_shap_dependence.png)
### Dependence (Fold 6)
![SHAP Dependence from Fold 6](learner_fold_5_shap_dependence.png)
### Dependence (Fold 7)
![SHAP Dependence from Fold 7](learner_fold_6_shap_dependence.png)
### Dependence (Fold 8)
![SHAP Dependence from Fold 8](learner_fold_7_shap_dependence.png)
### Dependence (Fold 9)
![SHAP Dependence from Fold 9](learner_fold_8_shap_dependence.png)
### Dependence (Fold 10)
![SHAP Dependence from Fold 10](learner_fold_9_shap_dependence.png)

## SHAP Decision plots

### Top-10 Worst decisions (Fold 1)
![SHAP worst decisions from fold 1](learner_fold_0_shap_worst_decisions.png)
### Top-10 Worst decisions (Fold 2)
![SHAP worst decisions from fold 2](learner_fold_1_shap_worst_decisions.png)
### Top-10 Worst decisions (Fold 3)
![SHAP worst decisions from fold 3](learner_fold_2_shap_worst_decisions.png)
### Top-10 Worst decisions (Fold 4)
![SHAP worst decisions from fold 4](learner_fold_3_shap_worst_decisions.png)
### Top-10 Worst decisions (Fold 5)
![SHAP worst decisions from fold 5](learner_fold_4_shap_worst_decisions.png)
### Top-10 Worst decisions (Fold 6)
![SHAP worst decisions from fold 6](learner_fold_5_shap_worst_decisions.png)
### Top-10 Worst decisions (Fold 7)
![SHAP worst decisions from fold 7](learner_fold_6_shap_worst_decisions.png)
### Top-10 Worst decisions (Fold 8)
![SHAP worst decisions from fold 8](learner_fold_7_shap_worst_decisions.png)
### Top-10 Worst decisions (Fold 9)
![SHAP worst decisions from fold 9](learner_fold_8_shap_worst_decisions.png)
### Top-10 Worst decisions (Fold 10)
![SHAP worst decisions from fold 10](learner_fold_9_shap_worst_decisions.png)
### Top-10 Best decisions (Fold 1)
![SHAP best decisions from fold 1](learner_fold_0_shap_best_decisions.png)
### Top-10 Best decisions (Fold 2)
![SHAP best decisions from fold 2](learner_fold_1_shap_best_decisions.png)
### Top-10 Best decisions (Fold 3)
![SHAP best decisions from fold 3](learner_fold_2_shap_best_decisions.png)
### Top-10 Best decisions (Fold 4)
![SHAP best decisions from fold 4](learner_fold_3_shap_best_decisions.png)
### Top-10 Best decisions (Fold 5)
![SHAP best decisions from fold 5](learner_fold_4_shap_best_decisions.png)
### Top-10 Best decisions (Fold 6)
![SHAP best decisions from fold 6](learner_fold_5_shap_best_decisions.png)
### Top-10 Best decisions (Fold 7)
![SHAP best decisions from fold 7](learner_fold_6_shap_best_decisions.png)
### Top-10 Best decisions (Fold 8)
![SHAP best decisions from fold 8](learner_fold_7_shap_best_decisions.png)
### Top-10 Best decisions (Fold 9)
![SHAP best decisions from fold 9](learner_fold_8_shap_best_decisions.png)
### Top-10 Best decisions (Fold 10)
![SHAP best decisions from fold 10](learner_fold_9_shap_best_decisions.png)

[<< Go back](../README.md)
