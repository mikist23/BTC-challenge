# Bitcoin Trading Algorithm

This is a machine learning-based Bitcoin trading algorithm using **Logistic Regression**. The model is designed to predict buy/sell signals based on historical Bitcoin price data.

## Prerequisites

To run this project, you will need Python 3.x installed, as well as the following dependencies. These will be installed in your virtual environment.

- scikit-learn
- pandas
- matplotlib
- numpy
- imbalanced-learn (for SMOTE)

## Setup Instructions

### 1. Clone the Repository or Download the ZIP File

download the project ZIP file and extract it to your preferred location.

### 2. Create and Activate Virtual Environment

Make sure to create and activate a virtual environment to manage dependencies:

- **On Windows**:
  ```bash
  python -m venv venv
  .\venv\Scripts\activate
  ```

- **On macOS/Linux**:
  ```bash
  python3 -m venv venv
  source venv/bin/activate
  ```

### 3. Install the Required Dependencies

Install the necessary libraries from the `requirements.txt` file by running the following command while the virtual environment is active:

```bash
pip install -r requirements.txt



## Feature Engineering

The following features have been added to the model:

## Summary of Features:
- **Trend Indicators**: Moving averages (MA7, MA30, MA60, MA200) and EMAs (EMA12, EMA26) help to identify trends over different time periods.
- **Momentum Indicators**: MACD, MACD_signal, ROC, and Momentum capture the speed of price changes and potential reversals.
- **Volatility Indicators**: ATR and Bollinger Bands provide insights into the market’s volatility and overbought/oversold conditions.
- **Market Strength**: RSI helps gauge the strength of a market trend and potential reversals based on price momentum.
- **Lag Features**: The lag features help capture short-term price movements from past data points.

These features are designed to provide a comprehensive view of market conditions and allow the model to make informed predictions based on a range of technical indicators.
