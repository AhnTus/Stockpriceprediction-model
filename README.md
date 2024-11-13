**Vietnamese Stock Price Prediction: *Analyzing Market Trends and Forecasting Future Price***
============
This work is a mini-project under the course IT2022E - Applied Statistics and Experimental Design.
Supervisor: Assoc. Prof. NGUYEN Linh Giang

This repository contains all folders of our project about "Stock Price Analysis and Prediction".
---

![image](https://github.com/tttruong0812/Capstone-Project-ML/assets/95478230/eb5cb261-5759-4937-a9a5-cff1cba66229)


Dataset is attached in the folder "Dataset", that includes some stocks in diffrent fields (construction, finance, consumer, technology).

We analyze some indicators like RSI, buy or sell signal in folder "Data Analysis". You can access this to see implementation, some properties of dataset and our prediction about buy or sell  indicated RSI.

About machine learning models, we use three algorithms that are ARIMA, Support Vector Regression (SVR), Extreme Gradient Boosting (XGBoost) to train, deploy and evaluate model, then give predictions about price of stock.

Before using algorithms to train model, we created data preprocessing, cleaning, and visualization for easier implementation.

In ARIMA model, we apply some test statistics to check if data is stationary or not, and then choose the parameters to train and evaluate model.

In folder SVR and XGBoost, we try to  model selection and choose optimal hyperparameters by using Nested Cross Validation Time Series (Predict-Second-Half and Day-Forward-Chaining). After that, we use that hyperparameters to retrain, evaluate model and predict price of stocks.
