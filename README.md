# Yes_bank_stock_closing_price
Yes bank is a well known bank in India which provide wide range of services and solutions right from bank accounts, deposits, cards, cash management, privilege banking, trade finance, Non-Resident India(NRI) banking, institutional banking, merchant acquiring, digital banking and agricultural banking solutions. As the data is all about stock price so, In this project I will analysing the patterns of dataset by performing Exploratory Data Analysis and try to build a model with the help of Machine Learning for predicting the closing stock price.

The tools for data analysis and model building used in the project are the packages from the python library such as Numpy and Pandas, Matplotlib,Seaborn, Linear regression, Lasso, Ridge, ElasticNet, MinMaxScalar etc.

## Table of Contents
1. [Introduction](#introduction)
2. [Models Used](#models-used)
3. [Evaluation Metrics](#evaluation-metrics)
4. [How to Execute](#how-to-execute)
5. [Dataset](#dataset)
6. [Conclusion and Future Considerations](#conclusion-and-future-considerations)

## Introduction

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. This project aims to analyze the impact of this case on the stock prices of Yes Bank. The dataset includes monthly stock prices, and the objective is to predict the stock’s closing price of the month.

## Models Used

Three models were developed for predicting the closing price:

### Ridge Regression:

- Type: Linear regression with regularization.
- Explanation: Adds a penalty to feature coefficients to reduce overfitting.
- Usage: Effective for balancing model complexity and performance, especially with multicollinearity.

### Random Forest:

- Type: Ensemble learning model based on decision trees.
- Explanation: Creates multiple decision trees and combines their predictions.
- Usage: Suitable for handling high-dimensional data and capturing complex patterns.

### XGBoost Regressor:

- Type: Ensemble learning model using gradient boosting.
- Explanation: Builds an ensemble of decision trees sequentially, correcting errors from previous trees.
- Usage: Widely used for its exceptional predictive performance and adaptability.

## Evaluation Metrics

The models were evaluated using the following metrics:

- **RMSE (Root Mean Squared Error)**: Measures average prediction error.
- **Adjusted R2 (Adjusted R-squared)**: Adjusts R-squared for the number of predictors.
- **R2 Score (Coefficient of Determination)**: Measures proportion of variance explained by the model.

## How to Execute

To execute this project and make predictions:

1. Open the Jupyter Notebook file named `Yes_Bank_Stock_Price_Prediction.ipynb`.
2. Execute the notebook cell by cell to load and preprocess the data, train the models, and make predictions.

## Dataset

The dataset used in this project is stored in the "data" folder.

## Conclusion and Future Considerations

The project aims to create a model capable of predicting Yes Bank's closing stock price, considering the impact of the fraud case involving Rana Kapoor. Future enhancements could include exploring daily-level stock price data, incorporating additional features, and evaluating time series models for more precise predictions.

For further information and assistance, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/ankita-gupta-6a168925a/).
