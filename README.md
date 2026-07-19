# COVID-19 Trends Dashboard (Jan–Mar 2021)

A Power BI dashboard analysing COVID-19 case, recovery, and death trends between January and March 2021, providing an interactive view of pandemic dynamics over time.

> **Note:** The original `.pbix` file is no longer available. This repo showcases the dashboard through a screenshot, along with a summary of the approach and key insights.

![COVID-19 Trends Dashboard](covid19-trends-dashboard.png)

---

## Project Objective

To analyse and visualise COVID-19 trends — confirmed cases, recoveries, and deaths — across a three-month period, enabling a clear view of how the pandemic progressed and identifying month-on-month shifts.

---

## Data Source

Publicly available COVID-19 dataset (Kaggle).

---

## Tools & Skills Used

| Stage | Tools |
|---|---|
| Data cleaning & transformation | Power Query |
| Data modelling | Power BI |
| Calculated metrics | DAX (KPI cards, monthly aggregations) |
| Dashboard development | Power BI Desktop |
| Interactivity | Date range filter/slicer |

---

## Dashboard Overview

- **Total Confirmed Cases:** 49K (15 Jan – 25 Mar 2021)
- **Monthly Confirmed Cases:** January 26K → February 15K → March 7K
- **Monthly Recoveries:** January 22K → February 7K → March 1K
- **Monthly Deaths:** January ~1,130 → February ~1,330 (peak) → March ~730
- **Interactive Filter:** Custom date range slider (15/01/2021 – 25/03/2021)

---

## Key Insights

- Confirmed cases fell sharply each month, from 26K in January to just 7K by March — a decline of roughly 73% over the period
- Deaths peaked in February (~1,330) despite cases already falling that month, before dropping sharply in March — reflecting a typical lag between case decline and death rate decline
- Recoveries dropped in line with confirmed cases, falling from 22K to 1K, consistent with fewer active cases needing to recover as the wave subsided

---

## Repo Contents

\```
├── README.md
└── covid19-trends-dashboard.png
\```

---

## About

Independent Power BI project — part of a self-directed portfolio built to strengthen data analytics and dashboard design skills. Completed **July–September 2025**.
