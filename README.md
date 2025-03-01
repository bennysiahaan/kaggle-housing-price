## About
This repository is intended to implement a machine learning model that makes predictions to [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) competition on Kaggle.

## How it works
The model uses standard scikit-learn pipeline to parallelize/propagate transformations on the data.
Some transformations include:
- Dropping irrelevant features
- Impute for numeric features
- One-hot encode for categorical features
- Random forest regressor

This pipeline is done with **GridSearchCV** in order to find the best estimator given multiple hyperparameters.

## Result
The result is stored in [predictions.csv](predictions.csv).