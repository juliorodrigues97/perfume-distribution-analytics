# 🧴Perfume Distribution — Sales Analytics Dashboard

## Overview
An end-to-end sales analytics project covering the full pipeline from raw data generation to an interactive Power BI dashboard. It includes revenue tracking against target, a breakdown of YoY performance into volume vs. price/mix effects, RFM-based customer segmentation, and Pareto/ABC portfolio concentration analysis.

---

## Business Context
This project is based on real-world experience as an operations analyst at a perfume and cosmetics distribution company. Although it wasn't part of my formal role, I noticed the sales team's only performance-tracking tool was a spreadsheet with a "thermometer" chart per rep, comparing revenue to target — no historical trend, no drill-down, no way to see what was actually driving the numbers.

Since I was studying data analytics on the side, I saw an opportunity to build something more useful: a centralized dashboard covering not just revenue vs. target, but also YoY performance drivers, customer segmentation, and portfolio concentration — insights the team didn't have visibility into before.

---

## Data Note
The original company name, employees, customers, and financial figures have been fully anonymized — all data in this repository is synthetic, generated to mirror the structure, scale, and data quality challenges of the original production system (including realistic "dirty data" scenarios like inconsistent categorization, duplicate records, and missing values).

The goal of this project is to demonstrate the type of ETL, data cleaning, and business intelligence work performed in that role, translated into a US-market context (schema, currency, and terminology).

---

## Tech Stack
- **Python** (pandas) — synthetic data generation and cleaning pipeline
- **Power BI** (Power Query, DAX) — data modeling and dashboard

---

## Repository Structure

perfume-distribution-analytics/

├── data/
│ ├── raw/us/
│ └── processed/us/

├── notebooks/

├── dashboard/

└── assets/screenshots/

---

## Data Pipeline
Raw generation → Data quality validation → Cleaning & business rules → Power BI model

---

## Key Features
- Revenue vs. target tracking with MTD pace projection
- YoY revenue bridge (volume vs. price/mix decomposition)
- RFM customer segmentation
- ABC/Pareto portfolio analysis with cross-sell insights

---

## Screenshots
[imagens aqui]

---

## Setup
1. Set the `PRESTIGE_DATA_PATH` environment variable (or edit the path directly in the notebooks)
2. Run notebooks in numbered order
3. Open `dashboard/sales_performance_dashboard.pbix` and set the `DataPath` parameter to your local data folder

---

## Author
Julio Rodrigues - Data & Business Analyst
[LinkedIn](https://www.linkedin.com/in/julio-cesar-rodrigues/) | Portfolio | [GitHub](https://github.com/juliorodrigues97)

