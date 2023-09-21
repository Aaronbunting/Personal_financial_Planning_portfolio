# Personal_financial_Planning_portfolio

# Personal Finance Planner

## Overview

This Python script helps users visualize their savings and investments to make better financial decisions. The application fetches current cryptocurrency prices and stock prices, calculates the value of the user's holdings, and runs a Monte Carlo simulation to project the value of the user's stock and bond investments over 30 years.

## Dependencies

Make sure you have the following dependencies installed:

- pandas
- os
- requests
- dotenv
- alpaca_trade_api
- MCForecastTools

## Getting Started

1. Clone this repository to your local machine.

2. Install the required dependencies using pip:


3. Create a `.env` file in the root directory of the project with the following variables:


4. Update the following variables in the script (`personal_finance_planner.py`) with your current assets and investments:

- `my_btc`
- `my_eth`
- `my_agg`
- `my_spy`
- `monthly_income`

## Usage

Run the script:


The script will display the following information:

- The current value of your cryptocurrency and stock holdings.
- A pie chart showing the composition of your savings.
- Information about your emergency fund.
- A Monte Carlo simulation for forecasting the cumulative returns of a 60% stocks (SPY) and 40% bonds (AGG) portfolio over the next 30 years.

## Output

The script generates the following outputs:

- The current value of your cryptocurrency and stock holdings.
- A pie chart showing the composition of your savings.
- Information about your emergency fund.
- A line plot of 500 simulated cumulative return paths for a 60% stocks (SPY) and 40% bonds (AGG) portfolio over the next 30 years.
- A histogram plot of the distribution of cumulative returns.
- A range of possible outcomes for an initial investment of $20,000 and $30,000 over the next 30 years, with a 95% confidence interval.

## Disclaimer

**Disclaimer:** This script is for informational purposes only and should not be considered financial advice. The results of the Monte Carlo simulation are based on historical data and should not be considered indicative of future performance. Always consult a financial advisor before making investment decisions.

---

*Note: Insert any additional information or screenshots as needed to provide clarity and context to your users.*


