# Forecasting & Analysis
## Overview
This repository combines forecasting models for SNAP EBT produce incentive programs with trend analysis of Double Up Food Bucks (DUFB) data across Texas sites. Together, these efforts provide actionable insights for grant planning, program sustainability, and community impact evaluation.
- **Forecasting:** Projects incentive redemption costs under $5 and $10 cap scenarios using store‑level produce sales and transaction data.
- **Analysis:** Explores SNAP and Double Up program trends from 2020–2025, highlighting variability, adoption patterns, and correlations across sites and organization types.
## Why This Matters
- **Grant Planning:** Transparent projections of program costs for funders and stakeholders.
- **Program Sustainability:** Scenario modeling ($5 vs. $10 caps) to balance reach and budget.
- **Community Impact:** Identifies high‑need areas and program adoption trends.
- **Strategic Decisions:** Correlation and trend analysis to optimize outreach and incentive design.
## Key Findings
  - Moving Average, Exponential Smoothing; SMA and ARIMA delivered strongest performance in most stores under limited, stable data.
- **Limitations:**
  - Short 7-month dataset limits ability to detect long-term trends or seasonality.​
  - Monthly aggregation masks week-to-week sales fluctuations, reducing forecast responsiveness.
  - Seasonality is weak/inconsistent making seasonal models less reliable.​
  - External drivers like incentive surges or policy shifts are not explicitly captured in the dataset, limiting predictive power.
- **Recommendations:**
  - Extend data to 12–18 months to capture more stable patterns and validate model performance.​
  - Increase granularity (e.g., switch from monthly to weekly data) to better model short-term shifts.
  - Retain all four models (SMA, ARIMA, HES, Prophet) but prioritize based on store-specific performance and data behavior.
- ## Dataset
- https://github.com/SheaRendle/Forecasting/blob/main/Forecasting%20Data.png?raw=true
- ## Forecast
- 
