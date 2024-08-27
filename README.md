# Stock Price Prediction

This project uses machine learning to predict stock prices based on historical data. It leverages various Python libraries to retrieve financial data, preprocess it, and build predictive models.

## Project Description

The objective of this project is to predict stock prices specifically of Tesla using historical data retrieved from Yahoo Finance. The notebook includes steps for data collection, preprocessing, visualization, and model training. Various evaluation metrics are used to assess the model's performance.

## Features

- **Data Retrieval**: Using `yfinance` to fetch historical stock data of Tesla.
- **Data Visualization**: Employing `matplotlib`, `seaborn`, and `plotly` for visualizing trends and model predictions.
- **Modeling**: Implementing linear regression using `sklearn` to predict future stock prices.
- **Evaluation**: Assessing the model with metrics like Mean Squared Error (MSE), R² score, and Mean Absolute Error (MAE).

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Aarnav005/Stock-Price-Prediction.git
   cd Stock-Price-Prediction
   ```

2. Install the required libraries:

   ```bash
   pip install yfinance
   pip install plotly
   pip install numpy
   pip install pandas
   pip install matplotlib
   pip install seaborn
   pip install scikit-learn
   ```

   Alternatively, you can install all the dependencies at once:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook StockPricePred.ipynb
   ```

   Follow the steps in the notebook to fetch stock data, preprocess it, and train the predictive model.

## Usage

After running the notebook, you can explore the following analyses and features:

### 1. Data Exploration and Visualization

- **Historical Stock Data Analysis**: Visualize historical stock prices with line charts and candlestick plots to observe trends, patterns, and anomalies over time.
- **Correlation Analysis**: Explore the relationships between different financial metrics and stock prices using heatmaps and scatter plots.
- **Moving Averages**: Calculate and plot moving averages to identify trends and potential buy/sell signals.

### 2. Predictive Modeling

- **Model Training**: Train a linear regression model on the historical stock data to predict future stock prices.
- **Model Evaluation**: Assess the model's performance using metrics like Mean Squared Error (MSE), R² score, and Mean Absolute Error (MAE).
- **Prediction Visualization**: Visualize the model's predictions against actual stock prices to evaluate accuracy and reliability.
