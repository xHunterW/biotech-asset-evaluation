# Biotech Investment & Asset Evaluation

A curated collection of quantitative frameworks for evaluating pharmaceutical assets and investment opportunities. Each project applies rigorous financial modeling such as risk-adjusted NPV (rNPV), real options, and Monte Carlo simulations to real-world clinical and commercial data. This repository serves as a hub for bridging scientific diligence with investment-grade decision-making.

---

## Project Index

### Batoclimab (IMVT-1401) Valuation Case Study

This project implements a **Decision Quality (DQ) framework** to evaluate the hypothetical acquisition of Immunovant's Batoclimab for Myasthenia Gravis. The Python-based model utilizes **Monte Carlo simulations (n=10,000)** to generate a risk-adjusted Net Present Value (rNPV) distribution.

Key features include:
* **Probabilistic Modeling:** Uses Truncated Normal, Beta, and Triangular distributions to model uncertainty in regulatory timelines, clinical Probability of Success (PoS), and peak market penetration..
* **Variable Correlation:** Implements Gaussian Copulas to preserve realistic dependencies between pricing and gross-to-net discounts.
* **Sensitivity Analysis:** Includes Tornado plots and Spearman rank correlations to identify primary value drivers (e.g., patient population vs. WACC).
* **Outcome:** Established a fair value band of **$4.1B – $5.6B** with limited downside risk.

[**View Project Folder**](./batoclimab_valuation) 

---

### [Placeholder: Future Project Title]

*Coming Soon.* This section is reserved for upcoming analyses, such as comparative portfolio Sharpe ratio optimizations or competitive landscape assessments for next-generation assets.

---
