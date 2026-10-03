# Travel Cost Optimization & Expense Analytics

## Overview

An end-to-end data analytics project focused on analyzing travel and expense transactions to identify spending patterns, anomalous transactions, employee travel behavior, and potential cost-optimization opportunities.

The project demonstrates a complete analytics workflow using **SQL, Python, Pandas, Scikit-learn, and Power BI**.

> **Note:** All data included in this repository is synthetic and created for demonstration purposes. No confidential company or employee data is included.

---

## Business Objectives

- Analyze travel and expense spending patterns
- Identify major cost drivers across departments and categories
- Detect anomalous and potentially erroneous transactions
- Analyze the impact of booking lead time on airfare spending
- Segment employees based on travel-spending behavior
- Identify potential travel-cost optimization opportunities
- Build datasets suitable for Power BI reporting

---

## Technology Stack

| Technology | Purpose |
|---|---|
| SQL | Data cleaning, aggregation, trend analysis, anomaly analysis |
| Python | Data processing and analytical pipeline |
| Pandas | Data cleaning, transformation and aggregation |
| NumPy | Numerical operations and synthetic data generation |
| Scikit-learn | K-Means clustering and feature scaling |
| Power BI | Interactive dashboards and KPI reporting |
| Git/GitHub | Version control and project documentation |

---

## Project Workflow

```text
Synthetic Expense Data
        ↓
SQL Data Cleaning
        ↓
Data Validation
        ↓
EDA & Statistical Analysis
        ↓
Anomaly Detection
        ↓
Feature Engineering
        ↓
K-Means Employee Segmentation
        ↓
Savings Scenario Analysis
        ↓
Power BI Dashboard
```

---

## SQL Analysis

The SQL layer includes:

- Duplicate detection using `ROW_NUMBER()`
- Missing-value handling using `COALESCE()`
- CTE-based data cleaning
- Window functions using `LAG()`
- Month-over-Month expense analysis
- Department and category-level aggregation
- Booking lead-time analysis using `CASE`
- Employee-level feature engineering
- Robust statistical anomaly detection
- Travel-cost savings scenarios

---

## Python Analysis

The Python pipeline performs:

1. Synthetic transaction-data generation
2. Data cleaning and validation
3. Duplicate removal
4. Missing-value handling
5. Negative-value correction
6. Exploratory data analysis
7. Robust Z-score anomaly detection
8. Employee-level feature engineering
9. Feature scaling
10. K-Means clustering
11. Silhouette-score evaluation
12. Employee behavioral segmentation
13. Savings scenario analysis
14. Export of dashboard-ready datasets

---

## Employee Segmentation

Employee-level features include:

- Total spend
- Number of trips
- Spend per trip
- Average airfare booking lead time
- Out-of-policy expense rate

K-Means clustering is used to identify groups of employees with similar travel-spending behavior.

---

## Power BI Dashboard

The exported datasets can be used to build dashboards covering:

- Total travel spend
- Monthly spending trends
- Department-level spending
- Category-level spending
- Average transaction value
- Booking lead-time analysis
- Out-of-policy expense rate
- Anomaly transactions
- Employee travel segments

---

## Repository Structure

```text
travel-cost-optimization-analytics/
│
├── data/
├── sql/
├── python/
├── notebooks/
├── outputs/
├── powerbi/
├── screenshots/
└── README.md
```

---

## Disclaimer

This project is a portfolio demonstration. The dataset is synthetic and does not contain confidential information from any organization.
