# Apple-stock-Analysis

Introduction 📝
🎯 Goal: This project involves using a Long Short-Term Memory (LSTM) neural network to predict Apple stock prices. The LSTM model is trained on historical stock data to forecast future prices based on past trends.

📖 Data:

Date - The date of the stock data.

Open - The opening price of the stock.

High - The highest price of the stock.

Low - The lowest price of the stock.

Close - The closing price of the stock.

Adj Close - The adjusted closing price of the stock.

Volume - The trading volume.

EDA 📊
📂 Loading the Dataset:

Read the CSV file: Load the Apple stock data (aapl_us_d.csv) using pandas. Display the first few rows to get a glimpse of the dataset structure.

Summary Statistics: Generate summary statistics for each feature to gain insight into the distribution of values and overall trends in Apple's stock data.

Checking for Missing Values: Identify any missing data that might need to be cleaned or handled to ensure accurate analysis.

📊 Data Visualization:

📉 Line Plot of Closing Prices: Visualize the trend of Apple’s closing stock prices over time to track how the stock fluctuates and identify any potential patterns.

📊 Histogram of Closing Prices: Analyze the distribution of closing prices to see how often certain price ranges occur and detect any skewness or outliers.

🔥 Correlation Heatmap: Use a heatmap to understand the correlations between different stock features (e.g., Open, Close, High, Low, Volume)

🔗 Scatter Plot (Open vs. Close Prices): Explore the relationship between Tesla's opening and closing prices. Identify if there’s a strong correlation between these features.

📈 Histogram of Daily Returns: Analyze the distribution of Tesla’s daily returns to get a sense of stock volatility and how often the stock price changes.

📊 Moving Averages: Plot the 50-day and 200-day moving averages along with closing prices to help identify longer-term trends and smooth out short-term fluctuations.

💻 Model Architecture:

🔧 The LSTM model is built using TensorFlow and Keras libraries and includes the following layers:

🔁 Two LSTM Layers: Each with 50 units to capture the sequence-based relationships in the stock data.

🛡️ Dropout Layers: Added to prevent overfitting by randomly setting a portion of input units to 0 during training.

🎯 Dense Output Layer: A single unit to predict the stock price with precision.
