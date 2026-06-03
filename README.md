# City Level Order Performance Analysis
## Description
This project analyses order level transactional data to evaluate sales performance, pricing components, and delivery metrics across cities. Using order, store, and customer datasets, the analysis focuses on how quantities, discounts, taxes, delivery fees, and total order values vary by city.

## Objective
The objective of this analysis is to evaluate city level performance across key financial and operational metrics and to identify cities driving the highest and lowest order value, tax, discount, and quantity outcomes.

## Business Questions
The analysis was guided by the following questions:
1. Which cities generate the highest and lowest total order value?
2. How do tax amounts vary across cities?
3. Which cities receive the highest and lowest total discounts?
4. How does quantity sold differ across cities?
5. Which cities contribute the highest and lowest subtotal amounts?
6. How are delivery fees distributed across cities?
7. Which cities record the highest and lowest items count?
8. How does actual delivery time compare with promised delivery time across stores?
9. How does total quantity sold vary across stores and business orders?

## Dataset Overview
The analysis is based on three related datasets.
- Orders Table
**Rows:** 1,001  
**Columns:** 16  
- Key Columns
Order ID, Order Timestamp, Store ID, Customer ID, Channel, Payment Method, Promo Code, Items Count, Quantity Total, Subtotal (NGN), Discount (NGN), Tax (NGN), Delivery Fee (NGN), Total Amount (NGN), Promised Delivery Minutes, Actual Delivery Minutes.

- Store Table
**Rows:** 13  
**Columns:** 5  
- Key Columns
Store ID, Store Name, City, Opening Hours, Delivery SLA Minutes  

- Customer Table
**Rows:** 2,001  
**Columns:** 5  
- Key Columns
Customer ID, Signup Date, City, Phone Number, Is Business  

## Tools Used
Microsoft Excel
- Excel Functions  
- Pivot Tables  
- Data Modelling  
- Charts  
- Dashboard Design  

## Data Preparation
The datasets were cleaned and prepared to ensure accuracy and consistency before analysis.
- Verified relationships between Orders, Store, and Customer tables
- Standardised city names across all datasets
- Validated numeric fields such as quantity, items count, tax, discount, and delivery fee
- Ensured monetary fields were correctly formatted in NGN
- Handled missing and blank values appropriately
- Verified timestamp fields for time-based analysis

## Dashboard
The Excel dashboard provides a city level overview including:
- Total Amount by City
- Subtotal, Discount, Tax, and Delivery Fee by City
- Quantity Total and Items Count by City
- High and low performing cities across key metrics
<img width="1094" height="777" alt="image" src="https://github.com/user-attachments/assets/0ee7b668-9cee-4a0d-9294-78111fe8a16d" />

## Key Insights
- Port Harcourt records the highest subtotal **1,101,025** and total order value **1,175,988.88**.
- Lagos records the highest quantity of items sold **505**.
- Abuja records the highest delivery fee totals **53900**.
- Ibadan consistently records the lowest performance across several metrics including subtotal **952,950.00**, quantity **397**, and total amount **1,044,376.98**.
- Discounts and taxes vary noticeably across cities, reflecting differences in order values and promotional activity.

## Recommendation
- Investigate the factors contributing to Port Harcourt's higher order values and subtotal performance. 
- Review operational and sales performance in Ibadan to understand the reasons for lower order value and quantity metrics. 
- Monitor delivery fee patterns across cities to identify locations with relatively higher delivery costs. 
- Analyse the relationship between discounts and total order values across cities to evaluate promotional effectiveness. 
- Compare quantity and order value trends across cities regularly to identify emerging performance changes.

## Conclusion
Order values and associated cost components vary significantly across cities. Port Harcourt leads in revenue generation, recording the highest subtotal and total order amount, while Lagos drives the highest sales volume in terms of quantity sold. Abuja records the highest delivery fee totals, suggesting higher delivery related costs in that location. In contrast, Ibadan consistently records the lowest performance across multiple metrics, including subtotal, quantity sold, and total order amount. These insights highlight opportunities for targeted pricing strategies, operational improvements, and city specific growth initiatives to improve overall performance.
