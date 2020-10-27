# Car Sales Prediction

Predicting car sales based on the model features. The notebook explores Tesla sales data from 2019. Several different methods were tried to determine the best model. The models used were

* Stochastic Gradient Descent
* Normal Equation
* GLM
* Random Forest Regression

All models were fairly consistant in their predictions and performed well when measured against RMSE and r-squared matrices.

The second notebook optimizes the hyper parameters for SGD and Random Forest Regressor.

Some observations include the sensitivity to train-dev split for SGD and Random Forest in this dataset. The problem probabaly occurs due to small sample size where a lot of vehicle types have very small number of units sold. This can probably be fixed by consolidatig the data in smaller groups so that these small categories are consolidated in a few major categories.

