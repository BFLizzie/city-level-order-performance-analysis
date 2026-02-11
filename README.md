# CITY-LEVEL ORDER PERFORMANCE ANALYSIS

## Description
This project analyses order-level transactional data to evaluate sales performance, pricing components, and delivery metrics across cities. Using order, store, and customer datasets, the analysis focuses on how quantities, discounts, taxes, delivery fees, and total order values vary by city, with the goal of identifying revenue concentration, cost drivers, and operational patterns.
The analysis was conducted in Microsoft Excel, reflecting a real-world analytical workflow using structured datasets and pivot-based insights.

## Project Objective
The objective of this analysis is to:
- Evaluate city-level performance across key financial and operational metrics
- Identify cities driving the highest and lowest order value, tax, discount, and quantity outcomes
- Understand how pricing components (discounts, tax, delivery fees) contribute to total order value
- Support data-driven decisions related to pricing strategy, logistics, and city-level optimisation

## Business Questions
The analysis was guided by the following questions:
1. Which cities generate the highest and lowest total order value?
2. How do tax amounts vary across cities?
3. Which cities receive the highest and lowest total discounts?
4. How does quantity sold differ by city?
5. Which cities contribute the highest and lowest subtotal amounts?
6. How are delivery fees distributed across cities?
7. Which cities record the highest and lowest items count per order?

## Dataset Overview
The analysis is based on three related datasets:

### Orders Table
- **Rows:** 1,001  
- **Columns:** 16  
**Key Columns:**  
Order ID, Order Timestamp, Store ID, Customer ID, Channel, Payment Method, Promo Code,  
Items Count, Quantity Total, Subtotal (NGN), Discount (NGN), Tax (NGN),  
Delivery Fee (NGN), Total Amount (NGN), Promised Delivery Minutes, Actual Delivery Minutes

### Store Table
- **Rows:** 13  
- **Columns:** 5  
**Key Columns:**  
Store ID, Store Name, City, Opening Hours, Delivery SLA Minutes

### Customer Table
- **Rows:** 2,001  
- **Columns:** 5  
**Key Columns:**  
Customer ID, Signup Date, City, Phone Number, Is Business

## Tools Used
- **Microsoft Excel**
  - Excel functions
  - Pivot tables
  - Data modelling with related tables
  - Charts
  - Dashboard design

## Data Preparation
The datasets were cleaned and prepared in Excel to ensure accuracy and consistency before analysis. Key steps included:
- Verifying primary and foreign key relationships between Orders, Store, and Customer tables
- Ensuring all monetary fields were formatted correctly in NGN
- Validating numeric fields such as quantity, items count, tax, discount, and delivery fees
- Standardising city names across all tables
- Handling missing or blank values appropriately
- Confirming timestamp fields supported time-based analysis

## Dashboard
An Excel dashboard was developed to provide a city-level performance overview, including:
- Total Amount by City  
- Subtotal, Discount, Tax, and Delivery Fee by City  
- Quantity Total and Items Count by City  
- High and low performing cities across key metrics  
<img width="1022" height="819" alt="image" src="https://github.com/user-attachments/assets/c2a9efcd-22db-45ee-aca5-e0ffb0393fca" />

## Key Insights
### City by Tax (NGN)
- **Port Harcourt** records the highest tax amount at **₦82,576.88**
- **Ibadan** records the lowest tax amount at **₦71,471.22**

### City by Discount (NGN)
- **Port Harcourt** receives the highest total discount at **₦45,513**
- **Ibadan** receives the lowest total discount at **₦20,344.25**

### City by Quantity Total
- **Lagos** records the highest quantity total at **505**
- **Ibadan** records the lowest quantity total at **397**

### City by Subtotal (NGN)
- **Port Harcourt** generates the highest subtotal at **₦1,101,025**
- **Ibadan** generates the lowest subtotal at **₦952,950**

### City by Delivery Fee (NGN)
- **Abuja** records the highest delivery fee total at **₦53,900**
- **Port Harcourt** records the lowest delivery fee total at **₦37,900**

### City by Total Amount (NGN)
- **Port Harcourt** generates the highest total order amount at **₦1,175,988.88**
- **Ibadan** generates the lowest total order amount at **₦1,044,376.98**

### City by Items Count
- **Abuja** records the highest items count at **371**
- **Ibadan** records the lowest items count at **286**

## Conclusion
This analysis shows that order value and cost components vary significantly across cities. Port Harcourt consistently leads in key revenue-related metrics, including subtotal, tax, discount, and total amount, indicating strong order value concentration. Lagos stands out in sales volume through quantity totals, while Abuja records higher delivery-related costs and item counts.
Ibadan consistently appears as the lowest-performing city across multiple metrics, highlighting potential opportunities for market development, pricing review, or operational optimisation.
Overall, the insights provide a clear city-level performance view that can support pricing strategy adjustments, logistics planning, and targeted city-level growth initiatives.
