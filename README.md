
## Overview

This project focuses on predicting stock closing prices using historical market data and a Long Short-Term Memory (LSTM) neural network. The model learns temporal patterns in stock prices and attempts to forecast future trends.

---

##  Objectives

* Analyze historical stock price data
* Build a predictive model using deep learning
* Evaluate model performance using standard metrics

---

##  Dataset

* Source: Yahoo Finance (via `yfinance`)
* Stock used: Microsoft (MSFT)
* Time period: 2015 – 2026

---

##  Tech Stack

* **Python**
* **Pandas & NumPy** (data processing)
* **Matplotlib & Seaborn** (visualization)
* **Scikit-learn** (preprocessing & evaluation)
* **TensorFlow / Keras** (LSTM model)
* **yfinance** (data collection)

---

##  Project Workflow

1. Data Collection using `yfinance`
2. Data Cleaning & Preprocessing
3. Feature Scaling using MinMaxScaler
4. Train-Test Split
5. LSTM Model Building
6. Model Training
7. Prediction & Evaluation

---

##  Model Details

* LSTM layers with dropout regularization
* Sequential model architecture
* Optimized using Adam optimizer
* Loss function: Mean Squared Error

---

## 📈 Evaluation Metrics

* RMSE (Root Mean Squared Error)
* R² Score

---

##  Project Structure

```
stock-price-prediction/
│── close_price_prediction_from_stock_data.ipynb
│── README.md
```

---



---

##  Results

* The model successfully captures trends in historical data
* Provides reasonable predictions of closing prices
* Performance depends on market volatility and features used

---

## 🔮 Future Improvements

* Add technical indicators (RSI, MACD)
* Use multiple stocks for training
* Hyperparameter tuning
* Deploy as a web app (Streamlit)
* Compare with other models (ARIMA, Prophet)

---

##  Key Learnings

* Time series forecasting using deep learning
* Importance of data preprocessing
* Model evaluation and tuning

---

## 👤 Author

**Swastika Mandal**
Aspiring Data Scientist | Machine Learning Enthusiast

---

