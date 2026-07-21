# My Portfolio vs. the S&P 500

A Python project that tests a simple question: **if I hand-pick 5 stocks, do I actually beat just buying an index fund?**

## What it does

This notebook builds a hypothetical $10,000 portfolio from 5 chosen stocks (equal-weighted, buy-and-hold) and compares it head-to-head against the S&P 500 (SPY) over a 5-year period, using real historical market data.

It calculates and visualizes:
- **Portfolio growth over time** — my picks vs. the index, dollar for dollar
- **Annualized return, volatility, Sharpe ratio, and max drawdown** for every stock, the portfolio, and the benchmark
- **Risk vs. return scatter plot** — which individual stocks were actually worth the risk
- **Drawdown chart** — the worst dip an investor would have had to sit through

## Tools used

- Python
- `yfinance` — real historical stock price data
- `pandas` / `numpy` — data processing and financial calculations
- `matplotlib` — charts

## Key result

*(Fill this in after you run it with your own tickers — e.g. "My 5-stock portfolio returned X% annualized vs. Y% for the S&P 500, but with Z% more volatility.")*

## Run it yourself

Click below to open and run the notebook directly in Google Colab (no setup required):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sahibnoorchahal239-glitch/portfolio-vs-sp500/blob/main/portfolio_management_project.ipynb)

## Preview

*(Add a screenshot of the risk/return scatter plot or growth chart here — drag an image into this same repo, then reference it like:)*

`![chart](your-screenshot-filename.png)`
