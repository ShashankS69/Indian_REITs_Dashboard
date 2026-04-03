# 📊 Indian REITs Comparative Investment Dashboard

### Institutional-Grade Analysis of Embassy, Mindspace, and Brookfield REITs

This repository presents a **data-driven investment dashboard** for the Indian Real Estate Investment Trust (REIT) sector, combining **Excel-based financial modeling** with **Python-powered risk-return analytics** to generate actionable insights.

---

## 📊 Project Overview

The **India Realty & Capital Brief** is designed to evaluate the performance of India’s three listed office REITs:

* Embassy Office Parks REIT
* Mindspace Business Parks REIT
* Brookfield India Real Estate Trust

Analysis is based on **Q3 FY2026 (Dec 31, 2025)** and extends beyond price tracking to incorporate institutional metrics such as:

* **Net Asset Value (NAV)**
* **Funds From Operations (FFO)**
* **Risk-Adjusted Returns (Sharpe Ratio)**
---

## 🧠 Analytical Framework

### 1. Valuation & Market Positioning

* CMP vs NAV → Identifying premium/discount opportunities
* 52-week range positioning

### 2. Portfolio Quality

* Gross leasable area comparison
* WALE (Weighted Average Lease Expiry)
* Occupancy trends

### 3. Risk-Return Modeling

* Annualized returns & volatility
* Sharpe Ratio vs **10Y G-Sec (risk-free rate)**
* Correlation across REITs

---

## 🚀 Technical Stack

**Excel (Primary Layer):**

* Comparative dashboard
* Financial modeling
* Capital structure tracking

**Python (Analytical Layer):**

* `yfinance` → NSE price data
* `pandas`, `numpy` → return & volatility calculations
* `matplotlib`, `seaborn` → visualization

---

## 📈 Key Insights (Q3 FY2026)

### 🟢 Efficiency Leader — Mindspace REIT

* **Sharpe Ratio:** 0.53 (highest in sector)
* **Occupancy:** 94.5%
* **LTV:** 24.9% → strongest balance sheet

👉 Best **risk-adjusted performer**

---

### 🟡 Value Opportunity — Brookfield REIT

* Trading at **~4.75% discount to NAV**
* Higher leverage (**35.4% LTV**)

👉 Attractive for **yield + valuation upside**

---

### 🔵 Macro Overlay — Yield Dynamics

* Compared REIT performance vs **10Y G-Sec (~6.5%)**
* Yield spread indicates **potential sector re-rating**

---

## 📂 Repository Structure

```bash
Indian_REITs_Dashboard/
│
├── reits_dashboard.ipynb        # Python analysis & modeling
├── README.md                   # Project documentation
└── relevant_data/              # (excluded from repo via .gitignore)
```

---

## 🛠️ How to Use

### 1. Financial Dashboard

Use the Excel model to explore:

* Relative valuation
* Capital structure
* Portfolio metrics

### 2. Python Analysis

Run the notebook to:

* Recalculate returns & volatility
* Modify tickers or time horizon
* Generate updated visualizations

---

## 📌 Key Value Proposition

This project demonstrates:

* Financial modeling capability (Excel)
* Quantitative analysis (Python)
* Ability to translate data → investment insights
---

## ⚠️ Disclaimer

This project is for educational and analytical purposes only and does not constitute financial advice.
