# 🧴Perfume Distribution — Sales Analytics Dashboard

---

[![Watch Dashboard Demo](./assets/dashboard_demo_thumbnail.png)](assets/screenshots/dashboard_demo_thumbnail.png)](https://www.youtube.com/watch?v=Sy8Xe4zqbcw)

*Click the image above to watch a 1-minute walkthrough of the dashboard.*

---

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

## 📈 Dashboard Pages

### 1. Sales Performance
Tracks monthly revenue against target, with daily pace and month-end 
forecast. 

**Example insight (February 2024):** 
Revenue closed at $2.06M against a $2.01M target (102.8%), a $55.7K beat driven mostly by a strong final week — daily pace was behind target for 26 of the 29 days before catching up on day 29. Rep-level performance varied widely, from significantly under target to well over 2x goal, highlighting how much individual variance the monthly total can mask.

### 2. Revenue Bridge
Breaks down YoY revenue change into volume and price/mix effects, 
ranked by rep, customer, and brand. *Example insight: "..."*

---

## Repository Structure

perfume-distribution-analytics/

├── `data/` # Raw and cleaned datasets (Aug 2021 – Feb 2024)

├── `notebooks/` # Data cleaning scripts (Python)

├── `assets/` Dashboard screenshots

├── `dashboard/` # Power BI dashboard files (.pbix)

├── `README.md` # Project documentation (this file)

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

| Sales Performance | Revenue Bridge |
|---|---|
| ![Sales Performance](assets/screenshots/page1_sales_performance.png) | ![Revenue Bridge](assets/screenshots/page2_revenue_bridge.png) |

| RFM Segmentation | Pareto/ABC |
|---|---|
| ![RFM](assets/screenshots/page3_rfm_segmentation.png) | ![Pareto](assets/screenshots/page4_pareto_abc.png) |

| Account Detail | Contribution Detail |
|---|---|
| ![Account Detail](assets/screenshots/account_detail.png) | ![Contribution Detail](assets/screenshots/contribution_detail.png) |

| Cross-Sell Analysis |
|---|
| ![Cross-Sell](assets/screenshots/cross_sell_analysis.png) | 

---

## Setup
1. Set the `PRESTIGE_DATA_PATH` environment variable (or edit the path directly in the notebooks)
2. Run notebooks in numbered order
3. Open `dashboard/sales_performance_dashboard.pbix` and set the `DataPath` parameter to your local data folder

---

## Author
Julio Rodrigues - Data Analyst  
[LinkedIn](https://www.linkedin.com/in/julio-cesar-rodrigues/) | Portfolio | [GitHub](https://github.com/juliorodrigues97)
