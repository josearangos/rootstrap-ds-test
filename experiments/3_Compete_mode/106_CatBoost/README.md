# Summary of 106_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.2
- **depth**: 9
- **rsm**: 0.9
- **loss_function**: Logloss
- **eval_metric**: F1
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

20.1 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.435767 | nan           |
| auc       | 0.87518  | nan           |
| f1        | 0.863155 |   0.505767    |
| accuracy  | 0.823552 |   0.505767    |
| precision | 0.972789 |   0.997098    |
| recall    | 1        |   0.000797629 |
| mcc       | 0.61587  |   0.505767    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.435767 |  nan        |
| auc       | 0.87518  |  nan        |
| f1        | 0.863155 |    0.505767 |
| accuracy  | 0.823552 |    0.505767 |
| precision | 0.847845 |    0.505767 |
| recall    | 0.879027 |    0.505767 |
| mcc       | 0.61587  |    0.505767 |


## Confusion matrix (at threshold=0.505767)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             1388 |              519 |
| Labeled as 1 |              398 |             2892 |

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
