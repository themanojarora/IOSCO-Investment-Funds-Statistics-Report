# IOSCO Investment Funds Statistics Reports (ISFR) — Data Science Project

This project explores and analyzes the **Investment Funds Statistics Reports (ISFR)** published annually by the **International Organization of Securities Commissions (IOSCO)**. These reports aim to improve global understanding of systemic risk in investment funds by collecting standardized data from national regulators across jurisdictions.

---

## 🌍 What is ISFR?

The **Investment Funds Statistics Reports (ISFR)** are a series of statistical publications developed by IOSCO to provide a **global, data-driven view** of investment funds' activities, exposures, leverage, and liquidity characteristics.

Each ISFR compiles aggregated and jurisdiction-level data from securities regulators and supervisors, helping regulators monitor systemic risk arising from collective investment schemes. The reports are based on a **standardized template**, ensuring **comparability across regions and time**.

---

## 🧾 What Do the Reports Contain?

Each ISFR covers three broad types of investment funds:

### 1. **Qualified Hedge Funds (QHFs)**
- Use of synthetic and financial leverage
- Derivatives exposures (FX, IR, etc.)
- Counterparty and collateral details
- Asset class breakdown (equities, bonds, etc.)
- Redemption and portfolio liquidity metrics

### 2. **Open-Ended Funds (OEFs)**
- Fund strategies (equity, fixed income, mixed, etc.)
- Use of financial leverage and derivatives
- NAV by jurisdiction and asset class
- Liquidity of portfolios vs. investor redemption terms

### 3. **Closed-Ended Funds (CEFs)**
- Focus on real assets (real estate, private equity)
- Leverage and derivative usage (typically minimal)
- Jurisdictional breakdown of NAV
- Long-term liquidity and risk exposures

---

## 📆 Reports Used in This Project

| Edition | Data Year Covered | Notable Enhancements |
|--------|-------------------|-----------------------|
| **ISFR 2022** | 2020 | Baseline edition; heavy on hedge fund detail |
| **ISFR 2023** | 2021 | Expanded jurisdictional coverage (45 jurisdictions), deeper OEF/CEF analysis |
| **ISFR 2024** | 2022 | More granular repo, derivatives clearing, and liquidity analytics |

---

## 🎯 Project Aim

This project will extract, standardize, and analyze multi-year ISFR data to:
- Understand leverage trends (gross, synthetic, financial)
- Compare asset allocation and exposure risk across fund types
- Visualize jurisdiction-wise concentrations of systemic risk
- Provide regulatory insights into trends that may impact financial stability

The project is particularly suited for regulators, economists, and financial system risk analysts.

---

## 🧠 Outcome

The final output will be a **Jupyter Notebook** that:
- Loads and cleans data extracted from ISFR PDFs
- Visualizes key metrics and trends
- Highlights anomalies or shifts in risk patterns
- Suggests policy-relevant takeaways based on empirical analysis

