# Stack-Regression-for-House-Price-Prediction
A stacked regression model for predicting the house price.

A brief description of steps in the code is below:
1. Perform multiple linear analysis, visual analysis, and correlation analysis on the independent variables of the house through pandas and matplotlib.
2. Clean invalid data and perform feature engineering through sklearn.
3. Use Lasso regression, ENet regression, Kernel Ridge regression, Gradient Boost, XGB and LightGBM to model and compare the accuracy.
4. Integrate the four models of ENet, GBoost, KRR and Lasso to build a mean regression Stacked Regressor.
5. Use Stacked, XGB and LightGBM to predict respectively, weight their prediction results, and establish Ensemble prediction.
6. Predict the test data by Ensemble regression.

The dataset is from kaggle, with 79 explantory variabels describing almost every aspect of the residential homes in Ames, Iowa.

The link is here,
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
