# Summary of 87_RandomForest_Stacked

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.6
- **min_samples_split**: 30
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

37.2 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.405586 |  nan        |
| auc       | 0.883773 |  nan        |
| f1        | 0.876586 |    0.498637 |
| accuracy  | 0.84087  |    0.498637 |
| precision | 0.979592 |    0.971386 |
| recall    | 1        |    0.013604 |
| mcc       | 0.653698 |    0.498637 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.405586 |  nan        |
| auc       | 0.883773 |  nan        |
| f1        | 0.876586 |    0.498637 |
| accuracy  | 0.84087  |    0.498637 |
| precision | 0.861038 |    0.498637 |
| recall    | 0.892705 |    0.498637 |
| mcc       | 0.653698 |    0.498637 |


## Confusion matrix (at threshold=0.498637)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             1433 |              474 |
| Labeled as 1 |              353 |             2937 |

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
