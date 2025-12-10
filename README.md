# E-Commerce & Online Retail Analytics Project
This project analyzes sales, customer behavior, and fulfillment patterns for an e-commerce and retail business.
The goal is to uncover insights that improve decision-making across sales, operations, inventory, and customer experience.

## Project Overview
This project involves:
- Cleaning and transforming the raw dataset using Python (Google Colab)
- Conducting comprehensive Exploratory Data Analysis (EDA)
- Understanding order status patterns, returns, sales trends, and fulfillment performance
- Creating KPIs, slicers, and interactive visuals in Power BI

## Tools & Technologies

- Python (Pandas, NumPy, Matplotlib/Seaborn)
- Google Colab – for accessible, cloud-based Python workflows
- Power BI – for dashboard creation and data storytelling
- GitHub – for project versioning and documentation

## Dataset Description

The dataset includes e-commerce order records with variables such as:
- Order Information: Order ID, Date, Qty, Amount
- Product Details: Style, SKU, Category, Size, ASIN
- Customer & Shipping: Ship City, State, Postal Code, Country
- Fulfillment & Status: Sales Channel, Fulfilment Type, Courier Status
- Indicators: B2B flag, Promotions, Currency

## Key Data Cleaning Steps
Performed in Google Colab:
- Corrected data types (dates, numeric values, categorical columns)
- Handled missing values appropriately
- Converted currency fields to numeric
- Standardized text fields (status, fulfillment, channel)
- Removed invalid or duplicate entries
- Extracted date parts (year, month, day, weekday)
- Created new calculated metrics

## Key KPIs (Power BI)
- Total Revenue
- Total Orders
- Delivery Rate
- Return Rate
- Top Performing Category
- Top City by Orders
- Average Order Value (AOV)
- Revenue by Sales Channel

![Dashboard Preview]([images/Financial View.png](https://github.com/amieecode/ecommerce-and-retail-store/blob/main/Images/Financial%20View.png))

