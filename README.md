# Credit Card Fraud Detection
## Overview
This project explores the Credit Card Fraud Detection Dataset provided by Machine Learning Group at Université Libre de Bruxelles. The dataset contains 284,807 transactions out of which 492 transactions are fraud. The objective is to fit the dataset into machine learning models to predict precisely while dealing with higher class imbalance.
## Dataset
**Link:** http://www.kaggle.com/mlg-ulb/creditcardfraud/data
## Dependencies
Install the following dependencies using pip
* numpy
* pandas
* matplotlib
* seaborn
## Evaluation Metric
In cases of class imbalance, AUC of ROC curve is a preferred evaluation metric over accuracy.
## Result
We implemented three models - Logistic Regression, Random Forest and XGBoost. **XGBoost** has the highest AUC score.