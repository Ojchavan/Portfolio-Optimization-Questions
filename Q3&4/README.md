Overview

This Python script performs a detailed analysis of stock data for Apple (AAPL) and Tesla (TSLA). It downloads historical daily stock prices, calculates daily returns, computes performance metrics like the Sharpe Ratio, evaluates a portfolio's returns, and visualizes cumulative returns. The script is divided into two main parts:

AAPL Stock Analysis:
Calculates daily returns for AAPL.
Computes the Sharpe Ratio for a specified time range.
Plots cumulative returns for AAPL over a given period.

Portfolio Analysis with AAPL and TSLA:
Calculates daily returns for both AAPL and TSLA.
Computes monthly mean and standard deviation of returns for AAPL and TSLA.
Creates a portfolio with predefined weights and calculates the total return.
Script Workflow

Download Data:
Historical data for AAPL and TSLA is downloaded using Yahoo Finance (yfinance library) and saved locally as CSV files.

Process Data:
The script reads the CSV files, removes timezone data, and adds daily returns to the dataset.

AAPL Analysis:
Computes daily returns and Sharpe Ratio (using a risk-free rate of 0%).
Visualizes cumulative returns for AAPL from 2000 to 2023.

Portfolio Analysis:
Calculates monthly mean and standard deviation of daily returns for AAPL and TSLA from 2015 to 2022.
Constructs a portfolio with weights $w_{AAPL} = \frac{1}{3}$ and $w_{TSLA} = \frac{2}{3}$
Computes the portfolio's total return for 2014-2022.
