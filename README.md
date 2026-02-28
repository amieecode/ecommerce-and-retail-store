# E-Commerce & Online Retail Analytics Project
This project analyzes sales, customer behavior, and fulfillment patterns for an e-commerce and retail business.
The goal is to uncover insights that improve decision-making across sales, operations, inventory, and customer experience.

**Brief overview of the company:**
An e-commerce company is facing multiple operational challenges that hinder growth and customer satisfaction. To address these issues, the company is using data to improve operations.

## Problem Statement
Orders are frequently delayed, canceled, or returned, affecting customer satisfaction and revenue. The company wants to identify operational inefficiencies and optimize product and fulfillment performance.

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

## Dashboard Overview 
![Dashboard Preview](https://github.com/amieecode/ecommerce-and-retail-store/blob/main/Image%20and%20Presentation/Ecom-dashboard.png)


## Challenges Faced
- Data quality issues (missing or inconsistent order statuses)
- Date hierarchies for trend analysis (month, week, weekday)
- Identifying operational KPIs in a concise one-page dashboard

## Conclusion
The analysis of the e-commerce and retail store data highlights several key insights:
- **Revenue Performance:** Strong growth was observed in April, with total revenue driven primarily by Amazon.in and top categories such as Sets, Kurtas, and Western Dresses.
- **Customer & Operational Insights:** Delivered orders constitute 58.47% of total orders, but a high cancellation rate (37.27%) indicates operational or fulfillment challenges.
- **Top Performing Markets:** Bengaluru, Hyderabad, and Mumbai are the leading revenue-generating cities.
- **Problematic Products:** Specific product styles, notably JNE3797, show disproportionately high failed orders, signaling product or fulfillment issues.
- **Channel & Category Dependence:** Heavy reliance on Amazon.in and a few key categories highlights potential risk concentration.
Overall, the company exhibits strong growth potential but faces operational inefficiencies and revenue concentration risks that require strategic action.

## Recommendation
- **Operational Improvements:** Investigate high cancellation and return rates; enhance fulfillment accuracy and delivery reliability.
- **Product Focus:** Review top problematic products (e.g., JNE3797) for quality, sizing, or listing improvements to reduce failures.
- **Channel Diversification:** Strengthen non-Amazon sales channels to reduce dependency and mitigate risk.
- **Market Strategy:** Prioritize marketing and inventory for high-performing cities (Bengaluru, Hyderabad, Mumbai) while exploring growth opportunities in underperforming cities.
- **Category Optimization:** Focus on high-revenue categories (Sets, Kurtas, Western Dresses) while reassessing low-performing categories for promotion, repositioning, or discontinuation.
- **Data-Driven Monitoring:** Implement continuous dashboard monitoring to track revenue trends, returns, cancellations, and top-performing products for proactive decision-making.

## Project Presentation 
You can view or download the full presentation here:

[View Presentation](Image%20and%20Presentation/Ecommerce_presentation.pdf)



