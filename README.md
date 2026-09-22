# AAPL Stock Price Movement Prediction

## Project Overview

This project predicts the next-day movement of Apple Inc. (AAPL) stock using Machine Learning techniques.

Historical AAPL stock data is analyzed and technical indicators are created to identify patterns in stock price movement. The project uses Logistic Regression and Random Forest algorithms to predict whether the next day's closing price will increase or decrease.

## Objectives

- Analyze historical AAPL stock data
- Perform Exploratory Data Analysis (EDA)
- Create useful technical indicators and features
- Predict next-day stock price movement
- Train and evaluate Machine Learning models
- Compare the performance of different models

## Dataset

The dataset contains historical AAPL stock information including:

- Date
- Open
- High
- Low
- Close
- Adjusted Close
- Volume

Additional features were created during the project.

## Features Used

The Machine Learning models use the following features:

- Close
- Return
- MA10
- MA20
- MA50
- RSI14
- Volatility_20
- High_Low_Range
- Open_Close_Diff
- Volume_Change

## Target Variable

The target indicates whether the next day's closing price is higher than the current day's closing price.

- 1 = Price goes up
- 0 = Price does not go up

## Machine Learning Models

The following models were implemented:

1. Logistic Regression
2. Random Forest Classifier

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Project Files

- AAPL_Stock_Prediction.ipynb – Complete Google Colab notebook
- AAPL_EDA.csv – Exploratory Data Analysis dataset
- AAPL_processed_dataset.csv – Processed dataset
- model_comparison.csv – Comparison of machine learning models
- final_predictions.csv – Final prediction results

## Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- GitHub

## Conclusion

This project demonstrates how historical stock-market data and technical indicators can be used to build a machine-learning classification model for predicting next-day AAPL stock price movement.

The project is intended for educational and analytical purposes and should not be considered financial advice.

## Author

AAPL Stock Prediction Project
