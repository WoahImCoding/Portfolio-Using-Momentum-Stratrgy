📈 Momentum Trading Strategy - Backtesting & Performance Analysis

🔥 Overview

This project implements a Momentum Trading Strategy and evaluates its performance against a benchmark (NIFTY 50). The backtesting framework analyzes various momentum strategies based on different lookback periods, stock selection criteria, and rebalancing frequencies.

📊 Strategy Breakdown

Stock Selection: Picks the top-performing stocks based on past momentum (returns over a lookback period).

Rebalancing: Adjusts portfolio holdings periodically (e.g., monthly, quarterly).

Performance Metrics: Compares against a benchmark using Sharpe Ratio, CAGR, Maximum Drawdown, and more.

🚀 Features

Backtests multiple momentum strategies

Compares performance against the NIFTY 50 index

Computes risk-adjusted returns (Sharpe Ratio, Max Drawdown, CAGR, Win Rate)

Visualization of cumulative returns

📌 Installation & Setup

Clone the repository:

git clone https://github.com/yourusername/momentum-strategy.git
cd momentum-strategy

Install dependencies:

pip install -r requirements.txt

Run the backtesting script:

python backtest.py

📈 Example Visualization

The following plot shows a comparison of Momentum Strategy vs. NIFTY 50 benchmark:



🔎 Performance Metrics

For each strategy, key performance indicators (KPIs) include:

Sharpe Ratio: Measures risk-adjusted returns.

Maximum Drawdown: Indicates the worst portfolio loss from peak to trough.
