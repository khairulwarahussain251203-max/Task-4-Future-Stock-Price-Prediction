# Stock Price Prediction Model

## 📈 Predict Future Stock Prices (Short-Term)

A machine learning project that predicts the next day's closing price of stocks using historical data from Yahoo Finance. The project implements and compares Linear Regression and Random Forest models for time series prediction.


---

## 🔍 Overview

This project demonstrates how to use machine learning models to predict stock prices based on historical market data. It fetches real-time data from Yahoo Finance, engineers relevant features, and trains two different regression models to forecast the next day's closing price.

---

## ✨ Features

- **Real-time Data Fetching**: Automatically downloads historical stock data using yfinance
- **Feature Engineering**: Creates technical indicators and lag features
  - Price percentages (High-Low, Close-Open)
  - Moving averages (5, 10, 20 days)
  - Volatility measures
  - Lag features from previous days
- **Multiple Models**: Implements and compares:
  - Linear Regression
  - Random Forest Regressor
- **Performance Metrics**: Evaluates models using:
  - Mean Squared Error (MSE)
  - R² Score
  - Mean Absolute Error (MAE)
- **Visualizations**: Comprehensive plots including:
  - Actual vs Predicted prices
  - Residuals analysis
  - Feature importance
  - Error distributions

---

## 🛠️ Technologies Used

- **Python 3.7+**
- **Libraries**:
  - `yfinance` - Stock data fetching
  - `pandas` - Data manipulation
  - `numpy` - Numerical computations
  - `matplotlib` & `seaborn` - Data visualization
  - `scikit-learn` - Machine learning models
  - `warnings` - Suppress warnings

---

## Run Individual Components
The project is divided into 10 parts that can be run separately:

Part 1: Data fetching and imports

Part 2: Feature engineering

Part 3: Data preparation

Part 4: Linear Regression training

Part 5: Random Forest training

Part 6: Model comparison

Part 7-8: Visualizations

Part 9: Next day prediction

Part 10: Summary report