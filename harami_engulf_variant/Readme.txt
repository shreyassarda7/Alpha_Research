This strategy is variant of Bullish Harami and Bearish Engulfing pattern.

First in "index_tickers_import.ipynb" we have parsed tickers of NIFTY50, NIFTYNEXT50, SP500 stocks from Wikipedia HTML

After that we checked our strategy for last 10 years worth of data in "candlestick_strategy.ipynb"

Finally, we applied the strategy on those stocks where last 5 years worth of mean returns >= std(last 5 years returns) and checked overall returns for 5 years/times

In, "candlestick_live_signals.ipynb" we have produced live signals to take action along with stop losses and targets.
