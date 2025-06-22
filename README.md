# 📈 Stock Price Prediction with Machine Learning in Python

This project uses machine learning techniques to predict future stock prices based on historical data. It demonstrates how to gather data using Yahoo Finance, preprocess it, and apply an LSTM (Long Short-Term Memory) neural network to predict closing prices.

## 🔧 Features
- 📊 Fetches historical stock data using yfinance
- 🧼 Preprocesses data with MinMaxScaler
- 🧠 Trains an LSTM model using TensorFlow/Keras
- 📈 Visualizes actual vs predicted closing stock prices
- ✅ Easy-to-modify code for other stocks and date ranges

## 📦 Libraries Used
- pandas
- numpy
- matplotlib
- yfinance
- scikit-learn
- tensorflow (Keras)

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/Stock_Price_Prediction_with_Machine_Learning_in_Python.git
cd Stock_Price_Prediction_with_Machine_Learning_in_Python
```

### 2. Install Required Libraries
```bash
pip install pandas numpy yfinance matplotlib scikit-learn tensorflow
```

### 3. Run the Notebook
```bash
jupyter notebook Stock_Price_Prediction_with_Machine_Learning_in_Python.ipynb
```

## 🧪 How It Works

- **Data Collection**: Downloads historical stock data using yfinance (e.g., ANGELONE.NS).
- **Data Preprocessing**:
  - Only the 'Close' price is used.
  - Normalized using MinMaxScaler to range [0, 1].
- **Model Architecture**:
  - Uses an LSTM-based Sequential model.
  - Trained on 80% of the dataset, tested on the remaining 20%.
- **Prediction & Visualization**:
  - Predicts the future stock prices.
  - Plots comparison between actual and predicted prices.

## 📷 Sample Output

![Screenshot 2025-06-22 122127](https://github.com/user-attachments/assets/95f179cd-4f0a-4c22-a52d-72caca5595ba)


## 📌 Notes
- The model is trained on ANGELONE.NS, but you can change the ticker symbol to any stock.
- LSTM is well-suited for time series forecasting but performance depends on data quality and model tuning.

