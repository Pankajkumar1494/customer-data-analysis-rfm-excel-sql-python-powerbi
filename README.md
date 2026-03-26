# customer-data-analysis-rfm-excel-sql-python-powerbi

 📊 Retail Customer Data Analysis: Multi-Tool RFM Segmentation

📌 Project Overview

This comprehensive project analyzes customer behavior for a mid-sized Indian retail company to drive data-driven marketing. By analyzing a dataset of 23,050 transactions and 1,000 customers, I implemented a full-stack data workflow to perform RFM (Recency, Frequency, Monetary) Analysis.

The project transitions from raw data exploration to a polished executive dashboard, providing actionable insights into "Champions," "Loyalists," and "At-Risk" segments.

🛠️ Multi-Tool Tech Stack

To ensure a robust analysis, I utilized the strengths of different industry-standard tools:

Excel: Initial data exploration, data profiling, and quick sanity checks of the synthetic datasets.

SQL (MySQL): Created the data warehouse, performed data cleaning (date standardization), and executed complex RFM metric calculations using CTEs and Window Functions.

Python (Pandas & Seaborn): Conducted deep-dive statistical analysis and advanced scoring using pd.qcut(). Generated static visualizations to identify correlations between age, income, and spending.

Power BI: Developed an interactive executive dashboard to visualize customer distribution across geographies and income brackets, allowing stakeholders to filter insights in real-time.

HTML/CSS: Built a custom presentation deck for a professional walkthrough of the project logic.

🚀 Project Workflow

1. Data Cleaning & Engineering (SQL & Excel)

Standardized inconsistent date formats (DD-MM-YYYY) into SQL-ready DATE objects.

Handled missing values and validated record uniqueness to ensure 100% data integrity.

2. RFM Calculation Logic (SQL & Python)

Recency (R): Days since the last purchase using reference "today" dates.

Frequency (F): Total count of unique purchase sessions per customer.

Monetary (M): Total revenue (₹) contribution per customer.

Scoring: Distributed customers into 5 equal quintiles (1-5 scale) based on their performance across all three metrics.

3. Business Segmentation & Visualization (Power BI)

Created an automated labeling system to categorize customers:

Champions: High-value, high-frequency, recent buyers.

Loyal Customers: Consistent repeat buyers who drive steady revenue.

At Risk: Former high-value shoppers who haven't engaged recently.

Big Spenders: High Monetary value customers who buy less frequently.

💡 Business Impact (Non-Technical Summary)

Stopping the Guesswork: We moved from generic marketing to a clear map of who the best customers are.

Optimizing Budget: Identified the top 20% of customers (Champions) who drive the majority of profit, allowing the marketing team to focus their spending where it counts.

Re-engagement Strategy: Created a list of "At-Risk" customers to target with specific "We Miss You" discount codes to prevent churn.

Geographic Insights: Power BI visualizations revealed which Indian metro cities have the highest concentration of high-income "Big Spenders."


