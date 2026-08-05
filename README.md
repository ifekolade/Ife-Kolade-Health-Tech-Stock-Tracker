

This is a Python notebook for primary analysis of health technology stocks, combining price data collection, technical trading signals, machine learning classification, and portfolio theory (CAPM and efficient frontier construction). I used my prior knowledge of Python programming alongside AI tools to explore how finance and data analysis might overlap.

# Overview

This project pulls historical price data for health tech and pharma tickers (ISRG, JNJ, LLY, and the S&P 500 as a benchmark) and applies several layers of analysis:

- Price visualization and descriptive statistics
- Technical trading strategies (moving average and EMA crossovers)
- A simple long-only backtesting engine
- Machine learning models to predict next-day price direction
- CAPM parameter estimation (alpha, beta, R²)
- Efficient frontier construction for a multi-stock portfolio
- A mean reversion strategy driven by RSI
