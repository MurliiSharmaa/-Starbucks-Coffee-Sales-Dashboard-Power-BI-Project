# ☕ Starbucks Coffee Sales Dashboard | Power BI Project
This repository contains an interactive Power BI dashboard analyzing Starbucks coffee sales. The dashboard explores key business metrics like product performance, revenue trends, and customer insights — all presented in a visually engaging and intuitive format.

✅ **Completed as part of the WsCube Tech Masterclass by Ayushi Jain**
## 📊 Project Objective
To build a dynamic and insightful Power BI dashboard that provides answers to business questions such as:

- Which product category generates the most revenue?
- What are the monthly sales trends?
- Which items are the best and worst performers?
- How is the overall sales performance across different segments?


## 🙌 Who It's For
This project is for Power BI learners, data analysts, and students who want to build portfolio-ready dashboards, analyze sales data, and improve their data visualization skills. Ideal for beginners and anyone interested in business intelligence.
## 📬 Contact
For questions or collaboration:

Email: murli.analyst@gmail.com

LinkedIn: https://www.linkedin.com/in/murli-v-sharma/

#🧾 Dataset Overview

This project uses two primary datasets:

Orders Table – captures each sales transaction

Products Table – contains detailed product information

🛍 Orders Table (Transactional Data)
Column Name	              Description
transaction_id          	Unique identifier for each transaction
transaction_date        	Date of the transaction
transaction_time        	Time of the transaction
store_id	                     Unique identifier of the Starbucks store
store_location	             Physical location of the store
product_id          	          Foreign key referencing the Products table
transaction_qty     	        Quantity of the product sold in transaction

📦 Products Table (Product Master Data)
Column Name	            Description
product_id	                Unique identifier for each product
product_category	    Category the product belongs to (e.g., Beverage)
product_type	            Type of product (e.g., Latte, Espresso)
product_detail          	Detailed description of the product
unit_price                  	Selling price per unit

These datasets are joined using the product_id field to perform meaningful analysis across product sales, locations, and time.
##  ## 📌 Key Features of the Dashboard
- Clean and user-friendly interface
- Slicers and filters for dynamic interaction
- KPIs (Key Performance Indicators) at a glance
- Category-wise and product-wise breakdown
- Monthly and yearly sales trends
- Revenue contribution by top-selling products

## ## 🛠 Tools Used
- **Power BI** (Dashboard Creation)
- **Excel / CSV** (Data Source)
- **DAX** (For calculated columns and measures)
- **Power Query** (For data cleaning and transformation)

## ## 📷 Dashboard Preview
