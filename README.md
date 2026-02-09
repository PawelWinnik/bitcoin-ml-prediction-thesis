# Bitcoin Price Prediction - ML & Deep Learning Analysis

This project is part of my Bachelor's Thesis: *"Analysis of the predictive effectiveness of machine learning algorithms in the decentralized financial market"*.

## Project Overview
The application compares various ML models in predicting Bitcoin price movements using technical indicators.

### Tech Stack:
* **Languages:** Python
* **Data:** yfinance (BTC-USD)
* **Libraries:** Scikit-learn, TensorFlow/Keras, TA-Lib, Pandas
* **Models:** LSTM, MLP, SVM, Random Forest, Logistic Regression

### Key Features:
* **Technical Analysis:** Automated calculation of RSI, SMA, MACD, and ATR.
* **Backtesting Engine:** Realistic simulation including transaction commissions (0.15%).
* **Visualization:** Automated generation of Confusion Matrices, Equity Curves, and Sharpe Ratio comparisons.

## How to run
1. Install requirements: `pip install -r requirements.txt`
2. Run the analysis: `python main.py`
