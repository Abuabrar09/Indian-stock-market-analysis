# 📈 Indian Stock Market Analysis — Nifty Leaders

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Abuabrar09/Indian-stock-market-analysis/blob/main/Stock_Market_Analysis.ipynb)

**Author:** Abrar Ahmed Syed — Business & Financial Data Analyst | AI

## 🎯 Problem
An investor wants to compare five of India's largest companies: which delivered the best returns, which carried the most risk, and how closely do they move together?

## 📊 Data
- **Source:** Yahoo Finance (via the `yfinance` Python library)
- **Period:** 5 years of daily closing prices
- **Stocks:** Reliance, TCS, HDFC Bank, Infosys, ICICI Bank
- **Benchmark:** Nifty 50 index

## 🛠️ Approach
1. Downloaded and cleaned 5 years of price data (handled missing values from market holidays)
2. Rebased prices to ₹100 to compare growth fairly
3. Calculated **CAGR, volatility, Sharpe ratio and maximum drawdown**
4. Identified trends using **50-day and 200-day moving averages** (golden cross / death cross)
5. Measured **correlation** between stocks to assess diversification

## 💡 Key Insights
1. **Best return:** [STOCK] grew [X]% per year
2. **Best risk-adjusted return:** [STOCK] had the highest Sharpe ratio ([X])
3. **Riskiest stock:** [STOCK] had the highest volatility ([X]%)
4. **Deepest fall:** [STOCK] dropped [X]% from its peak at the worst point
5. **Beat the Nifty 50:** [STOCKS] outperformed the index ([X]% per year)
6. **Best diversification pair:** [STOCK] + [STOCK] (correlation [X])

## 🧰 Tools
Python · pandas · NumPy · matplotlib · seaborn · yfinance · Google Colab

## ▶️ How to Run
Click the **Open in Colab** button above, then **Runtime → Run all**.

---
*This is an educational analysis, not investment advice.*
