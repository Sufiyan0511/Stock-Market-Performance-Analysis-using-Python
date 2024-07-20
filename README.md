# Stock Data Analysis and Visualization

This repository is a personal project for analyzing and visualizing stock market data.

## Project Goals

The goal of this project is to analyze recent stock performance trends and visualize moving averages and volatility.

## Libraries Used

- **pandas**: For data manipulation and analysis.
- **plotly.express**: For interactive plotting.
- **yfinance**: For downloading stock market data.
- **datetime**: For date and time handling.

## Features

1. **Downloading Stock Data**:
   - Retrieves historical stock data for a list of tickers over the past 3 months.

2. **Preparing Dataset**:
   - Merges individual stock data into a single DataFrame and resets the index.

3. **Visualizations**:
   - **Line Chart**: Plots closing prices over time.
   - **Area Chart**: Shows an area chart of closing prices with separate facets for each stock.

4. **Moving Average Calculation**:
   - Computes and visualizes 10-day and 20-day moving averages.

5. **Volatility Calculation**:
   - Calculates and visualizes the rolling 10-day standard deviation of percentage changes.

6. **Correlation Analysis**:
   - Calculates and visualizes the correlation matrix of the tickers.

## Acknowledgements
Special thanks to the resources and tutorials that helped in implementing this project.[https://thecleverprogrammer.com/2023/05/08/stock-market-performance-analysis-using-python/]
