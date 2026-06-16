# Saudi Arabia Consumer Goods Price Trends (2009-2026)

## Overview

A personal data analysis portfolio project studying price movements of around 170 consumer goods in Saudi Arabia (mainly food items) over more than 17 years, using official monthly data published by the General Authority for Statistics (GASTAT).

## Project Goals

- Explore inflation trends at both the individual item and category level (grains, meat, dairy, fruits and vegetables, etc.).
- Identify the most volatile versus the most stable goods over time.
- Detect recurring seasonal patterns in certain items (especially fruits and vegetables).
- Examine the impact of major economic events (such as the 2020 pandemic) on price trajectories.
- Build a clean, reusable dataset and present findings through clear visualizations and reports.

## Data Source

**Average Prices in the Kingdom** — GASTAT, monthly data from January 2009 to May 2026, covering around 170 consumer items classified under the international COICOP system.

> Data is sourced from official public records (stats.gov.sa) and contains no personal or sensitive information.

## Project Plan

1. **Cleaning & Preparation**: Reshape the table from wide to long format for analysis, and handle missing values.
2. **Exploratory Data Analysis (EDA)**: Descriptive statistics, distributions, and overall trends per category.
3. **In-depth Analysis**: Measuring volatility, annual/monthly rates of change, seasonality, and key turning points.
4. **Visualization**: Interactive and static charts highlighting key findings.
5. **Documentation & Presentation**: A final report or dashboard summarizing results for portfolio presentation.

## Repository Structure

```
saudi-consumer-price-trends/
├── README.md
├── data/
│   ├── raw/         ← original file from GASTAT (xlsx)
│   └── processed/   ← cleaned long-format dataset (csv)
├── notebooks/        ← analysis code
└── visuals/          ← final charts and figures
```

`data/processed/consumer_goods_prices_long.csv` contains 33,946 rows with columns: `item_code`, `item_name_ar`, `unit`, `year`, `month`, `price`.

## Tools Used

Python (pandas, matplotlib/seaborn), Excel, and possibly Power BI or an interactive dashboard for the final presentation.

## Project Status

🚧 In progress — Started: June 2026.

## License & Data Source

Data is publicly available from the General Authority for Statistics of Saudi Arabia (stats.gov.sa) and licensed for research and analytical use.
