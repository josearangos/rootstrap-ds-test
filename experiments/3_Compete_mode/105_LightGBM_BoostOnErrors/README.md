# Summary of 105_LightGBM_BoostOnErrors

[<< Go back](../README.md)


## LightGBM
- **n_jobs**: -1
- **objective**: binary
- **num_leaves**: 63
- **learning_rate**: 0.2
- **feature_fraction**: 0.8
- **bagging_fraction**: 1.0
- **min_data_in_leaf**: 10
- **metric**: custom
- **custom_eval_metric_name**: f1
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

36.1 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.455105 | nan          |
| auc       | 0.87407  | nan          |
| f1        | 0.861364 |   0.488892   |
| accuracy  | 0.821243 |   0.488892   |
| precision | 0.989899 |   0.998477   |
| recall    | 1        |   0.00121616 |
| mcc       | 0.610826 |   0.488892   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.455105 |  nan        |
| auc       | 0.87407  |  nan        |
| f1        | 0.861364 |    0.488892 |
| accuracy  | 0.821243 |    0.488892 |
| precision | 0.846086 |    0.488892 |
| recall    | 0.877204 |    0.488892 |
| mcc       | 0.610826 |    0.488892 |


## Confusion matrix (at threshold=0.488892)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             1382 |              525 |
| Labeled as 1 |              404 |             2886 |

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
