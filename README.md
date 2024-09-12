# Apple-stock-Analysis

Introduction 📝
🎯 Goal: This project involves using a Long Short-Term Memory (LSTM) neural network to predict Apple stock prices. The LSTM model is trained on historical stock data to forecast future prices based on past trends.

📖 Data:

aapl_stock_data.csv - Historical Stock Price Dataset from Yahoo Finance

Date - The date of the stock data.

Open - The opening price of the stock.

High - The highest price of the stock.

Low - The lowest price of the stock.

Close - The closing price of the stock.

Adj Close - The adjusted closing price of the stock.

Volume - The trading volume.

💻 Model Architecture:

🔧 The LSTM model is built using TensorFlow and Keras libraries and includes the following layers:

🔁 Two LSTM Layers: Each with 50 units to capture the sequence-based relationships in the stock data.

🛡️ Dropout Layers: Added to prevent overfitting by randomly setting a portion of input units to 0 during training.

🎯 Dense Output Layer: A single unit to predict the stock price with precision.
