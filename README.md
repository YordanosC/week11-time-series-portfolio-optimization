# Week 11 Challenge: Task 1 - Preprocessing and Exploring Financial Data

This repository contains the code and supporting files for Task 1 of the Week 11 Challenge for 10 Academy: Artificial Intelligence Mastery. The task focuses on preprocessing and exploring historical financial data for Tesla (TSLA), Vanguard Total Bond Market ETF (BND), and S&P 500 ETF (SPY).

Installation
To run this project, ensure you have Python 3.x installed along with the following libraries:

- yfinance
- pandas
- matplotlib
- statsmodels
  You can install these dependencies using pip with the following command:#

`pip install yfinance pandas matplotlib statsmodels`

Usage
Follow these steps to set up and run the project:

Clone the repository to your local machine:
`
git clone https://github.com/alebachew424/yourrepo.git`
Navigate to the project directory:
`
cd TSFPMO`
Run the jupiter notebook cell one by one:

Fetches historical financial data from Yahoo Finance (yfinance) for TSLA, BND, and SPY, covering the period from January 1, 2015, to the latest available date.
Cleans the data to handle missing values or inconsistencies.
Conducts exploratory data analysis (EDA) to uncover trends and patterns.
Generates visualizations saved in the output folder.

## Data

The dataset includes daily price metrics for TSLA, BND, and SPY, specifically:

- Open
- High
- Low
- Close
- Adjusted Close
- Trading Volume
  Data is sourced from Yahoo Finance via the yfinance library.

## Plots

The project generates several plots to visualize the data, including:

Closing Prices Over Time: Tracks the daily closing prices of each asset.
Daily Percentage Changes: Shows the day-to-day percentage changes in prices.
Rolling Means and Standard Deviations: Highlights trends and volatility using rolling statistics.
Time Series Decomposition: Breaks down the time series into trend, seasonality, and residual components.
