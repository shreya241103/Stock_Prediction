# Project Title

This project aims to analyze and predict stock market data using various machine learning and time series analysis techniques. The main tasks include data preprocessing, feature engineering, model training, and predicting both the close values and trading strategies.

## Introduction

The project utilizes a dataset containing historical stock market data, including open, close, and volume values. The goal is to build models that can accurately predict the future close values of stocks and recommend trading strategies based on the predicted values.

## Data Preprocessing

The dataset is first loaded and checked for missing values. No missing data points are found in the training data. The "Strategy" column, representing trading strategies ("Hold", "Buy", "Sell"), is encoded into numerical values for model training.

## Exploratory Data Analysis (EDA)

EDA involves visualizing and understanding the relationships between different variables in the dataset. Various plots, including box plots, scatter plots, heatmaps, and correlation matrices, are used to analyze the data and identify patterns.

## Feature Engineering

Several new features are engineered from the existing data, including moving averages, MACD (Moving Average Convergence Divergence), market participation, and RSI (Relative Strength Index). These features are created to improve model performance and capture relevant information for predicting close values and trading strategies.

## Model Training and Evaluation

### Close Value Prediction

A SARIMA (Seasonal Autoregressive Integrated Moving Average) model is trained using exogenous variables such as open values, moving averages, and MACD. The model is evaluated using metrics such as Mean Absolute Error, Mean Squared Error, Root Mean Squared Error, and SMAPE (Symmetric Mean Absolute Percentage Error).

### Trading Strategy Prediction

A K-Nearest Neighbors (KNN) classifier is trained to predict trading strategies based on features like open, close, SMA, MACD, and RSI. The model is evaluated using accuracy metrics on both the training and validation sets.

## Results and Conclusion

The SARIMA model achieves satisfactory performance in predicting close values, while the KNN classifier shows promising results in predicting trading strategies. The project demonstrates the feasibility of using machine learning and time series analysis techniques for stock market prediction tasks.

## Future Work

Future work could involve experimenting with different models, optimizing hyperparameters, and incorporating additional features for improved prediction accuracy. Further analysis could also explore more advanced trading strategies and risk management techniques.

For more details, refer to the code and documentation in the project repository.
