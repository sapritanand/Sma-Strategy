# Sma-Strategy

<h1>SMA Crossover Strategy
This project implements a Simple Moving Average (SMA) Crossover Strategy for stock trading. The strategy involves generating buy and sell signals based on the crossing points of short-term and long-term moving averages. It's designed to help traders make decisions about when to enter or exit trades.

<h2>Project Overview
The notebook in this repository (SmaCrossOver.ipynb) walks through the implementation of the SMA Crossover Strategy. It demonstrates how to:

Calculate short-term and long-term SMAs for historical stock price data.
Identify crossover points where trading signals are generated.
Backtest the strategy to evaluate its performance over a given time period.
<h2>Key Features
Data Import: The notebook pulls historical stock price data for analysis.
SMA Calculation: Two SMAs are calculated:
Short-term SMA (e.g., 50-day)
Long-term SMA (e.g., 200-day)
Signal Generation: Buy and sell signals are generated based on the crossing of the two SMAs:
Buy Signal: When the short-term SMA crosses above the long-term SMA.
Sell Signal: When the short-term SMA crosses below the long-term SMA.
Backtesting: The strategy is backtested to assess profitability, using common financial metrics.
