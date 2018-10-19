# Backtester

Python based Equity Backtester
Note: this is written in Python 2 and some functionality has been depricated
## This script provides a basic Backtesting / Market Simulator infrastructure for a given equity trading strategy.

Simply run the whole script to start the backtest

- It runs over the previous 12 months from the current date.

- Each day and it corresponding event (buy / sell etc) will print to console.

- A final plot of PnL will be displayed.

The idea is that you could 'plug-and-play' with various strategies -

currently a Z-score Mean Reversion strategy for "United Airlines" (or any other ticker symbol) based on significant deviation (1.5 Sigma) from the previous 20 day period mean.

It will buy or sell depending on the overbought / sold signal.
