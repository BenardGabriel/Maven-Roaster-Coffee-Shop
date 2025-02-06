# Maven-Roaster-Coffee-Shop
This project aims to provides an insightful overview of Maven Roasters' key business metrics, including total revenue, quantity sold, customer count, and product performance. It visualizes sales trends over time, identifies peak business days, and highlights the most and least popular products. 

## Data Source
The main dataset utilized for this analysis is the coffee shop sales file, which provides detailed information about each transaction made by the business.

## Tools
- Excel - Data cleaning and transformation 
- Power BI - Data visualization

## Data Cleaning / Preparation

In the initial data preparation phase, we performed the following task;
1. Data loading and inspection
2. Changed data type
3. Extracted time

### Exploratory Data Analysis

EDA involves exploring the sales data to answer key question such as;

- Sales trend overtime
- The day of the week that tends to be the busiest
- The Product that are sold most often and least often.

### Data Analysis 

Include some interesting DAX functions

```DAX
Total Product = Distinctcount(Transaction[product_category])
Total Qty = Sum(Transaction[transaction_qty])
```

### Results/Findings

The analysis provides us with key insights which are as follow:

1. Financial & Customer Metrics:
Total Revenue: $698.8K
Total Quantity Sold: 214K units
Total Customers: 149K
Total Products: 9

2. Sales Trend:
Sales have shown fluctuations but generally increased from January to June 2023.

3. Busiest Days:
The most active days are Monday (14.55%), Thursday (14.51%), and Friday (14.35%), while other days also contribute significantly.

4. Product Performance:
Most Sold Products: Coffee, Tea, and Bakery items.
Least Sold Products: Flavours, Coffee Beans, and Loose Tea.

### Recommendation

Based on the analysis, here are some recommendations for Maven Roasters:

1. Optimize Inventory & Marketing – Since coffee and tea are the best sellers, ensure consistent stock and consider promotions or loyalty programs to further boost sales.
2. Increase Sales on Slower Days – Since Monday, Thursday, and Friday are the busiest, introduce special discounts or events on slower days to balance foot traffic.
3. Expand Product Offerings – Flavours, coffee beans, and loose tea are the least sold, so consider bundling them with popular products or adjusting pricing and marketing strategies.
4. Seasonal & Trend Analysis – Given the sales trends, prepare for peak seasons by adjusting stock and workforce accordingly to maximize revenue opportunities.

These steps can help improve sales, customer engagement, and overall business performance.


