# Retail Sales Business Intelligence Analysis

## Business Context

A retail company aims to better understand its sales performance,
customer segmentation, regional distribution, and operational efficiency
to support data-driven decision-making.

This project analyzes historical sales data to uncover actionable insights
that can guide strategic planning, marketing focus, and logistics optimization.

---

## Project Objectives

- Evaluate overall sales performance and revenue distribution
- Identify high-performing customer segments and regions
- Analyze monthly sales trends and detect seasonality
- Assess operational efficiency using shipping lead time
- Detect revenue concentration across product categories and sub-categories

---

## Project Structure

retail-sales-bi-dashboard/

│

├── data/

│ ├── raw/

│ └── processed/

│

├── notebooks/

│ ├── 01_data_profiling.ipynb

│ ├── 02_data_cleaning.ipynb

│ └── 03_exploratory_analysis.ipynb

│

└── README.md


## Notebook Overview

**01 – Data Profiling**
- Dataset structure validation
- Missing values analysis
- Duplicate checks
- Data type inspection
- Initial data quality findings

**02 – Data Cleaning & Structural Feature Engineering**
- Date conversion and validation
- Missing value handling
- Lead Time calculation (Ship Date – Order Date)
- Creation of Year, Month, and Year-Month features
- Order-level consistency validation

**03 – Business-Oriented Exploratory Data Analysis**
- Revenue distribution analysis
- Monthly sales trend evaluation
- Segment and regional performance comparison
- Shipping performance analysis
- Category and sub-category revenue concentration

---

## Key Business Insights

- Sales show an overall upward trend with noticeable monthly volatility.
- The **Consumer segment** drives the majority of total revenue.
- The **West region** leads sales performance, while the South underperforms.
- **Technology** is the highest revenue-generating category.
- Revenue is concentrated in a few sub-categories, particularly **Phones and Chairs**.
- Shipping lead times increase consistently by service level, indicating operational alignment.

---

## Business Implications

- Marketing strategies may prioritize high-performing segments and regions.
- Underperforming regions represent potential expansion opportunities.
- Product portfolio optimization could focus on high-revenue sub-categories.
- Logistics strategy can evaluate trade-offs between shipping speed and cost.

---

## Tools & Technologies

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Git & GitHub
- Business Intelligence concepts
- Data Cleaning & Feature Engineering best practices

---

## Potential Next Steps

- Profitability analysis (if profit data available)
- Customer lifetime value estimation
- Sales forecasting modeling
- Development of an interactive Power BI dashboard
- Executive summary presentation for stakeholders

---

## Author

Silvio Guillén  
