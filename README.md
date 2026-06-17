# Olist-E-Commerce-Performance-Analysis-Dashboard
## Dashboard Powered by Power BI and DAX Analytics
## Table of Contents
- Analysis Overview
- Objective
- Data Source
- Preparation Tools
- Data Processing
- Skills Demonstrated
- Revenue Performance Insights
- Product Performance Insights
- Customer Insights
- Delivery & Operations Insights
- Recommendations
 -Dashboard
- Conclusion
- Dashboard Interaction

- ## Analysis Overview

This project analyzes sales performance, customer behavior, product performance, and delivery operations using the Olist Brazilian E-Commerce dataset. The objective was to transform raw transactional data into actionable business insights through interactive Power BI dashboards.

The analysis focused on four key business areas:

- Revenue Performance
- Product Performance
- Customer Insights
- Delivery & Operations

Using Power BI, data modeling techniques, DAX measures, and interactive visualizations were applied to uncover revenue trends, identify top-performing product categories, evaluate customer retention, and assess delivery efficiency across different states.

The final dashboard provides decision-makers with a centralized view of business performance and highlights opportunities for improving customer retention, product strategy, and operational efficiency.

## Objective

The objective of this project was to analyze Olist's e-commerce performance and uncover insights that can support business decision-making.

Specifically, the analysis aimed to:

* Evaluate overall revenue performance and sales trends over time.
* Identify top-performing product categories and their contribution to total revenue.
* Understand customer purchasing behavior and assess customer retention.
* Examine preferred payment methods used by customers.
* Measure delivery efficiency and monitor order fulfillment performance.
* Identify regions with longer delivery times and potential operational challenges.
* Develop an interactive dashboard that enables stakeholders to monitor key business metrics and make data-driven decisions.

## Data Source

The dataset used for this project is the **Olist Brazilian E-Commerce Public Dataset**, which contains transactional data from Olist, one of Brazil's largest online marketplaces. The dataset includes information on orders, customers, products, payments, sellers, and delivery operations covering the period from September 2016 to October 2018.

The analysis was primarily built using the following tables:

* **olist_orders_dataset** – order status and delivery dates.
* **olist_order_items_dataset** – product prices and freight values.
* **olist_products_dataset** – product category information.
* **product_category_name_translation** – English translations of product categories.
* **olist_order_payments_dataset** – payment methods and payment values.
* **olist_customers_dataset** – customer information and location data.

The data was obtained from the public Olist dataset available on Kaggle and integrated into Power BI for data modeling, analysis, and dashboard development.

## Preparation Tools

The following tools and technologies were used throughout the project:

* **Power BI Desktop** – data modeling, analysis, and dashboard development.
* **Power Query** – data transformation and preparation.
* **DAX (Data Analysis Expressions)** – creation of calculated measures and KPIs.
* **Microsoft Excel/CSV files** – source data format.
* **Kaggle** – source of the Olist Brazilian E-Commerce dataset.

These tools were used to transform raw transactional data into interactive dashboards and actionable business insights.

## Data Processing

Several data preparation and modeling steps were performed before building the dashboard:

* Imported and integrated multiple tables from the Olist dataset into Power BI.
* Established relationships between tables to enable cross-table analysis.
* Created DAX measures for key performance indicators such as Revenue, Orders, Average Order Value (AOV), Delivery Metrics, and Customer Retention Metrics.
* Used customer_unique_id to accurately analyze repeat customer behavior.
* Applied Top N filters to highlight the highest-performing product categories and customers.
* Handled issues related to category translation and table relationships during the modeling process.
* Formatted metrics using appropriate units and percentages to improve dashboard readability.
* Developed four dashboard pages covering Revenue Overview, Product Performance, Customer Insights, and Delivery & Operations.

## Skills Demonstrated

This project demonstrates the following technical and analytical skills:

* Data Cleaning and Transformation
* Data Modeling and Relationship Management
* DAX Calculations and KPI Development
* Dashboard Design and Data Visualization
* Revenue and Product Performance Analysis
* Customer Segmentation and Retention Analysis
* Delivery and Operations Performance Analysis
* Business Insight Generation
* Problem Solving and Data Validation
* Storytelling with Data
* Power BI Best Practices

## Revenue Performance Insights

* The business generated approximately **R$15.84 million** in total revenue during the analysis period.
* Revenue exhibited fluctuations over time, with noticeable peaks during certain months, indicating periods of stronger customer demand.
* São Paulo (SP) contributed the highest share of revenue, making it the most important market for the business.
* Credit cards were the most preferred payment method among customers, accounting for the majority of transactions.
* Revenue concentration across states suggests opportunities for expanding sales in less represented regions.

## Product Performance Insights

* Revenue was concentrated among a relatively small number of product categories.
* The top-performing categories consistently generated the highest sales and contributed a significant share of total revenue.
* Revenue distribution across categories showed that a few categories dominated the marketplace, while many others contributed relatively smaller amounts.
* Trend analysis revealed that category performance changed over time, suggesting varying customer preferences and possible seasonal effects.
* Understanding category performance can help prioritize inventory management and marketing efforts.

## Customer Insights

* The platform served approximately **96,000 customers** during the analysis period.
* Customer spending varied considerably, with a small group of customers contributing disproportionately to revenue.
* Most customers made only one purchase, while a much smaller percentage returned for additional orders.
* Customer retention was relatively low, indicating that the business relied heavily on acquiring new customers.
* Increasing repeat purchases through loyalty programs and targeted promotions could improve long-term customer value.

## Delivery & Operations Insights

* Orders were delivered in an average of approximately 9 days, demonstrating generally efficient order fulfillment.
* More than 92% of orders were delivered on or before the estimated delivery date, indicating strong delivery performance.
* Only a small proportion of orders experienced delays, although delayed orders took an average of 12.5 days beyond the estimated delivery date.
* Delivery performance varied across states, with some regions experiencing significantly longer delivery times than others.
* Monitoring regional delivery performance can help identify logistics bottlenecks and improve customer satisfaction.

## Recommendations

Based on the analysis, the following recommendations are proposed:

* Strengthen customer retention strategies through loyalty programs, personalized offers, and remarketing campaigns to encourage repeat purchases.
* Focus marketing efforts on high-performing product categories while exploring opportunities to improve underperforming categories.
* Expand market penetration in states with lower revenue contribution to diversify revenue sources.
* Continue optimizing logistics operations to reduce delivery delays and improve customer satisfaction.
* Leverage the popularity of credit card payments by offering flexible payment options and promotional incentives.
* Monitor product and delivery performance continuously to support data-driven business decisions.

## Dashboard

The final Power BI dashboard was organized into four interactive pages:

### Revenue Overview

Provides insights into revenue trends, geographic performance, and customer payment preferences.


### Product Performance

Highlights top-performing categories, category revenue contribution, and category revenue trends.

### Customer Insights

Examines customer value and purchasing behavior, including customer retention patterns.

### Delivery & Operations

Evaluates delivery efficiency, order fulfillment performance, and regional delivery variations.

The dashboard enables stakeholders to monitor key metrics and gain a comprehensive understanding of overall business performance.

## Conclusion

This project demonstrates how Power BI can be used to transform raw e-commerce data into actionable business insights. Through data modeling, DAX calculations, and interactive visualizations, key patterns in revenue, product performance, customer behavior, and delivery operations were identified. The findings provide valuable information that can support strategic decision-making and operational improvements.
