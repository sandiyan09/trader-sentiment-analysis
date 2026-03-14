# trader-sentiment-analysis
Trader Performance vs Market Sentiment Analysis – Primetrade.ai Assignment
# Trader Performance vs Market Sentiment Analysis

## Objective

This project analyzes how Bitcoin market sentiment (Fear vs Greed) affects trader behavior and performance on Hyperliquid.

The goal is to identify patterns that can help improve trading strategies.

## Datasets Used

### 1. Bitcoin Fear & Greed Sentiment

Contains daily sentiment classification:

* Fear
* Greed

### 2. Hyperliquid Historical Trader Data

Contains:

* account
* symbol
* price
* trade size
* side (long/short)
* leverage
* closedPnL
* timestamp

## Data Preparation

Steps performed:

* Loaded both datasets using Pandas
* Checked missing values and duplicates
* Converted timestamps to datetime
* Aggregated trader data to daily level
* Merged sentiment data with trader activity by date

## Metrics Created

* Daily PnL
* Win rate
* Trade frequency
* Average trade size
* Leverage distribution
* Long vs Short ratio

## Analysis

We compared trader behavior across:

* Fear vs Greed market conditions
* High leverage vs low leverage traders
* Frequent vs infrequent traders

## Key Insights

1. Traders tend to increase leverage during Greed markets.
2. Trade activity increases during Fear periods.
3. High leverage traders show higher profit potential but larger losses.

## Strategy Recommendations

1. During Fear markets, reduce leverage to limit downside risk.
2. During Greed markets, traders may increase exposure cautiously.

## How to Run

Install dependencies:

pip install pandas numpy matplotlib seaborn

Open the notebook:

jupyter notebook trader_sentiment_analysis.ipynb

## Author

Dhanush
Data Science Internship Assignment – Primetrade.ai
