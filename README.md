# Netflix Stock Price Prediction

Welcome to the GitHub repository for the "Netflix Stock Price Prediction" project. This project leverages historical stock data to forecast future prices using advanced machine learning models. It aims to provide insights into effective strategies for predictive analysis in financial markets, particularly focusing on Netflix Inc. as a case study.

## Project Overview

This project explores the use of various statistical and machine learning techniques to predict the future stock prices of Netflix. Through comprehensive data analysis and modeling, we assess the predictive power of each model and identify the most effective approaches for stock price forecasting.

## Data Description

The dataset includes detailed daily stock prices of Netflix from the last decade. Each record in the dataset consists of the following features:

- **Date**: Trading day
- **Open**: Price of the stock at the market open
- **High**: Highest price of the stock during the trading day
- **Low**: Lowest price of the stock during the trading day
- **Close**: Price of the stock at market close
- **Adj Close**: Adjusted closing price after modifications for all applicable splits and dividend distributions
- **Volume**: Number of shares traded

This data is used to create various features that help in predicting future stock prices, such as moving averages, day-to-day return percentage, and other technical indicators.

## Models Used

The project experiments with several predictive models to evaluate their performance in forecasting stock prices:

- **Linear Regression**: A baseline model to predict future prices based on linear relationships between the features.
- **Decision Tree Regressor**: A model that uses decision rules inferred from the features to predict the price.
- **Random Forest Regressor**: An ensemble model that uses multiple decision trees to improve the prediction accuracy and avoid overfitting.
- **ARIMA (Autoregressive Integrated Moving Average)**: A common statistical model for time series forecasting which is used to predict future stock price movements based on past trends.

## Libraries and Tools

The project utilizes several Python libraries:

- `Pandas` and `NumPy` for data manipulation.
- `Scikit-learn` for implementing machine learning algorithms.
- `Matplotlib` and `Seaborn` for visualizing the data.
- `Statsmodels` for more traditional statistical approaches like ARIMA.
