# Trader Behavior vs Market Sentiment

## Objective

The purpose of this analysis is to understand how Bitcoin market sentiment (Fear vs Greed) affects trader behavior and performance on Hyperliquid.

## Data Preparation

Two datasets were used: sentiment data and trader activity data.

Key steps:

* Converted timestamps to daily dates
* Cleaned missing values and duplicates
* Aggregated trader data at daily level
* Merged datasets by date

## Key Metrics

* Daily trader PnL
* Trade frequency
* Average trade size
* Leverage distribution
* Long/Short ratio
* Win rate

## Findings

### Sentiment vs Performance

Trader performance tends to be more volatile during Fear periods.

### Behavioral Differences

During Fear:

* Higher trading activity
* Lower position sizes

During Greed:

* Increased leverage
* Larger position sizes

### Trader Segments

Three trader groups were identified:

1. High leverage traders
2. Frequent traders
3. Low leverage traders

## Strategy Recommendations

1. Reduce leverage during Fear markets to control risk.
2. Increase trading activity selectively during high volatility periods.

## Conclusion

Market sentiment has a noticeable impact on trader behavior and profitability, and incorporating sentiment signals into trading strategies can improve risk management.
