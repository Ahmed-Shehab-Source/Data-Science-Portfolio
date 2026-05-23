# 👥 Customer Churn Analysis & Retention Strategy

## 📌 Project Overview
This project targets structural customer churn by analyzing multi-source enterprise datasets, including raw transaction records, customer care history, and live session activity logs. The ultimate objective is to pinpoint exactly why users drop off and build data-driven retention strategies to preserve monthly recurring revenue (MRR).

## ⚡ Core Insights & Engineering Deliverables
* **Tiered Churn Discrepancy:** Advanced exploratory data analysis uncovered an alarming 41% user churn rate within free-tier accounts, compared to a stable ~23% drop-off within paid premium tiers.
* **KPI Engineering:** Formulated and benchmarked a leading indicator metric labeled **"30-Day Zero-Activity Rate"**. This behavioral feature identifies early-stage platform abandonment trends before financial account closure takes place.
* **Root Cause Validation:** Multivariate correlation analyses confirmed that low interaction frequency, rather than customer support ticket volume, acts as the primary systemic indicator of churn.

## 📂 Execution Path
1. Run `pip install -r requirements.txt` to align execution dependencies.
2. Open and execute `customer_churn_analytics.ipynb` within your Jupyter environment to run the data manipulation steps and visualize the churn curves.
