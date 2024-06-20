# Summary of 70_NearestNeighbors

[<< Go back](../README.md)


## k-Nearest Neighbors (Nearest Neighbors)
- **n_jobs**: -1
- **n_neighbors**: 3
- **weights**: uniform
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

7.1 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 1.81431  |  nan        |
| auc       | 0.706378 |  nan        |
| f1        | 0.785696 |    0        |
| accuracy  | 0.684048 |    0.333333 |
| precision | 0.830964 |    0.666667 |
| recall    | 0.955015 |    0        |
| mcc       | 0.311584 |    0.666667 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 1.81431  |  nan        |
| auc       | 0.706378 |  nan        |
| f1        | 0.75959  |    0.333333 |
| accuracy  | 0.684048 |    0.333333 |
| precision | 0.732768 |    0.333333 |
| recall    | 0.78845  |    0.333333 |
| mcc       | 0.302386 |    0.333333 |


## Confusion matrix (at threshold=0.333333)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |              961 |              946 |
| Labeled as 1 |              696 |             2594 |

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
