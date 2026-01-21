Stock Price Prediction Using LSTM

This project demonstrates how to build a stock price prediction model using Long Short-Term Memory (LSTM) neural networks. It fetches historical stock data from Yahoo Finance, visualizes closing prices, trains an LSTM model, predicts future prices, and estimates the next day’s closing price.

🚀 Features

Fetches real-time historical stock data using yfinance

Interactive price chart with hover tooltips using mplcursors

Data normalization using MinMaxScaler

Time-series forecasting using LSTM (TensorFlow / Keras)

Predicts:

Next 30 days of stock prices

Next trading day closing price

Visualizes historical and predicted prices

🧠 Model Overview

Model Type: LSTM Neural Network

Input Window: Last 90 days of closing prices

Layers:

LSTM (50 units, return sequences)

LSTM (50 units)

Dense (25 units)

Dense (1 unit)

Optimizer: Adam

Loss Function: Mean Squared Error

Epochs: 1 (can be increased for better accuracy)

📦 Installation

Install the required dependencies before running the script:

pip install yfinance
pip install mplcursors
pip install tensorflow
pip install scikit-learn
pip install matplotlib
pip install pandas
pip install numpy

▶️ How to Run

Run the script in a Python environment (Jupyter Notebook or Python file).

Enter the stock ticker symbol when prompted:

Enter the symbol: AAPL


The program will:

Download historical stock data

Plot historical closing prices

Train the LSTM model

Predict future prices

Display prediction plots

Output the predicted next-day price

📊 Visualizations

Historical Closing Price Chart

Predicted Future Prices Plot

Interactive cursor to inspect values on hover

🔮 Output

Array of predicted prices for the next 30 days

Predicted next trading day closing price

Graph combining historical and predicted data

⚠️ Notes & Limitations

This model is for educational purposes only

Uses only closing price (no volume, indicators, or fundamentals)

Accuracy depends on:

Training epochs

Market volatility

Data quality

Increasing epochs and adding technical indicators can improve results

🛠 Possible Improvements

Increase training epochs

Add technical indicators (RSI, MACD, Moving Averages)

Train/test split instead of full dataset training

Use validation data

Add confidence intervals for predictions

📚 Technologies Used

Python

TensorFlow / Keras

NumPy

Pandas

Matplotlib

yFinance

Scikit-learn

mplcursors

📌 Disclaimer

This project does not provide financial advice. Predictions are based on historical data and machine learning assumptions and should not be used for real trading decisions.
