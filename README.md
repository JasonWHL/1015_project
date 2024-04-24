# SC1015 Mini Project: Measuring Academic Performances on Household Factors

## About 

This project analyses students' academic performances using the [Student Performance API](https://archive.ics.uci.edu/dataset/320/student+performance).

## Contributors

- Basadzishvili Archil - GBM
- Char Bao Jie - Data Extraction, Data Resampling, Logistic Regression
- Jason Liu - Visualisation

## Problem Definition

- Can we predict whether a student will perform well academically (score above 75%) based on household factors?
- Which model would be best to predict it?

## Models Used

1. Logistic Regression
2. Gradient Boosting Machines (GBM)

## Conclusion

- Key determinants of influence include whether at least one parent has received formal education, the extent of the educational disparity between parents, whether the parents reside together, and the father's employment status
- Logistic Regression yielded unsatisfactory results when applied to variables with nonlinear correlations.
- Gradient Boosting Machine (GBM) did not demonstrate effective performance due to the limited size of our dataset.
- There is sufficient accuracy to predict whether a student will perform well academically.

## What did we learn from this project?

- Addressing the imbalance in datasets by employing resampling techniques through the imbalanced-learn (imblearn) package.
- Logistic Regression from sklearn
- Gradient Boosting Machines (GBM), XGBoost, LightGBM, CatBoost
- Collaboration on GitHub
- Application and utility of Precision, Recall, and F1 Score.

## References

- https://www.kaggle.com/code/rafjaa/resampling-strategies-for-imbalanced-datasets
- https://www.tensorflow.org/tutorials/structured_data/imbalanced_data
- https://stackoverflow.com/questions/64800003/seaborn-confusion-matrix-heatmap-2-color-schemes-correct-diagonal-vs-wrong-re
- https://www.geeksforgeeks.org/how-to-annotate-bars-in-barplot-with-matplotlib-in-python/
- https://towardsdatascience.com/building-a-logistic-regression-in-python-step-by-step-becd4d56c9c8
- https://www.datacamp.com/tutorial/understanding-logistic-regression-python
- https://machinelearningmastery.com/gradient-boosting-with-scikit-learn-xgboost-lightgbm-and-catboost/
- https://medium.com/@ilyurek/gradient-boosting-machines-gbm-with-python-example-b65421d10f2a
