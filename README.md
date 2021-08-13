# Cryptocurrency Price Action versus Stock Market and Volatility Index
Project 1 for Rice University's FinTech Boot Camp

---

## Introduction:

### Project Description:

The purpose of this project is to determine correlations between the market as exemplified by the S&P 500 using SSgA Active Trust - S&P 500 ETF TRUST ETF (SPY), the volatility index (VIX), and the price of the cryptocurrencies to determine if there is a predictive behavior. We will analyze data of three top cryptocurrencies traded based on market popularity; these are Bitcoin, Ethereum, and Litecoin. The time frame of our analysis will be two years from July of 2019 through June of 2021. We will source this data from Alpaca, Quandl, and Coinbase using APIs.

### Project Objective:

We find the cryptocurrency market fascinating and want to analyze how the cyryptocurrency market correlates with the stock market and it's volatility. We could use this information to aid in determining trends that would be useful in designing an investement portfolio.

### Research Questions:

Do price movements of Bitcoin correspond with movements in the stock market and volatility index? If so, do movements in the price of Bitcoin  pre-date, align, or post-date movements in the the stock market and volatility index?

Do price movements of Ethereum correspond with movements in the stock market and volatility index? If so, do movements in the price of Ethereum  pre-date, align, or post-date movements in the stock market and volatility index?

Do price movements of Litecoin correspond with movements in the stock market and volatility index? If so, do movements in the price of Litecoin  pre-date, align, or post-date movements in the stock market and volatility index?

Based on the analysis of Bitcoin, Ethereum, and Litecoin, do movements in the price of the various cryptocurrencies in the market and the respective movements in the stock market and volatility index correlate with each other?

### Datasets to be Used:

Bitcoin price data from 2019-07-01 to 2021-07-01 using the Coinbase API.

Ethereum price data from 2019-07-01 to 2021-07-01 using the Coinbase API.

Litecoin price data from 2019-07-01 to 2021-07-01 using the Coinbase API.

SPY SSgA Active Trust - S&P 500 ETF TRUST ETF data from 2019-07-01 to 2021-07-01 using the Alpaca API.

VIX Volatility Index data from 2019-07-01 to 2021-07-01 using the Quandl API.

---

## Technologies

This project leverages python 3.7 with the following modules:

* [os](https://docs.python.org/3/library/os.html) - For providing a portable way of using operating system dependent functionality.

* [datetime](https://docs.python.org/3/library/datetime.html) - For supplying classes for manipulating dates and times.

* [hvplot](https://hvplot.holoviz.org) - For plotting in various formats working with a wide array of datatypes in the PyData ecosystem.

* [json](https://docs.python.org/3/library/json.html) - For data interchange.

* [requests](https://docs.python-requests.org/en/master/index.html) - For sending HTTP/1.1 requests.

* [pandas](https://github.com/pandas-dev/pandas) - For reading data into a DataFrame and analyzing data via statistics and plots.

* [dotenv](https://pypi.org/project/python-dotenv/) - For reading key-value pairs from a .env file and setting them as environment variables.

* [cbpro](https://pypi.org/project/cbpro/) - For collecting the necessary data on Bitcoin, Ethereum, and Litecoin.

* [alpaca_trade_api](https://alpaca.markets/docs/api-documentation/) - For collecting the necessary data on the SSgA Active Trust - S&P 500 ETF TRUST ETF (SPY).

* [csv](https://docs.python.org/3/library/csv.html) - For reading and writing tabular data in CSV (Comma Seperated Values) format.

* [pathlib](https://docs.python.org/3/library/pathlib.html) - For representing the file system path to a csv.

* [matplotlib](https://matplotlib.org/stable/users/index.html) - For embedding plots in the application.

---

## Installation Guide

Before running the application first install the following dependencies:

```python
  pip install pandas
  pip install hvplot
  pip install python-dotenv
  pip install cbpro
  pip install alpaca-trade-api
  pip install mkdocs
```

---

## Usage

To use the project analysis:

Clone the Cryptocurrency_Stock_Correlation repository from GitHub:

'git clone https://github.com/jpweldon/Cryptocurrency_Stock_Correlation.git'

Add an environment file to the Resources folder with your Quandl and Alpaca keys.

Open the Resources folder and then the Market_Data, Volatility_Data, and crypto_data Jupyter Lab notebooks within. Run the notebooks.

Examine the summary data, statistics, and analysis contained within the notebooks.

Open the Data_Exploration folder and data_exploration Jupyter Lab notebook within. Run the notebook.

Examine the statistics, charts, and analysis contained within the notebook.

Open the Data_Analysis folder and data_analysis Jupyter Lab notebook within. Run the notebook.

Examine the summary data, statistics, charts, and analysis contained within the notebook. We have included analysis outlining the significance.

---

## Contributors

Brienne DeMott

Email: brienne_demott@yahoo.com

[LinkedIn:] (https://www.linkedin.com/in/brienne-demott-203b94215/)

John P Weldon

Email: johnpweldon01@gmail.com

[LinkedIn:] (www.linkedin.com/in/john-weldon-333b0695)

Elliot Lozano

Email: elliotlozano95@gmail.com

Jose Medina

Email: medina.jose003@gmail.com

---

## License

MIT

---

