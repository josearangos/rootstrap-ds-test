# Summary of 33_CatBoost_Stacked

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.2
- **depth**: 8
- **rsm**: 1.0
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

27.6 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.408547 | nan          |
| auc       | 0.882863 | nan          |
| f1        | 0.873601 |   0.508201   |
| accuracy  | 0.837021 |   0.508201   |
| precision | 0.958807 |   0.950122   |
| recall    | 1        |   0.00138516 |
| mcc       | 0.645291 |   0.508201   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.408547 |  nan        |
| auc       | 0.882863 |  nan        |
| f1        | 0.873601 |    0.508201 |
| accuracy  | 0.837021 |    0.508201 |
| precision | 0.858106 |    0.508201 |
| recall    | 0.889666 |    0.508201 |
| mcc       | 0.645291 |    0.508201 |


## Confusion matrix (at threshold=0.508201)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             1423 |              484 |
| Labeled as 1 |              363 |             2927 |

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
