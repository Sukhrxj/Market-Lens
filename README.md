# MarketLens — AI Market Analytics Platform

MarketLens is a machine learning-powered financial analytics platform that predicts short-term stock price movement using historical market data, technical indicators, and macroeconomic signals.

The platform uses an XGBoost classification model to forecast whether a stock is likely to increase or decrease over a 15-day period while providing backtesting insights and prediction confidence.

---

## Features

- 📈 Machine learning stock movement prediction
- 📊 Technical indicator feature engineering
- 🌎 Macroeconomic data integration using FRED API
- 🔍 Historical backtesting across multiple equities
- ⚙️ Automated daily prediction pipeline
- 📉 Interactive analytics dashboard

---

## Tech Stack

### Machine Learning
- Python
- XGBoost
- Scikit-learn
- Pandas
- NumPy

### Financial Data
- yfinance
- FRED API

### Development
- GitHub Actions
- Flask
- Git

---

## Machine Learning Pipeline

### 1. Data Collection
Historical market data is collected from financial APIs.

### 2. Feature Engineering

Generated features include:

- Moving averages
- Momentum indicators
- Market trends
- Technical signals
- Macroeconomic variables

### 3. Model Training

An XGBoost classifier predicts 15-day stock price direction.

### 4. Backtesting

The model is evaluated using historical market periods to analyze:

- Accuracy
- Prediction confidence
- Performance metrics

---

## Project Structure
