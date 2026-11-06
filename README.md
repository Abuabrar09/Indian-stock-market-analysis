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
1. **Best return:** ICICI Bank grew **16.2% per year**
2. **Best risk-adjusted return:** ICICI Bank had the highest Sharpe ratio (**0.49**)
3. **Riskiest stock:** Infosys had the highest volatility (**26.3%**)
4. **Deepest fall:** TCS dropped **53.4%** from its peak at the worst point
5. **Beat the Nifty 50:** ICICI Bank was the **only stock** to outperform the index (6.9% per year)
6. **Best diversification pair:** ICICI Bank + TCS (correlation **0.23**)

## 📝 Conclusion
ICICI Bank was the clear winner, combining the highest return with the best risk-adjusted performance. The IT stocks (Infosys and TCS) carried more risk without beating the index. Pairing a bank stock with an IT stock offers the strongest diversification, because they move largely independently of each other.

## 🧰 Tools
Python · pandas · NumPy · matplotlib · seaborn · yfinance · Google Colab

## ▶️ How to Run
Click the **Open in Colab** button above, then **Runtime → Run all**.

---
*This is an educational analysis, not investment advice.*
