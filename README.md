# Exploring and Forecasting Saudi Stock Market (Kingdom 4280) using ARIMA

This project focuses on exploring and forecasting the stock prices of **Kingdom Company (4280)** listed in the **Saudi Stock Exchange (Tadawul)** using **Time Series Analysis**. By applying the ARIMA model on historical daily stock prices from **2008 to 2020**, the goal is to extract patterns, identify trends, and build a forecasting model that can aid in financial insights and future predictions.

## 🛠️ Technologies Used
- Python  
- Google Colab  
- Pandas  
- NumPy  
- Matplotlib  
- statsmodels  
- scikit-learn  

## ▶️ How to Run

This project is implemented in Google Colab. You can simply open the notebook and run the cells in order.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/176dymo2_xiMNwoZVZJ7LjuXnlhwg6wIz?usp=sharing)

## 📊 Results

The ARIMA(1,1,1) model was successfully fitted to the historical daily stock prices of Kingdom Company (Ticker: 4280). After differencing the data to ensure stationarity, the model was able to capture the underlying structure of the series.

Key observations:
- The model was trained on historical data from 2008 to 2020 and produced forecasts for the test set.
- Visual comparison between actual and predicted values shows that the ARIMA model captured the general trend, but struggled with short-term volatility.
- The **Mean Absolute Error (MAE)** between the forecasted and actual values was approximately **2.82**, indicating a moderate level of accuracy for daily stock price prediction.

### 🔍 Forecast Visualization

![ARIMA Forecast](arima_forecast.png)

## 📌 Notes
- Dataset used: Saudi Daily Stocks History (Tadawul), focusing on Kingdom 4280 stock.
- This analysis was conducted purely for academic and learning purposes.

## 📄 License
MIT License
# saudi-stock-arima
ARIMA Time Series Forecasting for Saudi Stock Market
