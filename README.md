# Stock Market Prediction

This project analyzes historical stock price data and predicts short-term price movement trends using machine learning.

## Problem Statement
Stock market prices are highly volatile and difficult to predict.  
Instead of predicting exact prices, this project focuses on predicting whether the stock price will move **up or down** over a future time window.

## Dataset
- Historical stock price data downloaded using `yfinance`
- Example stock used: Apple (AAPL)
- Features include Open, High, Low, Close, and Volume

## Approach
- Calculated technical indicators such as:
  - 50-day Moving Average
  - 200-day Moving Average
  - Daily Returns
  - Volatility
  - Momentum
- Created a target variable based on future price movement
- Used **time-series split** to avoid data leakage
- Trained a Random Forest classification model

## Results
- Applied time-series split for realistic evaluation
- Achieved around **50% accuracy** in predicting 10-day price movement
- Results reflect the real-world uncertainty of financial markets

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- yfinance
- Google Colab / Jupyter Notebook

## Conclusion
This project demonstrates proper methodology for stock market trend prediction, emphasizing correct data handling and evaluation over unrealistically high accuracy.
