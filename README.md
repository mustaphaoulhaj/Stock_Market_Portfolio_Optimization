# Portfolio Optimization Project

## Overview
This project involves the optimization of a stock portfolio to identify the portfolio with the highest Sharpe ratio. 
The Sharpe ratio is a measure of risk-adjusted return, and the goal is to find the optimal mix of stocks that maximizes this ratio.

## Sharpe Ratio Calculation
The Sharpe ratio is calculated using the formula:

$$
\text{Sharpe Ratio} = \frac{R_p - R_f}{\sigma_p}
$$

where:
- $R_p$ = Expected return of the portfolio
- $R_f$ = Risk-free rate
- $\sigma_p$ = Standard deviation of the portfolio's returns (a measure of risk or volatility)

## Data Source
Historical stock data for this analysis is sourced from Yahoo Finance, retrieved using the yfinance API. 
We collected data from **July 2023** to **July 2024** for the following tickers and their associated companies:

- **AC** : Air France-KLM (Air France)
- **AI** : C3.ai, Inc.
- **BN** : LVMH Moët Hennessy Louis Vuitton
- **MC** : LVMH Moët Hennessy Louis Vuitton (also represented by ticker "MC")
- **OR** : Kering S.A.
- **TTE** : TotalEnergies

## Methodology
1. Illustrate the stock market performance of these companies in the stock market over time.
2. Visualize the distribution of daily returns of for each stock.
3. Calculate the correlation between all these stocks.
4. Calculate the expected returns and volatility for each stock.
5. Generate a series of random portfolios and plot the efficient frontier.
6. Optimize the portfolio to maximize the Sharpe ratio.

## Results

After running the portfolio optimization, you will get:

- Visualizations of stock price trends and return distributions.
- The portfolio with the maximum Sharpe ratio.
- A DataFrame displaying the optimal weights of each stock in the portfolio.

## Visualizations

The project generates the following plots:

- **Adjusted Close Price Over Time**: Shows the price trends of selected stocks.
- **Distribution of Daily Returns**: Displays histograms of daily returns for each stock.
- **Correlation_matrix**: Visualizes the correlation coefficients between the daily returns of each pair of stocks.
- **Efficient Frontier**: Illustrates the set of optimal portfolios that offer the highest expected return for a defined level of risk, or the lowest risk for a given level of expected return.
- **Portfolio Weight Distribution by Ticker**: Shows the allocation of weights for each stock in the portfolio.

## Summary
Optimizing a stock portfolio is essential for maximizing returns while controlling for risk. It enables efficient capital allocation and diversification, reducing the impact of individual stock volatility on the overall portfolio. This project demonstrates the practical application of these principles, providing a roadmap for creating balanced, high-performance investment portfolios.
