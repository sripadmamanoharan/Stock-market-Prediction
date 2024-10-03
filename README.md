# Stock-market-Prediction

This project aims to predict stock prices by leveraging historical financial data and using both ARIMA (statistical model) and LSTM (deep learning model) for time series forecasting. The project demonstrates feature engineering techniques and applies machine learning and deep learning algorithms to forecast stock prices, providing a comprehensive view of stock market trends.

Project Structure
Data Source: Stock data for Tesla (TSLA) is sourced using the yfinance API.
Feature Engineering: Includes the creation of technical indicators like moving averages, momentum, and VWAP.
Models Used:
ARIMA: A statistical model used for time series forecasting.
LSTM: A deep learning model tailored to handle sequential data, making it suitable for time series forecasting.
Features
Time Series Forecasting: Forecast stock prices using historical data.
Feature Engineering: Incorporates technical indicators such as Moving Averages, Momentum, and VWAP.
Dual Model Implementation: Combines ARIMA for traditional statistical analysis and LSTM for advanced deep learning predictions.
Performance Evaluation: Compares models using performance metrics such as RMSE (Root Mean Squared Error).
Tech Stack
Programming Language: Python
Libraries Used:
Data Handling: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Modeling: ARIMA, LSTM (Keras)
API for Data Collection: yfinance
Time Series Libraries: pmdarima (for ARIMA)
Scaler: MinMaxScaler (for LSTM data preprocessing)
Evaluation: Mean Squared Error (MSE)
