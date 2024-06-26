# Machine Learning for Portfolio Optimization

This repository contains code and datasets used for predicting stock prices using Long Short-Term Memory (LSTM) neural networks, and optimizing stock portfolios using various algorithmic strategies. The project is structured to facilitate both machine learning predictions and algorithmic portfolio management.

## Project Structure

- `Algos`: Contains Jupyter notebooks and CSV files for different portfolio optimization algorithms, including Hierarchical Risk Parity (HRP) and the Markowitz model with and without neural network enhancement.
- `Predictions`: Stores CSV files with predictions of stock prices, generated by the LSTM neural network models.
- `graphs`: Directory for graphical representations of predictions and optimizations.
- `sp500.csv`: The data file containing S&P 500 index prices used for analysis and model training.

## Predictions

The LSTM model is used to predict future stock prices based on historical data. The predictions are saved in CSV files within the `Predictions` directory. Each file corresponds to a different stock symbol from the S&P 500 index.

## Portfolio Optimization Algorithms

The `Algos` directory includes a variety of optimization algorithms. Here's a brief overview:

- `HRP Clustering.ipynb`: A Jupyter notebook detailing the Hierarchical Risk Parity approach.
- `Portefeuille HRP.csv`: Output file with the optimized portfolio using HRP.
- `Portefeuilles optimaux de Markowitz avec ML.csv`: Portfolios optimized using the Markowitz model, enhanced with machine LSTM predictions.
- `erreurs_train.csv`: The training errors for machine learning models.
- `perf_measures.ipynb`: Performance measurement calculations for the optimized portfolios.
- `portfolio_optimizer.ipynb`: A notebook for running the various portfolio optimizations.
- `stock prediction NN LSTM.ipynb`: The main neural network model used for stock price predictions.

## How to Use

To use this repository for predictions and optimizations:

1. Clone the repository.
2. Run the Jupyter notebooks within the `Algos` directory to understand the optimization algorithms.
3. Check the `Predictions` directory for the LSTM model output of stock price predictions.
