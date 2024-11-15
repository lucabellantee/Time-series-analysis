# Time-series-analysis

The Standard and Poor's 500 or S&P 500 is the most famous financial benchmark in the world.

This stock market index tracks the performance of 500 large companies listed on stock exchanges in the United States. As of December 31, 2020, more than $5.4 trillion was invested in assets tied to the performance of this index.

Because the index includes multiple classes of stock of some constituent companies—for example, Alphabet's Class A (GOOGL) and Class C (GOOG)—there are actually 505 stocks in the gauge.

## How to use this dataset
- Create a time series regression model to predict S&P value and/or stock prices.
- Explore the most the returns, components and volatility of the S&P 500 index.
- Identify high and low performance stocks among the list.

## sp500_companies.csv attributes:
- *Exchange*: Exchange where its stocks are negociated
- *Symbol*: Stock symbol
- *Shortname*:Company short name
- *Longname*: Company long name
- *Sector*: Sector where the company operates
- *Industry*: Industry, within a sector, where the company operates
- *Currentprice*: Current stock price
- *Marketcap*: Current marketcap
- *Ebitda*: Earnings before interest, taxes, depreciation and amortization
- *Revenuegrowth*: Revenue growth

## sp500_index.csv attributes:
- *Date*: Date
- *S&P500*: Value of the S&P 500 index

## sp500_stocks.csv attributes:
- *Date*: Date
- *Symbol*: Company Symbol/Ticker
- *Adj Close*: Similar to the price at market closure, yet also takes into account company actions such as dividends and splits
- *Close*: Price at market closure
- *High*: Maximum value of period
- *Low*: Minimum value of period
- *Open*: Price at market opening
- *Volume*: Volume traded



