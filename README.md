# Quant Research Library

A structured quantitative finance research library implemented in Python, covering the full investment pipeline from interest rate modelling to portfolio construction.

The project integrates theory and implementation across fixed income, derivatives, credit risk, equity research, and portfolio optimization.

It is designed to reflect a **realistic institutional workflow**, not isolated academic models.

---

## Model Architecture & Workflow

The repository follows a complete financial modeling pipeline:

### 1. Interest Rate Term Structure & Short-Rate Models
Stochastic interest rate modelling using:
- Vasicek model
- Cox-Ingersoll-Ross (CIR) model

Focus:
- Mean reversion dynamics
- Term structure evolution
- Interest rate simulation

---

### 2. Fixed-Income Pricing and Risk Analytics
Bond pricing and yield curve construction under stochastic rates:

Focus:
- Zero-coupon bond pricing (CIR-based)
- Yield curve generation
- Interest rate sensitivity and discounting mechanics

---

### 3. SABR and Black-Scholes Derivatives Pricing
Options and volatility modelling framework:

Focus:
- Black-Scholes closed-form pricing
- SABR stochastic volatility model
- Volatility surface intuition and dynamics

---

### 4. Credit Risk Model and Creditworthiness Assessment
Fundamental credit analysis and default risk estimation:

Focus:
- Balance sheet-driven credit scoring
- Financial ratio analysis
- Probability-weighted credit quality assessment

---

### 5. Fundamental Equity Screener
Multi-factor equity research and valuation system:

Focus:
- Growth, valuation, and quality metrics
- ROIC / ROE-based analysis
- Sector-specific scoring (general equities + financials)
- Rule-based scoring system (0–100)

---

### 6. Multi-Method Portfolio Optimization Framework
Portfolio construction using multiple optimization paradigms:

Includes:
- Markowitz Mean-Variance Optimization
- Black-Litterman Model
- Hierarchical Risk Parity (HRP)

Focus:
- Risk-return optimization
- Market-implied equilibrium allocation
- Correlation-aware clustering
- Robust allocation under uncertainty

---

## Design Philosophy

This project is built around three principles:

### 1. Full Pipeline Thinking
Each model represents a stage in a real investment workflow:
**Rates → Pricing → Credit → Equity → Portfolio**

### 2. Practical Implementation
All models are implemented using real market data (`yfinance`) with reproducible Python code.

### 3. Interpretability
Every model is transparent, formula-driven, and designed for explainability rather than black-box prediction.

## Technologies used

- Python 3.x
- NumPy
- Pandas
- SciPy
- Matplotlib
- yFinance
- Jupyter Notebooks

## Repository Structure

```text
quant-research-toolkit/

├── 1_Interest_Rate_Term_Structure_&_Short_Rate_Models.ipynb
├── 2_Fixed_Income_Pricing_and_Risk_Analytics.ipynb
├── 3_SABR_and_BlackScholes_Derivatives_Pricing.ipynb
├── 4_Credit_Risk_Model_and_Creditworthiness_Assessment.ipynb
├── 5_Fundamental_Equity_Screener.ipynb
├── 6_Multi_Method_Portfolio_Optimization_Framework.ipynb

├── assets/
├── requirements.txt
└── README.md
---


