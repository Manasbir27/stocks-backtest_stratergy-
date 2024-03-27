This repository contains a robust backtesting framework designed to evaluate the performance of an options trading strategy focused on the Bank Nifty Index. The strategy employed involves selling out-of-the-money straddles (a combination of call and put options) and managing the trades based on predefined risk management rules.

# Key Features

- Data Preprocessing: The code handles data cleaning, sorting, and formatting to ensure accurate calculations.
- Strike Price Identification: Utilizes an efficient algorithm to determine the at-the-money (ATM) strike price based on the underlying futures price.
- Option Premium Calculation: Computes the premiums received from selling the ATM call, ATM put, out-of-the-money (OTM) call, and OTM put options.
- Risk Management: Implements stop-loss and profit target levels based on the collected premiums to manage trade risk.
- Trade Execution: Simulates the entry, monitoring, and exit of trades according to the predefined rules.
- Performance Evaluation: Calculates a comprehensive set of performance metrics, including return on investment (ROI), win rate, maximum drawdown, Calmar ratio, and various other statistics.
- Visualization: Generates insightful plots for the equity curve and drawdown to facilitate strategy analysis.

# Getting Started

To run the backtesting framework, follow these steps:
1. Install the required Python packages: `pandas`, `numpy`, and `matplotlib`.
2. Obtain the historical data for Bank Nifty futures and options for the desired period.
3. Update the file paths in the code to point to your data files.
4. Execute the script, and the results will be printed to the console, accompanied by the equity curve and drawdown plots.

# Results

The script will output the following key performance statistics:
- Return on Investment (ROI)
- Win Rate
- Maximum Drawdown
- Capital
- Total Trades
- Profitable Trades
- Losing Trades
- Hit Ratio
- Risk Reward Ratio
- Calmar Ratio
- Average Return per Trade
- Average Profit per Trade
- Average Loss per Trade
- Maximum Profit per Trade
- Maximum Loss per Trade
- Average Return per Month
- Average Return per Year
- Total Return
- Compound Annual Growth Rate (CAGR)

by Manasbir Singh Bhatia 

