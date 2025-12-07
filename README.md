# 🔗 Statistical Arbitrage — Cointegration Pairs Trading (NSE)

This project implements a **market-neutral stat-arb trading strategy** based on **cointegration** between two highly correlated banking sector stocks in India:
- HDFCBANK.NS
- KOTAKBANK.NS

The strategy identifies mean-reverting price spreads and executes trades when the spread deviates significantly from its long-term equilibrium.

---

## 📌 Key Concepts

| Technique | Purpose |
|---------|---------|
| Cointegration Test (Engle-Granger) | Detect long-term equilibrium relationship |
| OLS Regression | Calculate hedge ratio |
| Z-Score Signals | Identify trade entry/exit |
| Cumulative P&L | Evaluate strategy profitability |

---

## 📊 Performance Highlights

| Metric | Value |
|------|------|
| Cointegration p-value | 0.1422 |
| Final P&L | **528.34** |
| Market Exposure | Market-neutral (hedged) |

---

## 📈 Visual Results

Add your screenshots here:

- Spread Z-Score with signal bands  
- Cumulative P&L (mean reversion profits)  

Example 👇  
📌 Pairs Trading Performance  
📌 Z-Score Signal Chart  

---


---

## 🛠️ Tech Stack

Python, pandas, numpy, statsmodels, matplotlib, yfinance

---

## 🚀 Possible Enhancements

- Better entry/exit threshold optimisation
- Stop-loss & dynamic hedge rebalancing
- Multi-pair scanning & ranking
- Johansen cointegration for baskets

---

## 👨‍💻 Author
Rugved Shete  
Aspiring Quant / HFT Analyst  
📍 Pune, India

⭐ If you liked this repo — please give it a star!


## 📁 Files
