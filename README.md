Overview
Type: Momentum + Fundamental Growth
Asset(s): Top S&P 100 Stocks
Timeframe: Daily
Style: Weekly swing / Medium-term rotation
This strategy selects a subset of S&P 100 stocks based on a blend of revenue growth and 12-month price momentum. It filters for companies with strong fundamentals and recent performance while excluding high-volatility names. Portfolio rebalancing occurs weekly to ensure exposure to the top 20 scored stocks.

Parameters
Revenue Growth: > 5% year-over-year
Momentum: 12-month return > 0%
Volatility Filter: Bottom 90% of stocks by volatility retained
Portfolio Size: 20 stocks
Rebalance Frequency: Weekly (every Monday)
Strategy Logic
Signal Generation
Coarse universe filter includes only S&P 100 tickers
Fine filter includes stocks with:
Revenue growth > 5%
Positive 12-month return
Volatility in the bottom 90%
Score = 0.6 * Momentum + 0.4 * Revenue Growth
Select top 20 stocks by score
Risk Management
Equal weighting
Volatility filter excludes the riskiest names
Exit Logic
Liquidate positions not in the new selection at rebalance
Rebalance every Monday at 10:00 AM
