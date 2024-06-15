# Time Series Forecasting: Stock Price Prediction using LSTM

This project demonstrates how to forecast stock prices using a Long Short-Term Memory (LSTM) neural network. We use historical stock price data from Yahoo Finance to train and evaluate our model. The project is implemented in Python and utilizes libraries such as TensorFlow/Keras, Pandas, NumPy, and Matplotlib.

## Project Overview

The project includes the following steps:
1. Load and preprocess historical stock price data.
2. Perform exploratory data analysis (EDA).
3. Build and train an LSTM model for time series forecasting.
4. Evaluate the forecasting performance.
5. Visualize the forecasted vs. actual stock prices.

## Tools and Libraries

- Python
- TensorFlow/Keras
- Pandas
- NumPy
- Matplotlib
- yfinance

## Setup and Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/stock-price-prediction.git
    cd stock-price-prediction
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. If you are using Google Colab, ensure that you mount your Google Drive to save and load data.

## Data Collection

We use the Yahoo Finance library to download historical stock price data.

```python
import yfinance as yf

# Define the ticker symbol and download data
ticker = 'AAPL'  # Apple Inc.
data = yf.download(ticker, start='2015-01-01', end='2022-12-31')

```
## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
The project uses data from Yahoo Finance.
The LSTM model implementation is based on TensorFlow/Keras.
