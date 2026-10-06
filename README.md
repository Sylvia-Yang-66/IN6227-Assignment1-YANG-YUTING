# IN6227 Data Mining – Assignment 1 (Variant 1)

Comparison of **Logistic Regression** and **Random Forest** on the provided imbalanced binary classification dataset.

## Files

| File                                       | Content                                                                                                             |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------- |
| `IN6227_A1_part1_EDA.ipynb`                | Data exploration: types, imbalance, missing values, outliers, correlation, mutual information                       |
| `IN6227_A1_part2_Cleaning.ipynb`           | Cleaning: drop rows without label, merge rare levels, keep `Unknown`; writes `train_clean.csv` and `test_clean.csv` |
| `IN6227_A1_part3_FeatureEngineering.ipynb` | Preprocessing pipelines and the cross-validated feature-selection experiment for LR                                 |
| `IN6227_A1_part4_Training.ipynb`           | Grid search with 5-fold stratified CV, stopping criteria; saves `lr_model.joblib` and `rf_model.joblib`             |
| `IN6227_A1_part5_Evaluation.ipynb`         | Final test-set evaluation, bootstrap comparison, ROC curves, feature importance, report figures                     |
| `train.csv`, `test.csv`                    | Provided dataset                                                                                                    |

