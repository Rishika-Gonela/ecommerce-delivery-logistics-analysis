# E-Commerce Delivery & Logistics Performance Analysis

**An End-to-End Data Analytics Project | Python | Power BI**

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)](https://powerbi.microsoft.com/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)](https://pandas.pydata.org/)
[![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-orange?logo=googlecolab)](https://colab.research.google.com/)

## Project Overview

This project focuses on analysing e-commerce delivery and logistics performance using the Brazilian Olist e-commerce dataset.

The analysis explores delivery timelines, late deliveries, cancellations, product categories, seller performance and customer review scores to identify operational patterns and generate meaningful business insights.

The project uses Python for data preparation and exploratory analysis and Power BI for interactive data visualization.

## Project Objectives

- Audit and prepare the dataset for analysis.
- Perform exploratory data analysis (EDA).
- Calculate important delivery performance KPIs.
- Identify patterns in delayed deliveries.
- Analyse delivery performance across product categories and sellers.
- Compare customer review scores for late and on-time deliveries.
- Develop a Power BI dashboard.
- Provide actionable business recommendations.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Google Colab | Notebook execution |
| Power BI | Interactive dashboard |
| GitHub | Project documentation and version control |

## Dataset

The project uses the publicly available Brazilian E-Commerce Public Dataset by Olist.

The dataset contains e-commerce order information, including purchase timestamps, delivery timestamps, estimated delivery dates, order status, product categories, sellers and customer reviews.

**Data limitation:** The available data does not provide a usable carrier identifier or direct delivery-distance measure for this analysis.

## Project Workflow

### Week 1 – Data Quality Audit & EDA
- Loaded and inspected the dataset.
- Checked dataset dimensions and data types.
- Identified duplicate records and missing values.
- Examined important order and delivery fields.
- Documented data quality issues.

### Week 2 – KPI Engineering & Delivery Analysis
- Calculated delivered-order counts.
- Analysed purchase-to-delivery duration.
- Calculated late-delivery and cancellation rates.
- Examined monthly delivery performance.
- Compared delivery performance across sellers and categories.
- Evaluated customer review scores.

### Week 3 – Deeper Analysis & Recommendations
- Investigated patterns in delayed deliveries.
- Analysed purchase-to-carrier handover time.
- Examined carrier-to-customer transit time.
- Compared customer review scores for delayed and non-delayed orders.
- Developed operational recommendations.

### Week 4 – Dashboard & Documentation
- Developed a Power BI dashboard.
- Created KPI cards and visualizations.
- Prepared the final project report.
- Documented findings, limitations and recommendations.

## Key Performance Indicators (KPIs)

| Metric | Result |
|---|---:|
| Total Orders | 99,441 |
| Eligible Delivered Orders | 96,470 |
| Late Deliveries | 6,534 |
| Late Delivery Rate | 6.77% |
| On-Time / Early Delivery Rate | 93.23% |
| Average Delivery Duration | 12.56 days |
| Median Delivery Duration | 10.22 days |
| Cancellation Rate | 0.63% |

*Note: KPI values are based on the analysis summary and its respective eligibility criteria.*

## Key Business Insights

- Approximately 6.77% of eligible delivered orders arrived later than their estimated delivery dates.
- The average purchase-to-customer delivery duration was 12.56 days.
- Purchase-to-carrier handover averaged approximately 3.23 days.
- Carrier handover-to-customer transit averaged approximately 9.33 days.
- March 2018 recorded a higher late-delivery rate of approximately 18.96% in the monthly analysis.
- Late deliveries were associated with lower average customer review scores (2.27 compared with 4.29 for on-time/early deliveries).

These findings are descriptive and do not establish causation.

## Power BI Dashboard

The dashboard explores:

- Total delivered orders.
- Late delivery rate.
- Average delivery duration.
- Monthly late-delivery trends.
- Late deliveries by product category.
- Late deliveries by seller.

*Dashboard measures should be interpreted alongside eligible order counts.*

## Business Recommendations

1. Investigate operational factors contributing to high late-delivery months.
2. Improve order processing and carrier handover efficiency.
3. Monitor seller and product-category delivery performance.
4. Track customer satisfaction alongside delivery KPIs.
5. Incorporate carrier, regional and distance information in future analysis.

## Limitations

- No reliable carrier identifier or direct delivery-distance measure was available.
- Seller and category comparisons may be affected by differences in order volumes.
- Customer review comparisons are observational.
- KPI results depend on the selected filters and eligible records.

## Repository Contents

The repository contains the following project materials:

- `01_data_quality_eda.ipynb` – Week 1 data quality and EDA notebook.
- `01_data_quality_eda (1).ipynb` – Additional notebook version.
- `week1_project_files.zip` – Supporting project files.
- Power BI dashboard (`.pbix`).
- Final project report (`.docx`).
- `README.md` – Project documentation.

## How to Explore

1. Open the Python notebook using Google Colab.
2. Review the data preparation and analysis workflow.
3. Open the Power BI dashboard using Power BI Desktop.
4. Explore the final report for detailed findings and recommendations.

## Original Project Attribution

This portfolio project is based on the original work by **Aravinda Surampally**.

Original repository:  
https://github.com/aravindasurampally-123/ecommerce-delivery-logistics-analysis

The original analytical materials are credited to their author. Any additional analysis, documentation or modifications should be identified separately. Please check reuse permissions before redistributing original project materials.

## Author

**Gonela Rishika**

B.Tech – Computer Science and Engineering (AI & ML)  
Aspiring Data Analyst

GitHub: https://github.com/Rishika-Gonela
