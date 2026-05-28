# XAUUSD Data Science Project

## Overview

This project analyzes the behavior of gold prices (XAUUSD) using historical financial market data and machine learning techniques. The main goal of the project is to explore whether future market direction can be predicted using engineered technical indicators and historical price behavior.

The project demonstrates a complete introductory data science workflow including:

* Data cleaning and preprocessing
* Feature engineering
* Exploratory data analysis
* Data visualization
* Machine learning classification
* Model evaluation

---

## Objective

The objective of this project is to predict the direction of the next market candle:

* **Bullish (1)** → price closes higher
* **Bearish (0)** → price closes lower

A Logistic Regression model was trained to classify future price direction based on historical market features and technical indicators.

---

## Dataset

* **Asset:** Gold Spot Price (XAUUSD)
* **Source:** Investing.com
* **Observations:** ~1300 rows

### Original Variables

* Open
* High
* Low
* Close
* Volume

The dataset contains historical gold market data used for financial analysis and predictive modeling.

---

## Data Cleaning & Preprocessing

Several preprocessing steps were performed before analysis:

* Renaming columns
* Removing unnecessary columns
* Converting string values into numerical data
* Cleaning volume data
* Handling missing values

These steps prepared the dataset for feature engineering and machine learning analysis.

---

## Feature Engineering

Additional market features were created to improve the predictive model and better represent market behavior.

### Engineered Features

| Feature   | Description                                |
| --------- | ------------------------------------------ |
| Range     | High - Low (market volatility)             |
| Body      | Close - Open (candle strength)             |
| Direction | Bullish or bearish candle                  |
| MA20      | 20-period moving average                   |
| RSI       | Relative Strength Index momentum indicator |
| Target    | Next candle direction                      |

These features help capture:

* market volatility,
* momentum,
* trend direction,
* and candle behavior.

---

## Exploratory Data Analysis

Several visualizations were created to better understand the dataset and market behavior.

### Visualizations Included

* XAUUSD price movement over time
* Bullish vs Bearish distribution
* RSI vs Price relationship
* Correlation heatmap

The visual analysis helped identify trends, relationships between variables, and overall market characteristics.

---

## Machine Learning Model

### Model Used

* Logistic Regression

### Workflow

1. Feature selection
2. Train/Test split
3. Model training
4. Predictions
5. Performance evaluation

### Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## Results

The Logistic Regression model achieved an accuracy of approximately **52%**.

The results demonstrate the difficulty of predicting financial markets due to:

* market volatility,
* noise,
* external economic factors,
* and non-linear price behavior.

Although prediction accuracy is limited, the project successfully demonstrates the use of machine learning techniques on real-world financial data.

---

## Conclusion

This project shows how data science and machine learning techniques can be applied to financial market analysis.

The project successfully demonstrates:

* data preprocessing,
* feature engineering,
* exploratory data analysis,
* machine learning classification,
* and model evaluation.

Future improvements could include:

* larger datasets,
* additional technical indicators,
* advanced machine learning algorithms,
* and deep learning techniques.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Files Included

| File                    | Description               |
| ----------------------- | ------------------------- |
| `xauusd_analysis.ipynb` | Main project notebook     |
| `xauusd.csv`            | Historical XAUUSD dataset |
| `README.md`             | Project documentation     |

---

## Author

Francesko Hasipi
