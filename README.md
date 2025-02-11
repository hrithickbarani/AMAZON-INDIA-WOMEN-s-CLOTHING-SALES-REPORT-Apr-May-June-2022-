# Amazon India Women's Clothing Sales Report (April-May-June 2022)

![License](https://img.shields.io/badge/license-MIT-blue.svg)  
[![Python Version](https://img.shields.io/badge/python-3.x-blue)](https://www.python.org/)  
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)


### TO LOOK AT THE CODE, PLEASE VISIT THE IPYNB FILE.
### TO VIEW ALONG WITH VISUALIZATIONS, VISIT BELOW LINK: 
https://nbviewer.org/github/hrithickbarani/Amazon-India-Women-s-Clothing-Sales-Report-Apr-May-June-2022-/blob/main/amazonIndia_womens_clothing_sales_report_%28Apr_May_June%29_2022.ipynb

## Description

This project analyzes the sales data of women's clothing on Amazon India for the months of April, May, and June 2022. The dataset includes details such as product category, size, sales date, order status, fulfilment method, style, SKU, ASIN, courier status, quantity, amount, B2B sales, and currency. The analysis provides insights into sales trends, popular product categories, regional performance, cancellation rates, and lost revenue due to cancellations.

---

## Dataset Overview

The dataset contains the following columns:

1. **Category**: Type of product. (String)  
2. **Size**: Size of the product. (String)  
3. **Date**: Date of the sale. (Date)  
4. **Status**: Status of the sale. (String)  
5. **Fulfilment**: Method of fulfilment. (String)  
6. **Style**: Style of the product. (String)  
7. **SKU**: Stock Keeping Unit. (String)  
8. **ASIN**: Amazon Standard Identification Number. (String)  
9. **Courier Status**: Status of the courier. (String)  
10. **Qty**: Quantity of the product. (Integer)  
11. **Amount**: Amount of the sale. (Float)  
12. **B2B**: Business-to-business sale. (Boolean)  
13. **Currency**: The currency used for the sale. (String)

---

## Key Insights

### 1. **Sales Trends Over Months**
- **April** had the highest sales revenue (`₹7,639,769`) and quantity sold (`12,135`).
- **May** saw a drop in quantity (`10,441`) but maintained strong revenue (`₹7,092,527`).
- **June** experienced a sharp decline in both quantity (`6,294`) and revenue (`₹4,341,529`).

### 2. **Top Product Categories**
- **Set** dominated sales with the highest revenue (`₹8,965,064`) and quantity sold (`10,671`).
- **Kurta** followed closely with revenue of `₹4,880,318` and `10,491` units sold.
- **Western Dress**, **Top**, and **Ethnic Dress** also performed well but with lower volumes.

### 3. **Popular Sizes**
- **Set** and **Kurta** were the most popular categories, with sizes **M, L, XL, S, and XXL** leading in sales.
- Larger sizes (e.g., **4XL, 5XL, 6XL**) had minimal sales across all categories.

### 4. **Regional Performance**
- **Maharashtra** generated the highest revenue (`₹3.21M`) and quantity sold (`4,983`).
- **Karnataka** and **Tamil Nadu** followed closely in both revenue and quantity.
- Cities like **Bengaluru**, **Hyderabad**, and **Mumbai** were top performers.

### 5. **Order Trends**
- **April** had the highest number of orders (`43,940`), with a gradual decline in **May** (`37,823`) and **June** (`34,122`).
- **Saturday** and **Friday** were the busiest days for orders.

### 6. **Cancellations and Lost Revenue**
- **April** had the highest cancellations (`3,004`) and lost revenue (`₹1.93M`).
- Cancellation rates remained stable, with **Set** and **Kurta** being the most affected categories.
- **Maharashtra** and **Karnataka** had the highest number of cancellations.

### 7. **Cancellations by Cities**
- **Bengaluru** had the highest number of cancellations across all months:
  - **April**: `1,272` cancellations.
  - **May**: `957` cancellations.
  - **June**: `922` cancellations.
- **Hyderabad** and **Mumbai** also showed significant cancellations, with **Hyderabad** consistently ranking second.

---

## Analysis Highlights

### Exploratory Data Analysis (EDA)
- Analyzed monthly sales trends, popular categories, and regional performance.
- Identified key drivers of sales and cancellations.

### Cancellation Analysis
- Investigated cancellation trends by month, category, region, and city.
- Calculated lost revenue due to cancellations.

### Regional Insights
- Highlighted top-performing states and cities.
- Identified regions with low sales and high cancellations.

---

