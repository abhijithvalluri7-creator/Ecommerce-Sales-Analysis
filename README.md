# E-Commerce Sales Analysis Using Python

## Project Overview
This project explores an online retail dataset to understand sales performance, product demand, revenue trends, and order cancellations. I used Python to clean and analyze the data, calculate key business metrics, and identify areas where the business could improve.

## Tools Used
- Python
- Pandas
- Matplotlib
- Google Colab

## Dataset
Source: UCI Machine Learning Repository - Online Retail Dataset

The dataset contains 541,909 transaction records covering December 2010 to December 2011.

After data cleaning, 524,878 records were retained for sales analysis.

## Key Metrics
| Metric | Result |
|---|---|
| Total Sales Revenue | £10,642,110.80 |
| Total Orders | 19,960 |
| Identified Customers | 4,338 |
| Units Sold | 5,572,420 |
| Average Order Value | £533.17 |
| Invoice Cancellation Rate | 14.81% |

## Analysis Performed
1. Cleaned the retail transaction data and prepared it for analysis.
2. Calculated revenue, order volume, customer count, and average order value.
3. Compared revenue across countries.
4. Identified the highest-revenue merchandise products.
5. Analyzed monthly revenue trends.
6. Examined cancelled invoices and negative transaction values.

## Key Findings
### Revenue by Country
The United Kingdom contributed approximately 84.6% of positive-sales revenue, showing a strong concentration in the domestic market.

### Product Performance
Regency Cakestand 3 Tier generated approximately £174,157, making it the highest-revenue merchandise description in this analysis.

I also identified non-merchandise entries such as postage and manual charges and separated them when analyzing product performance.

### Monthly Sales Trends
Revenue increased noticeably toward the end of 2011, with November recording approximately £1.50 million in sales.

### Order Cancellations
The dataset contained 3,836 cancelled invoices out of 25,900 unique invoice numbers, representing a cancellation rate of approximately 14.81%.

Negative cancellation lines totaled approximately £896,812 in absolute value.

## Business Recommendations
- Explore opportunities to expand sales outside the UK to reduce geographic concentration.
- Prioritize inventory planning for high-revenue merchandise.
- Investigate the causes of invoice cancellations to identify opportunities for operational improvement.
- Use historical monthly trends to support seasonal inventory and sales planning.

## Project Notebook
[View the complete analysis](Day01_Ecommerce_Sales_Analysis.ipynb)

## Author
Abhijith Valluri
