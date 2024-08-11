# Stock Market Predictor using LSTM

## Project Overview

This project focuses on building and training a Long Short-Term Memory (LSTM) model to predict the next day's closing price of a stock. The notebook contains all the steps involved in data preprocessing, model architecture design, training, and evaluation. It is part of a larger project aimed at creating a web application that provides stock price predictions based on historical data.

## Project Structure

- **Data Preprocessing:** The notebook begins with data loading and preprocessing steps. This includes handling missing data, normalizing the dataset, and preparing the data for input into the LSTM model.

- **LSTM Model:** The core of the project is the LSTM model, which is a type of recurrent neural network (RNN) well-suited for time series prediction tasks. The model is designed to capture temporal dependencies in stock prices and make accurate predictions.

- **Training:** The model is trained on historical stock price data, with the aim of minimizing the prediction error for the next day's closing price. Various hyperparameters, such as the number of LSTM units, learning rate, and epochs, are tuned to optimize performance.

- **Evaluation:** The model's performance is evaluated using metrics such as Mean Squared Error (MSE) and visualized through plots comparing the predicted prices with the actual prices.

## Larger Project Context

This notebook is a crucial component of a larger project: a web application that provides users with daily stock price predictions. The LSTM model developed here is integrated into the web app, which allows users to input stock ticker symbols and receive predictions for the next day's closing price.

## Getting Started

To run this notebook locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd stock-market-predictor-lstm
   ```
3. **Install the required dependencies:**
   Create Your virtual enviroment and install dependencies...
   
   ```bash
   pip install -r requirements.txt
   ```
5. **Open the Jupyter Notebook:**
   ```bash
   jupyter notebook "Stock Market Predictor LSTM.ipynb"
   ```
## Dependencies

This project requires the following Python libraries:

- **yfinance**: For downloading historical stock price data.
- **torch**: PyTorch, used for building and training the LSTM model.
- **pandas**: For data manipulation and analysis, particularly for handling time series data.
- **tqdm**: For displaying progress bars during data processing and model training.
- **scikit-learn**: For preprocessing tasks like scaling and evaluation metrics.
- **matplotlib**: For plotting stock prices and model predictions.
- **numpy**: For numerical computations and handling arrays.
- **optuna**: For hyperparameter optimization.
- **datetime** and **dateutil.relativedelta**: For handling and manipulating date and time data.
- **warnings**: To manage warning messages during execution.
