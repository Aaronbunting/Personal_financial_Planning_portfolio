# Personal_financial_Planning_portfolio

# Personal Finance Planner

## Overview

This Python script serves as a tool to assist users in gaining insights into their financial assets, thereby aiding them in making informed financial choices. It accomplishes this by retrieving real-time data on cryptocurrency and stock prices, performing calculations to determine the current value of the user's assets, and conducting a Monte Carlo simulation to forecast the potential growth of their stock and bond investments over a 30-year period.

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

- The present valuation of their cryptocurrency and stock assets.
- An illustrative pie chart that visually represents the breakdown of their savings.
- Insights regarding their emergency fund.
- A Monte Carlo simulation that offers predictions for the cumulative returns of a portfolio consisting of 60% stocks (SPY) and 40% bonds (AGG) over the upcoming three decades.

## Output

The script generates the following outputs:

- Asset Valuation: It displays the current worth of your cryptocurrency and stock holdings.

- Savings Composition: A visual representation in the form of a pie chart that breaks down the makeup of your savings, offering insights into the distribution of your assets.

- Emergency Fund Insights: Information and details about your emergency fund, helping you assess your financial preparedness for unforeseen expenses.

- Monte Carlo Simulation: It generates a line plot illustrating 500 simulated cumulative return paths for a diversified portfolio consisting of 60% stocks (SPY) and 40% bonds (AGG) over the next 30 years. This helps you visualize potential investment growth scenarios.

- Risk Analysis: A histogram plot is included to depict the distribution of cumulative returns, giving you an overview of the range of possible outcomes and the associated risks.

- Investment Projections: It provides a range of possible outcomes for an initial investment of both $20,000 and $30,000 over the course of the next 30 years, complete with a 95% confidence interval. This information aids in assessing the potential long-term performance of your investments under varying starting conditions.

- ![image](https://github.com/Aaronbunting/Personal_financial_Planning_portfolio/assets/128101698/c9b71994-b399-4c08-b7e9-a51a1af1b836)


## Disclaimer

**Disclaimer:** This script is for informational purposes only and should not be considered financial advice. The results of the Monte Carlo simulation are based on historical data and should not be considered indicative of future performance. Always consult a financial advisor before making investment decisions.

*Note: Insert any additional information or screenshots as needed to provide clarity and context to your users.*


