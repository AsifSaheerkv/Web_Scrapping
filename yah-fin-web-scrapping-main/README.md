# yahoo finance web scrapping package

This repository is a demonstration of how to use the yahoo_fin package to scrape data from Yahoo Finance. The package is powerful and user-friendly, making it an excellent tool for both beginners and experienced professionals looking to automate the process of pulling real-time stock prices and other financial data.

# Overview
The yahoo_fin package is designed to simplify the extraction of financial data from Yahoo Finance. It provides a variety of functions to retrieve stock prices, historical data, financial statements, and more. This package is especially useful for those interested in financial analysis, algorithmic trading, and data-driven decision-making.

For detailed documentation on the yahoo_fin package, visit The Automatic.

# Features
Real-time Stock Prices: Fetch the latest stock prices with ease.
Historical Data: Retrieve historical stock prices for analysis.
Financial Statements: Access detailed financial statements of companies.
Market Data: Obtain data on market indices, sectors, and more.

# Installation
To install the yahoo_fin package, use pip:
pip install yahoo_fin

# Usage
Here is a basic example to get you started:

from yahoo_fin import stock_info as si

"Get the current price of a stock"

apple_price = si.get_live_price('AAPL')
print(f"Apple Inc. (AAPL) Current Price: ${apple_price:.2f}")

"Get historical data for a stock"

historical_data = si.get_data('AAPL', start_date='2020-01-01', end_date='2021-01-01')
print(historical_data)

"Retrieve financial statements"

income_statement = si.get_income_statement('AAPL')
print(income_statement)

