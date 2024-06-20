# Summary of 125_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: entropy
- **max_depth**: 3
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

19.4 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.542846 |  nan        |
| auc       | 0.770295 |  nan        |
| f1        | 0.801884 |    0.37892  |
| accuracy  | 0.734077 |    0.487552 |
| precision | 0.94824  |    0.951282 |
| recall    | 1        |    0.169529 |
| mcc       | 0.418883 |    0.59375  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.542846 |  nan        |
| auc       | 0.770295 |  nan        |
| f1        | 0.800404 |    0.487552 |
| accuracy  | 0.734077 |    0.487552 |
| precision | 0.762521 |    0.487552 |
| recall    | 0.842249 |    0.487552 |
| mcc       | 0.40958  |    0.487552 |


## Confusion matrix (at threshold=0.487552)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             1044 |              863 |
| Labeled as 1 |              519 |             2771 |

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
