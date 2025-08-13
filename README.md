Zepto E-commerce SQL Data Analysis Project

This project is a real-world data analysis portfolio project built using an inventory dataset from **Zepto**, one of India's fastest-growing quick-commerce platforms. The focus is on SQL-based business analysis of e-commerce data including pricing, inventory, and product performance.

Project Overview

The objective of this project is to simulate a real-world data analyst workflow, from raw dataset loading to structured SQL queries that provide actionable business insights. The project includes:

- Importing and cleaning real-world e-commerce data  
- Handling missing or inconsistent values  
- Writing analytical SQL queries  
- Preparing for future data visualizations (Power BI / Python)

🗂️ Dataset Description

The dataset was scraped from Zepto's live product listings and sourced via Kaggle. Each row represents a unique SKU (Stock Keeping Unit) — with products possibly appearing multiple times in different weights, quantities, or discounts.

 🔸 Key Columns:
- `sku_id`: Unique product identifier
- `name`: Product name
- `category`: Product type (e.g., Beverages, Fruits, Snacks)
- `mrp`: Maximum Retail Price (₹)
- `discountPercent`: Discount on MRP
- `discountedSellingPrice`: Final selling price after discount
- `availableQuantity`: Inventory available
- `weightInGms`: Product weight in grams
- `outOfStock`: Boolean flag (TRUE = not available)
- `quantity`: Units per package

🔍 SQL Analysis Performed

12 business-focused SQL queries were written to extract useful insights from the dataset. These include:
- Top discounted products
- High-MRP products currently out of stock
- Revenue by product category
- Price per gram analysis
- Weight category classification (Low / Medium / Bulk)
- Inventory weight per category
- Most stocked or popular product categories
- Categories with highest discount offers
- Value of unsold inventory (based on available stock)


📌 Power BI Visualization – Zepto Dataset

This interactive Power BI dashboard delivers detailed insights from the Zepto product dataset, including: 

📊 Sales Performance: Revenue trends by category and product.

💰 Pricing Insights: Comparison of MRP vs. discounted selling prices.

🏆 Top Rankings: Best-selling products and top revenue-generating categories.

🎯 Discount Analysis: Distribution and impact of discounts across categories.


⚠️ Note: These insights are generated solely from the provided dataset and do not represent real-world market trends

These will help convert raw SQL insights into visual reports useful for stakeholders.

-------👨‍💻 Author------

Nikhil Pereira

Aspiring Data Analyst | BSc Statistics & Computer Science

Learning through real-world projects and building a strong data portfolio

Feel free to connect on [LinkedIn](https://www.linkedin.com/in/nikhilpereira23/)


