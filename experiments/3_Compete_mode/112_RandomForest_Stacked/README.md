# Summary of 112_RandomForest_Stacked

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.8
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

44.6 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.408711 | nan         |
| auc       | 0.882232 | nan         |
| f1        | 0.873815 |   0.489949  |
| accuracy  | 0.836059 |   0.489949  |
| precision | 0.966514 |   0.959684  |
| recall    | 1        |   0.0219382 |
| mcc       | 0.64277  |   0.510226  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.408711 |  nan        |
| auc       | 0.882232 |  nan        |
| f1        | 0.873815 |    0.489949 |
| accuracy  | 0.836059 |    0.489949 |
| precision | 0.852109 |    0.489949 |
| recall    | 0.896657 |    0.489949 |
| mcc       | 0.642005 |    0.489949 |


## Confusion matrix (at threshold=0.489949)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             1395 |              512 |
| Labeled as 1 |              340 |             2950 |

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
