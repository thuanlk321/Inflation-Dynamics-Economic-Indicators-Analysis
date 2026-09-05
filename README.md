# Economic Indicators' Effect on the Inflation Rate

**Author:** Thuan Van Le  
**Period Covered:** 2010–2023  

---

## Project Overview

This project examines how key macroeconomic indicators interact with inflation over time. Using World Bank data, the analysis focuses on the relationships between:

- **Inflation (CPI %)**
- **Real Interest Rate (%)**
- **Unemployment Rate (%)**
- **GDP Growth (% Annual)**

The study concentrates primarily on the **United States** and **Canada**, covering the post-financial crisis expansion, the COVID-19 shock (2020), and the subsequent inflation surge (2021–2022).

---

## Research Questions

- Do unemployment and inflation move in opposite directions (as suggested by the Phillips Curve)?
- Does stronger GDP growth tend to coincide with higher inflation?
- How do real interest rates respond to changes in inflation?
- How did the COVID-19 pandemic temporarily disrupt these relationships?

---

## Dataset

**Source:** [Global Economic Indicators (2010–2025) – World Bank](https://www.kaggle.com/datasets/tanishksharma9905/global-economic-indicators-20102025)

Key variables used:
- Inflation (CPI %)
- Unemployment Rate (%)
- Interest Rate (Real, %)
- GDP Growth (% Annual)

Analysis window: **2010–2023** (2024–2025 data are incomplete for many countries).

---

## Methodology

1. Load and clean the World Bank panel dataset
2. Compute country-level average indicators
3. Perform time-series visual analysis for the United States and Canada
4. Examine co-movements between inflation and the other three indicators
5. Highlight structural breaks around the COVID-19 period

---

## Key Findings

- **Unemployment ↔ Inflation:** Outside the pandemic period, the two series generally move in opposite directions, consistent with a short-run Phillips Curve relationship.
- **GDP Growth ↔ Inflation:** Strong growth episodes (especially the 2021 rebound) are associated with higher inflation, pointing to demand-side pressure.
- **Real Interest Rates:** Remained low through most of the 2010s and only turned more positive after the 2021–22 inflation surge, illustrating policy lags.
- **COVID-19 Shock:** Produced a classic demand-shock pattern (collapsing growth, rising unemployment, low inflation), followed by a sharp inflation overshoot during the recovery.

---

## Project Structure
