# AML Transaction Monitoring & Risk Analytics

## Project Overview
An end-to-end Anti-Money Laundering (AML) analytics project using a
synthetic transaction monitoring dataset. The goal is to explore
transaction patterns, develop risk-based detection rules, evaluate
machine learning approaches, and present findings through a dashboard.

## Objectives
- Explore transaction data and assess data quality.
- Analyze transaction amounts, payment methods, and transaction patterns.
- Develop explainable AML detection rules and generate alerts.
- Evaluate detection approaches using appropriate metrics for imbalanced data.
- Build data engineering and analytics workflows.
- Present key findings through Power BI.

## Technology Stack
- Python and Pandas
- SQL
- Snowflake
- Machine Learning
- Power BI
- Git and GitHub

## Dataset
Source: [Synthetic Transaction Monitoring Dataset AML on Kaggle](https://www.kaggle.com/datasets/berkanoztas/synthetic-transaction-monitoring-dataset-aml)

The dataset is synthetic and is not a collection of real customer banking records.
The original dataset is intentionally excluded from this repository because of its size.

## Current Progress
- [x] Inspected dataset dimensions and column names.
- [x] Checked missing values.
- [x] Examined laundering label distribution.
- [x] Summarized transaction amounts.
- [ ] Analyze payment types and transaction patterns.
- [ ] Develop AML detection rules.
- [ ] Build and evaluate machine learning models.
- [ ] Develop data engineering workflows.
- [ ] Build a Power BI dashboard.

## Repository Structure
- `01_data-exploration.ipynb` — initial dataset exploration.
- `.gitignore` — excludes datasets and local or temporary files.

## Disclaimer
This is an educational portfolio project. A transaction flagged by an
analytical rule or model is not proof of money laundering.
