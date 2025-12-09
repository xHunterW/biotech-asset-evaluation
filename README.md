# Biotech Investment & Asset Evaluation

A curated collection of quantitative frameworks for evaluating pharmaceutical assets and investment opportunities. Each project applies rigorous financial modeling such as risk-adjusted NPV (rNPV), real options, and Monte Carlo simulations to real-world clinical and commercial data. This repository serves as a hub for bridging scientific diligence with investment-grade decision-making.

---

# Project Index

### Batoclimab (IMVT-1401) Valuation Case Study

This project implements a **Decision Quality (DQ) framework** to evaluate the hypothetical acquisition of Batoclimab for Myasthenia Gravis. The Python-based model utilizes **Monte Carlo simulations (n=10,000)** to generate a risk-adjusted Net Present Value (rNPV) distribution.

Key features include:
* [cite_start]**Probabilistic Modeling:** Uses Truncated Normal, Beta, and Triangular distributions to model uncertainty in regulatory timelines, clinical Probability of Success (PoS), and peak market penetration[cite: 304, 382, 387].
* [cite_start]**Variable Correlation:** Implements Gaussian Copulas to preserve realistic dependencies between pricing and gross-to-net discounts[cite: 322, 352].
* [cite_start]**Sensitivity Analysis:** Includes Tornado plots and Spearman rank correlations to identify primary value drivers (e.g., patient population vs. WACC)[cite: 168, 178].
* [cite_start]**Outcome:** Established a fair-value band of **$4.1B – $5.6B** with limited downside risk[cite: 151].

[**View Project Folder**](./batoclimab_valuation) | [**View Presentation**](./batoclimab_valuation/presentation.pdf)

---

### [Placeholder: Future Project Title]

*Coming Soon.* This section is reserved for upcoming analyses, such as comparative portfolio Sharpe ratio optimizations or competitive landscape assessments for next-generation assets.

---
