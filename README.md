Overview
The Retail Dashboard in Excel is an interactive data visualization tool designed to analyze retail sales performance. It integrates Power Query, Pivot Tables, and Dynamic Charts to provide key insights into sales, profitability, orders, and market trends. This dashboard enables data-driven decision-making for businesses looking to optimize operations and increase efficiency.

Features:
Automated Data Processing using Power Query

KPI Dashboard with key business metrics

Interactive Charts & Visualizations for in-depth analysis

Sales & Profitability Insights across different segments and categories

Geographic Sales Analysis by country and region

Datasets Used
1. Orders Table
Contains transactional details, including product, customer, and financial metrics.

**Sample Data:**  

| Order ID        | Order Date  | Ship Date  | Ship Mode     | Customer Name  | Segment    | Country       | Sales   | Profit  | Discount |
|----------------|------------|------------|--------------|---------------|-----------|--------------|--------|--------|----------|
| CA-2012-124891 | 31-07-2020 | 31-07-2020 | Same Day     | Rick Hansen   | Consumer  | United States | 2309.65 | 762.18 | 0        |
| IN-2013-77878  | 05-02-2021 | 07-02-2021 | Second Class | Justin Ritter | Corporate | Australia     | 3709.40 | -288.77 | 0.1      |

### 2. Returns Table  
Tracks orders that were returned along with the associated market.  

**Sample Data:**  

| Returned | Order ID        | Market |
|----------|----------------|--------|
| Yes      | MX-2013-168137  | LATAM  |
| Yes      | US-2011-165316  | LATAM  |

