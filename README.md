Stock Insight Generator based on Fundamentals, Moving Average Crossovers, and Reddit Sentiment

Midterm Project for ECON-UB 232 Developers: Darren Nguyen, Zayaan Atif, Bryan Zhao

This program creates a composite score for S&P 500 stocks based on return on assets, return on equity, moving average momentum, number of mentions in subreddits, and average sentiment across those subreddits. It pulls data from yfinance and different stock-related subreddits.

Essential Questions:

How can we combine current sentiment, price momentum, and underlying valuation metrics to create a relative composite score for each stock?

On average, what sector performs best under our scoring method?

Based on these metrics, which stocks from the S&P 500 should be purchased?

Similarly, what stocks should be shorted?

How do price moving averages with different windows compare relative to each other?

What similarities exist between the graphs of two different stocks in the same sector? How about the graphs of two different stocks’ moving averages?

The final equation came out to be: Composite Score = (Sentiment Weight x Average Sentiment x Mentions) + (Momentum Weight * MA Momentum) + (ROE Weight * ROE) + (ROA Weight * ROA)

We used weights: Sentiment Weight: 12.5% Momentum Weight: 50% ROE Weight: 12.5% ROA Weight: 12.5%

The top 3 stocks were NVDA, UNH, and AMD. The bottom 3 stocks were XRX, GT, and ALGN.

The best performing sector was Technology, and the worst performing sector was Consumer Defensive. Stocks within the same sector have similar trends in their price graphs and moving average graphs.
