# E-Commerce Delivery & Logistics Performance Analysis

**An End-to-End Data Analytics Project | Python | Power BI**

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-orange?logo=googlecolab)

## Project Overview

This project focuses on analysing e-commerce delivery and logistics performance using the Brazilian E-Commerce Public Dataset by Olist.

The analysis explores delivery timelines, late deliveries, cancellations, product categories, seller performance and customer review scores to identify operational patterns and generate meaningful business insights.

Python is used for data preparation, exploratory data analysis and KPI calculations, while Power BI is used to develop interactive dashboards and visualize important business metrics.

## Project Objectives

- Audit and prepare the dataset for analysis.
- Perform Exploratory Data Analysis (EDA).
- Identify missing values, duplicates and data quality issues.
- Calculate important delivery performance KPIs.
- Analyse late-delivery patterns across different time periods.
- Compare delivery performance across product categories and sellers.
- Examine customer review scores for late and on-time deliveries.
- Develop an interactive Power BI dashboard.
- Generate actionable business recommendations.

## Tools & Technologies

| Technology | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Google Colab | Notebook execution |
| Power BI Desktop | Interactive dashboards |
| GitHub | Project documentation and version control |

## Dataset

The project uses the Brazilian E-Commerce Public Dataset by Olist.

The dataset contains information about:
- Customer orders
- Purchase and delivery timestamps
- Estimated delivery dates
- Order status
- Product categories
- Seller information
- Customer reviews

**Data limitation:** The available dataset does not provide a usable carrier identifier or direct delivery-distance measure for this analysis.

## Project Workflow

### Week 1 – Data Quality Audit & Exploratory Data Analysis

- Loaded and inspected the dataset.
- Examined dataset dimensions and data types.
- Identified missing values and duplicate records.
- Analysed important order and delivery fields.
- Checked timestamp fields and data quality issues.
- Documented preprocessing requirements.

### Week 2 – KPI Engineering & Delivery Performance Analysis

- Calculated delivered-order counts.
- Analysed purchase-to-customer delivery duration.
- Compared actual and estimated delivery dates.
- Calculated late-delivery and cancellation rates.
- Examined monthly delivery performance.
- Compared delivery performance across sellers and product categories.
- Analysed customer review scores.

### Week 3 – Deeper Analysis & Business Insights

- Investigated patterns in delayed deliveries.
- Analysed purchase-to-carrier handover time.
- Examined carrier-to-customer transit time.
- Compared customer review scores for late and on-time deliveries.
- Identified operational patterns.
- Developed practical business recommendations.

### Week 4 – Power BI Dashboard & Final Documentation

- Developed a Power BI dashboard.
- Created KPI cards and visualizations.
- Analysed monthly late-delivery trends.
- Compared delivery performance across categories and sellers.
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

*Note: KPI results are based on the available analysis summary and their respective calculation criteria.*

## Key Business Insights

- Approximately 6.77% of eligible delivered orders arrived later than their estimated delivery dates.
- The average purchase-to-customer delivery duration was approximately 12.56 days.
- The median delivery duration was approximately 10.22 days.
- Purchase-to-carrier handover averaged approximately 3.23 days.
- Carrier handover-to-customer transit averaged approximately 9.33 days.
- March 2018 recorded a higher late-delivery rate of approximately 18.96% in the monthly analysis.
- Late deliveries were associated with lower average customer review scores (2.27 compared with 4.29 for on-time/early deliveries).

These findings are descriptive. The relationship between delivery delays and customer reviews does not establish causation.

## Power BI Dashboard

The Power BI dashboard provides an overview of e-commerce delivery and logistics performance.

### Dashboard Highlights

- Total Delivered Orders
- Late Delivery Rate
- Average Delivery Duration
- Monthly Late-Delivery Trends
- Late-Delivery Rate by Product Category
- Late-Delivery Rate by Seller

The dashboard helps explore delivery performance and identify areas that may require operational improvement.

## Business Recommendations

1. Investigate operational conditions during months with unusually high late-delivery rates.
2. Improve order processing and carrier handover efficiency.
3. Monitor seller and product-category delivery performance alongside eligible order counts.
4. Track customer satisfaction and review scores alongside delivery KPIs.
5. Incorporate carrier, regional and delivery-distance information in future analyses.

## Project Limitations

- The dataset does not provide a usable carrier identifier or direct delivery-distance measure.
- Seller and product-category comparisons may be affected by differences in order volumes.
- Customer review comparisons are observational and do not establish causation.
- KPI values depend on the eligible records, filters and calculation criteria used.

## Repository Contents

The repository includes the following project materials:

- `01_data_quality_eda.ipynb` – Data quality audit and exploratory analysis.
- `01_data_quality_eda (1).ipynb` – Additional notebook version.
- Power BI dashboard (`.pbix`).
- Project report (`.docx`).
- `week1_project_files.zip` – Supporting project files.
- `README.md` – Project documentation.

## How to Explore the Project

1. Open the Python notebook using Google Colab.
2. Review the data cleaning and exploratory analysis workflow.
3. Explore the delivery performance metrics and visualizations.
4. Open the Power BI dashboard using Power BI Desktop.
5. Review the project report for detailed findings and recommendations.

## Project Author

**Gonela Rishika**

B.Tech – Computer Science and Engineering (AI & ML)

**GitHub Profile:**  
https://github.com/Rishika-Gonela

**Project Repository:**  
https://github.com/Rishika-Gonela/ecommerce-delivery-logistics-analysis

**Technologies:** Python | Pandas | NumPy | Matplotlib | Power BI

