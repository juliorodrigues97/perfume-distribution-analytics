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


