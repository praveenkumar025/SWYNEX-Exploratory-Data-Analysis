# SWYNEX-Exploratory-Data-Analysis

# SWYNEX - Task 2: Exploratory Data Analysis (EDA)

## Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) using SQL on the cleaned e-commerce retail dataset. The objective is to uncover underlying distribution patterns, seasonal trends, consumer purchasing behaviors, and high-value product categories to support business strategy.

## Key Statistical Findings
- **Order Sizes:** Analyzed central tendency and dispersion metrics (Mean, Median, Standard Deviation, and IQR) for `Quantity` and `UnitPrice`.
- **Seasonality:** Identified monthly sales velocity and hourly peak ordering times.
- **Pareto Concentration:** Evaluated customer lifetime order totals and SKU velocity.

## 5 Key Analytical Insights
1. **Dominant Domestic Footprint:** Over 85% of transactions and net sales originate within the United Kingdom.
2. **Right-Skewed Transaction Quantities:** Significant variance between median purchase size and high-volume wholesale outlier orders.
3. **Q4 Seasonal Demand:** Order volume peaks during October and November, aligning with holiday-driven retail behavior.
4. **Diurnal Mid-Day Concentration:** Highest order density occurs between 10:00 AM and 3:00 PM, peaking around lunch hour.
5. **Signature SKU Dependency:** A small cluster of top-performing SKUs (such as Regency Cakestands) drives the majority of the catalogue revenue.

## Files in This Repository
- `data_cleaning.sql`: Data ingestion and cleaning pipeline.
- `eda_online_retail.sql`: Analytical SQL queries for summary statistics, segmentation, and trends.
- `visualizations/`: Exported trend charts (Revenue by Month, Top Countries, Hourly Distribution).
