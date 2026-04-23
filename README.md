# XAUUSD Data Science Project

## Overview
This project analyzes the behavior of gold (XAUUSD) prices using historical market data and machine learning techniques.

## 🎯 Objective
To predict the direction of the next price movement (bullish or bearish) using engineered features and a classification model.

## Dataset
- Source: Investing.com
- ~1300 observations
- Features: Open, High, Low, Close, Volume

## Feature Engineering
The following features were created:
- Range (High - Low) → volatility
- Body (Close - Open) → price strength
- Direction → bullish or bearish
- MA20 → trend indicator
- RSI → momentum indicator

## Model
- Logistic Regression
- Train/Test split
- Target: next candle direction

## Results
- Accuracy: ~52%
- Shows the difficulty of predicting financial markets

## Visualizations
- Price over time
- Bullish vs Bearish distribution
- RSI vs Price relationship

## Conclusion
Financial markets are complex and noisy. While the model captures some patterns, prediction remains challenging. Future improvements could include more advanced models and additional features.

## Tools Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
