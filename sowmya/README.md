## Resources Used

| Resource/Library Name | Source |
|---------------|:------:|
| SMOTE - Synthetic Minority Oversampling Technique | [Library](https://imbalanced-learn.org/stable/), [Reference](https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/) |
| MissForest imputation | [Library](https://github.com/epsilon-machine/missingpy), [Reference 1](https://www.betterdatascience.com/python-missforest/), [Reference 2](https://towardsdatascience.com/missforest-the-best-missing-data-imputation-algorithm-4d01182aed3) |
| Stacking Classifier | [Reference](http://rasbt.github.io/mlxtend/user_guide/classifier/StackingClassifier/) |

## To-Do List
- Parameter tuning for each model
    - [ ] AdaBoostClassifier
    - [ ] MLP
    - [ ] Decision Trees
    - [ ] Random Forest
    - [X] SVM
- [ ] Do a 5-fold CV and check Output
- [ ] [ROC curves](https://scikit-learn.org/stable/auto_examples/model_selection/plot_roc.html)
- [X] [VIF](https://www.statsmodels.org/devel/generated/statsmodels.stats.outliers_influence.variance_inflation_factor.html)

## Changes
- 30/12/20: Changed the imputation of the test to be independent of the `ID_Test` value. The files are saved as `train_rf_imputed.csv` and `test_rf_imputed.csv`.
- 30/12/20: Removed rows that are highly correlated and the results are stored in `train_final.csv` and `test_final.csv`.