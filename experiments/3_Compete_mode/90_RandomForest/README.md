# Summary of 90_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.5
- **min_samples_split**: 50
- **max_depth**: 6
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

14.9 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.493629 |  nan        |
| auc       | 0.826737 |  nan        |
| f1        | 0.825503 |    0.497754 |
| accuracy  | 0.769867 |    0.497754 |
| precision | 0.984848 |    0.961486 |
| recall    | 1        |    0.077303 |
| mcc       | 0.492813 |    0.603164 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.493629 |  nan        |
| auc       | 0.826737 |  nan        |
| f1        | 0.825503 |    0.497754 |
| accuracy  | 0.769867 |    0.497754 |
| precision | 0.793771 |    0.497754 |
| recall    | 0.859878 |    0.497754 |
| mcc       | 0.492615 |    0.497754 |


## Confusion matrix (at threshold=0.497754)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             1172 |              735 |
| Labeled as 1 |              461 |             2829 |

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
