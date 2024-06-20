# Summary of 114_RandomForest_Stacked

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.7
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

44.3 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.404033 | nan         |
| auc       | 0.885241 | nan         |
| f1        | 0.874408 |   0.489138  |
| accuracy  | 0.837021 |   0.508569  |
| precision | 0.965616 |   0.967509  |
| recall    | 1        |   0.0121695 |
| mcc       | 0.645291 |   0.508569  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.404033 |  nan        |
| auc       | 0.885241 |  nan        |
| f1        | 0.873601 |    0.508569 |
| accuracy  | 0.837021 |    0.508569 |
| precision | 0.858106 |    0.508569 |
| recall    | 0.889666 |    0.508569 |
| mcc       | 0.645291 |    0.508569 |


## Confusion matrix (at threshold=0.508569)
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
