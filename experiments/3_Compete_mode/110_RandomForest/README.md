# Summary of 110_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.6
- **min_samples_split**: 20
- **max_depth**: 7
- **eval_metric_name**: f1
- **explain_level**: 1

## Validation
 - **validation_type**: kfold
 - **k_folds**: 10
 - **shuffle**: True
 - **stratify**: True
 - **random_seed**: 12

## Optimized metric
f1

## Training time

17.3 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.47836  | nan         |
| auc       | 0.837534 | nan         |
| f1        | 0.832868 |   0.494034  |
| accuracy  | 0.782182 |   0.503067  |
| precision | 0.984848 |   0.971811  |
| recall    | 1        |   0.0326396 |
| mcc       | 0.523485 |   0.503067  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.47836  |  nan        |
| auc       | 0.837534 |  nan        |
| f1        | 0.832346 |    0.503067 |
| accuracy  | 0.782182 |    0.503067 |
| precision | 0.81167  |    0.503067 |
| recall    | 0.854103 |    0.503067 |
| mcc       | 0.523485 |    0.503067 |


## Confusion matrix (at threshold=0.503067)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             1255 |              652 |
| Labeled as 1 |              480 |             2810 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
