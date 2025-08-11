# How It Works

# Load Data

Fetch historical stock prices from Yahoo Finance for AAPL from Jan 2022 to Dec 2024.

Automatically adjust prices for stock splits and dividends.

# Prepare Data

Use Open, High, Low, and Volume as features.

Create a target column Next_Close representing the next day's closing price.

# Split Data

80% for training, 20% for testing.

shuffle=False to respect time order.

# Train Model

Use LinearRegression from scikit-learn.

# Evaluate Model

Calculate MSE and R² score.

Compare actual vs predicted prices.

# Visualize Results

Plot actual vs predicted values.

# 📜 Example Output

Data shape: (X, Y)
Mean Squared Error: 2.45
R-squared Score: 0.87
