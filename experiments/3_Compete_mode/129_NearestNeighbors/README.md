# Summary of 129_NearestNeighbors

[<< Go back](../README.md)


## k-Nearest Neighbors (Nearest Neighbors)
- **n_jobs**: -1
- **n_neighbors**: 5
- **weights**: distance
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

14.1 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 1.01436  |  nan        |
| auc       | 0.75557  |  nan        |
| f1        | 0.795205 |    0.197233 |
| accuracy  | 0.709255 |    0.464077 |
| precision | 0.896624 |    0.921094 |
| recall    | 0.989666 |    0        |
| mcc       | 0.366078 |    0.613391 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 1.01436  |  nan        |
| auc       | 0.75557  |  nan        |
| f1        | 0.781173 |    0.464077 |
| accuracy  | 0.709255 |    0.464077 |
| precision | 0.746058 |    0.464077 |
| recall    | 0.819757 |    0.464077 |
| mcc       | 0.354414 |    0.464077 |


## Confusion matrix (at threshold=0.464077)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |              989 |              918 |
| Labeled as 1 |              593 |             2697 |

## Learning curves
![Learning curves](learning_curves.png)
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
