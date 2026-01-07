# 📈 Stock Price Prediction Using LSTM

## 🔍 Overview
This project focuses on predicting stock prices using a Long Short-Term Memory (LSTM) neural network.
LSTM is well-suited for time-series forecasting as it can capture long-term dependencies in sequential financial data.

The model is trained on historical stock price data and evaluated using a proper time-series
train-test split to avoid data leakage.

## 🎯 Problem Statement
Stock prices exhibit complex temporal patterns influenced by historical trends and market volatility.
Traditional machine learning models struggle to capture these long-term dependencies.

This project aims to leverage LSTM networks to model time-dependent behavior in stock prices
and forecast future values based on past observations.

## 🗂 Dataset
The dataset consists of historical stock price data with the following features:
- Open
- High
- Low
- Close
- Volume

The data is ordered chronologically and used as a time-series for model training and evaluation.

## 🧠 Approach & Methodology

1. Data preprocessing and cleaning
2. Feature scaling using MinMaxScaler
3. Chronological train-test split to prevent data leakage
4. Sequence generation using a fixed look-back window
5. LSTM model training on past stock data
6. Model evaluation on unseen future data
7. Visualization of actual vs predicted stock prices

## 🤖 Why LSTM?
LSTM networks are specifically designed for sequential data and can retain information
over long time intervals.

Unlike traditional models, LSTM can learn temporal dependencies in stock price movements,
making it suitable for financial time-series forecasting.

## ⚙️ Tech Stack
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

## 📊 Results
The LSTM model was able to capture the overall trend of stock prices and produced
reasonable predictions on unseen test data.

Visual comparison between actual and predicted prices demonstrates the model’s
ability to follow temporal patterns while handling market fluctuations.
![Prediction Results](results/prediction_plot.png)

## ⚠️ Limitations
- The model is trained only on historical price data
- External factors such as news and market sentiment are not considered
- Stock markets are inherently volatile and unpredictable
- This project is for educational purposes and not financial advice

## 🚀 Future Scope
- Incorporating technical indicators such as RSI and MACD
- Integrating news or social media sentiment analysis
- Multi-step forecasting (predicting next N days)
- Real-time stock prediction using live APIs
- Portfolio-level stock analysis

## ▶️ How to Run
1. Clone the repository
2. Install dependencies using `pip install -r requirements.txt`
3. Open the notebook from the `notebooks/` folder
4. Run all cells sequentially

## 👤 Author
Kislay Tinker
