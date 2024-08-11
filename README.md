# Stock Price Predictor App

This repository contains a web-based Stock Price Predictor application that uses historical stock data and a machine learning model to predict future stock prices. The app is built using Streamlit and TensorFlow, leveraging financial data from Yahoo Finance.

## Features

- **Real-Time Stock Data**: Fetches the latest 20 years of stock data using Yahoo Finance.
- **Moving Averages**: Displays the moving averages (MA) for 100, 200, and 250 days.
- **Predictive Modeling**: Predicts future stock prices based on historical data using a pre-trained machine learning model.
- **Data Visualization**: Visualizes the actual vs. predicted stock prices.

## Requirements

- Python 3.8 or later
- Streamlit
- TensorFlow (Keras)
- Pandas
- Numpy
- Matplotlib
- scikit-learn
- yfinance

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/stock-price-predictor.git
   cd stock-price-predictor
## Step 3: Install Required Python Packages

```bash
pip install -r requirements.txt
```
## Step 4: Download the Pre-Trained Model

You need to download the pre-trained model and place it in the root directory. The model file should be named `Latest_stock_price_model.keras`.

```bash
# Example command to download the model (replace with actual command or link)
# wget -O Latest_stock_price_model.keras <model_download_link>
```
## Step 5: Run the Streamlit App

```bash
streamlit run web_stock_price_predictor.py
```


