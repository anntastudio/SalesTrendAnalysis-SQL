# RetailSalesTrendAnalysis-SQL
### Project background
A retail store needed better insights from sales data to understand overall trends, customer spends, and high performing products.

### Objectives
The goal was to analyse sales data, stored in the data warehouse (Microsoft SQL Server), to answer three key questions:
1. How are sales changing over time?
2. Who are our most valuable customers?
3. Which product categories make us the most money?
   
### Methodology
* Data source: local data warehouse
* Tools used: Azure Data Studio, SQL Notebook, MS SQL to analyse 60,000+ transactions from 2010-2013, creating queries to track monthly sales performance, classify customers into segments (New, Regular, VIP), and calculate product category contributions using aggregate functions, CTE and window functions.
  
### Insights
*All charts generated in SQL notebook*
* Sales trends: Revenue grew from 2010 to 2013, with peak sales in Dec 2013 at €1.87M
<img width="1000" height="547" alt="image" src="https://github.com/user-attachments/assets/cc15dc2c-3e3e-4b12-9569-089dc8086b68" />


* Customer base: 79% are new customers, only 9% are VIPs (lifespan > 12 months and spend > €5K)
<img width="1000" height="531" alt="image" src="https://github.com/user-attachments/assets/73cad9e0-1d31-4666-90ff-5b54f9733fb7" />


* Product mix: Bikes generate 96% of revenue; Accessories and Clothing combined contribute less than 4%
<img width="350" height="581" alt="image" src="https://github.com/user-attachments/assets/7a55d058-6858-4020-920e-873e41bc6973" />
<br>

### Recommendations
* Improve customer retention to convert New customers into Regular and VIP segments
* Reduce revenue dependency on Bikes by growing Accessories and Clothing sales
* Investigate seasonal sales patterns to optimize inventory and marketing
* Build automated dashboards for ongoing performance monitoring

### Next Steps
Create predictive models for sales forecasting and connect sales data with marketing campaigns to identify what drives purchases.
