# Summary of 110_RandomForest_Stacked

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

36.3 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.402735 |  nan        |
| auc       | 0.885999 |  nan        |
| f1        | 0.874704 |    0.490913 |
| accuracy  | 0.837214 |    0.490913 |
| precision | 0.975207 |    0.971269 |
| recall    | 1        |    0.013351 |
| mcc       | 0.644545 |    0.490913 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.402735 |  nan        |
| auc       | 0.885999 |  nan        |
| f1        | 0.874704 |    0.490913 |
| accuracy  | 0.837214 |    0.490913 |
| precision | 0.852975 |    0.490913 |
| recall    | 0.897568 |    0.490913 |
| mcc       | 0.644545 |    0.490913 |


## Confusion matrix (at threshold=0.490913)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             1398 |              509 |
| Labeled as 1 |              337 |             2953 |

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
