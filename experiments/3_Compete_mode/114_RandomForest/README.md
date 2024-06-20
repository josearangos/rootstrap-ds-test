# Summary of 114_RandomForest

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

18.7 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.480438 | nan         |
| auc       | 0.835796 | nan         |
| f1        | 0.832868 |   0.500479  |
| accuracy  | 0.78122  |   0.500479  |
| precision | 0.97992  |   0.966678  |
| recall    | 1        |   0.0610143 |
| mcc       | 0.51956  |   0.500479  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.480438 |  nan        |
| auc       | 0.835796 |  nan        |
| f1        | 0.832868 |    0.500479 |
| accuracy  | 0.78122  |    0.500479 |
| precision | 0.806433 |    0.500479 |
| recall    | 0.861094 |    0.500479 |
| mcc       | 0.51956  |    0.500479 |


## Confusion matrix (at threshold=0.500479)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             1227 |              680 |
| Labeled as 1 |              457 |             2833 |

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
