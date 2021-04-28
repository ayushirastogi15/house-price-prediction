# House Prices Prediction using ML algorithms

This repository contains the basics of predicting house prices using different machine learning algorithms like Linear Regression, Ridge Regression, Lasso Regression, Random Forest Regressor, Gradient Boosting Regressor using Randomized Search CV and Grid Search CV methods to cross validate the dataset we've. 
This is the basic Kaggle competition of Getting started with Advanced Regression Techniques. It has a number of features to consider for the prediction.

You can find out the code using the given link [Kaggle Notbook - 1](https://www.kaggle.com/ayushirastogi15/house-priceprediction) and [Kaggle notebook - 2](https://www.kaggle.com/ayushirastogi15/house-prediction).

I've tried to first clean the data, impute missing values in the data, did some feature engineering as I've created some new features using existing featues and removed/dropped those columns which are not useful to us.

It turns out that wwith the given features, the **gradient boosting algorithm** with **grid search cv** method worked really well and it is giving us a good accuracy on both traning and testing dataset. The metrics I've used to measure the accuracy or the results of prediction is **mean_squared_log_error** which is a very good metric to measure the error between the predicted values and the actual values.
