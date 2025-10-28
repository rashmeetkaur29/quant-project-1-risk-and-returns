# 📈 Quantitative Analysis of Risk & Return (2022–2025)

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)
![Status](https://img.shields.io/badge/Project%20Status-Active-brightgreen.svg)
![Data Source](https://img.shields.io/badge/Data%20Source-Yahoo%20Finance-yellow.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/rashmeetkaur29/quant-project-1-risk-and-returns)
![Repo Size](https://img.shields.io/github/languages/code-size/rashmeetkaur29/quant-project-1-risk-and-returns)
![GitHub issues](https://img.shields.io/github/issues/rashmeetkaur29/quant-project-1-risk-and-returns)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rashmeetkaur29/quant-project-1-risk-and-returns/blob/main/notebooks/stock_analysis.ipynb)


## 🧭 Project Overview
This project explores **risk vs return dynamics** across major U.S. sectors — technology, finance, and energy — using historical market data from 2022–2025.  
The goal is to visualize and quantify how volatility, returns, and correlations influence portfolio construction decisions.

---

## ⚙️ Tech Stack
- **Language:** Python 3  
- **Libraries:** pandas, numpy, yfinance, matplotlib, seaborn, jupyter  
- **Data Source:** Yahoo Finance (via yfinance API)

---

## 📊 Dataset
| Ticker | Company / ETF | Sector |
|:-------|:---------------|:--------|
| AAPL | Apple Inc. | Technology |
| MSFT | Microsoft Corp. | Technology |
| TSLA | Tesla Inc. | Consumer Discretionary |
| JPM | JPMorgan Chase & Co. | Financials |
| XLE | Energy Select Sector SPDR Fund | Energy |

---

## 📈 Rolling Volatility Analysis
![Rolling Volatility Plot](data/rolling_volatility.png)

- **TSLA** shows the highest volatility, reflecting aggressive growth dynamics.  
- **AAPL / MSFT** remain moderate and stable.  
- **JPM / XLE** exhibit defensive, low-volatility behavior.  
> *Volatility = Risk, but not necessarily = Loss.*

---

## 🔗 Correlation Heatmap
![Correlation Heatmap](data/correlation_heatmap.png)

- **AAPL–MSFT** = 0.64 → strong correlation within tech.  
- **JPM / XLE** show weak correlation with tech → better diversification.  
- **TSLA** ≈ 0.4 correlation → partial market independence.

---

## 📋 Quantitative Summary

| Asset | Annualized Return (%) | Annualized Volatility (%) | Key Insight |
|:------|:----------------------:|:--------------------------:|:-------------|
| **AAPL** | 14.40 | 29.05 | Steady large-cap growth |
| **MSFT** | 16.26 | 27.04 | Strong performer, moderate risk |
| **TSLA** | 21.56 | 62.51 | High-risk, high-reward growth |
| **JPM** | 22.24 | 25.07 | Strong returns with lower volatility |
| **XLE** | 18.39 | 26.25 | Consistent and defensive |

---

## 🧠 Insights
Diversification across sectors (Tech, Finance, Energy) delivers a **balanced portfolio** with high return potential and controlled volatility.  
> “Risk is not inherently bad; unmanaged risk is.”

---

## 📈 Risk Metrics: Sharpe Ratio & Beta (2022–2025)

| Asset | Sharpe Ratio | Beta (vs S&P 500) | Interpretation |
|:------|:-------------:|:-----------------:|:----------------|
| **JPM** | 0.740 | 0.903 | Strongest risk-adjusted performance with below-market volatility. |
| **MSFT** | 0.467 | 1.163 | Balanced growth; tracks market slightly above 1:1 sensitivity. |
| **AAPL** | 0.378 | 1.252 | Higher market exposure, consistent long-term growth. |
| **XLE** | 0.550 | 0.669 | Defensive sector ETF; stabilizes portfolio during drawdowns. |
| **TSLA** | 0.299 | 2.057 | High-risk, high-beta asset — momentum-driven growth exposure. |

### 🧩 Insight
- **Sharpe Ratio** quantifies return per unit of volatility → higher = more efficient use of risk.  
- **Beta** measures systematic risk vs. the market → higher = more sensitive to macro movements.  
Combining these helps identify **diversifiers (low β, decent Sharpe)** and **return drivers (high Sharpe, moderate β)** for better portfolio construction.

---

## 🚀 Next Steps
- Expand the analysis to a **10-asset portfolio**, incorporating cross-sector diversification.  
- Implement **portfolio optimization** using Modern Portfolio Theory (Markowitz Efficient Frontier).  
- Introduce **expected return forecasting** and **covariance matrix modeling** for smarter allocation.  
- Build an interactive **Streamlit dashboard** to visualize portfolio risk–return trade-offs dynamically.  

