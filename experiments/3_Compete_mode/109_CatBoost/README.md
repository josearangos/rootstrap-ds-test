# Summary of 109_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.1
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

21.0 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.428516 | nan          |
| auc       | 0.874224 | nan          |
| f1        | 0.861374 |   0.50129    |
| accuracy  | 0.819896 |   0.50129    |
| precision | 0.986395 |   0.992251   |
| recall    | 1        |   0.00408568 |
| mcc       | 0.606449 |   0.50129    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.428516 |   nan       |
| auc       | 0.874224 |   nan       |
| f1        | 0.861374 |     0.50129 |
| accuracy  | 0.819896 |     0.50129 |
| precision | 0.839977 |     0.50129 |
| recall    | 0.883891 |     0.50129 |
| mcc       | 0.606449 |     0.50129 |


## Confusion matrix (at threshold=0.50129)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             1353 |              554 |
| Labeled as 1 |              382 |             2908 |

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
