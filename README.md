# 📈 Bitcoin Time Series Analysis

This repository contains a detailed time series analysis of daily **Bitcoin closing prices** from **September 2014 to March 2025**. Using classical statistical techniques and visualizations, the project investigates trends, stationarity, volatility, and distributional properties of Bitcoin prices.

## 📊 Overview

Bitcoin exhibits highly volatile behavior, making it a unique candidate for time series analysis. This project focuses on understanding the underlying dynamics of Bitcoin's daily closing prices and provides insights into:

- Price trends and seasonality
- Stationarity and differencing
- Volatility and outliers
- Residual analysis and fitted distributions
- Auto-correlation and partial auto-correlation

## 🔍 Key Techniques Used

- **Logarithmic Transformation** for variance stabilization
- **Moving Averages** for trend visualization
- **First-Order Differencing** to address non-stationarity
- **Augmented Dickey-Fuller Test** for statistical stationarity checks
- **IQR Method** for outlier detection
- **ACF & PACF Plots** for temporal dependency analysis
- **Distribution Fitting** including t-distribution to model heavy tails


## 📚 Dataset

- Source: [Yahoo Finance – BTC-USD](https://finance.yahoo.com/quote/BTC-USD/history/)
- Fields:
  - Date
  - Open, High, Low, Close prices
  - Volume


## 🧾 References

- Dickey, D.A., & Fuller, W.A. (1979). *Distribution of the Estimators for Autoregressive Time Series with a Unit Root.*
- Yahoo Finance (2025). *Bitcoin Historical Price Data.*
