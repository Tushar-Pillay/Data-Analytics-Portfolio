# 🛒 Zepto E-commerce SQL Data Analyst Project
![Zepto logo](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/SQL/Zepto-sql-Analysis/zepto%20image.webp)

## Overview
This project involves a comprehensive analysis of Zepto app data using SQL. 
The goal is to extract valuable insights and answer various business questions based on the dataset. 
The following README provides a detailed account of the project's objectives, business problems, solutions, findings, and conclusions.

## Objectives
✅ Set up a messy, real-world e-commerce inventory database

✅ Perform Exploratory Data Analysis (EDA) to explore product categories, availability, and pricing inconsistencies

✅ Implement Data Cleaning to handle null values, remove invalid entries, and convert pricing from paise to rupees

✅ Write business-driven SQL queries to derive insights around pricing, inventory, stock availability, revenue and more

 ## 📁 Dataset Overview
The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/palvinder2006/zepto-inventory-dataset/data?select=zepto_v2.csv) and was originally scraped from Zepto’s official product listings. It mimics what you’d typically encounter in a real-world e-commerce inventory system.
Each row represents a unique SKU (Stock Keeping Unit) for a product. Duplicate product names exist because the same product may appear multiple times in different package sizes, weights, discounts, or categories to improve visibility – exactly how real catalog data looks.

 ## 🧾 Database Columns:
- sku_id: Unique identifier for each product entry (Synthetic Primary Key)
- name: Product name as it appears on the app
- category: Product category like Fruits, Snacks, Beverages, etc.
- mrp: Maximum Retail Price (originally in paise, converted to ₹)
- discountPercent: Discount applied on MRP
- discountedSellingPrice: Final price after discount (also converted to ₹)
- availableQuantity: Units available in inventory
- weightInGms: Product weight in grams
- outOfStock: Boolean flag indicating stock availability
- quantity: Number of units per package (mixed with grams for loose produce)

##### Refer to the [SQL_project_file](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/SQL/Zepto-sql-Analysis/Zepto_SQL_data_analysis.sql).

## 🔧 Project Workflow

### 1. Database & Table Creation
We start by creating a SQL table with appropriate data types:
```sql
CREATE TABLE zepto (
  sku_id SERIAL PRIMARY KEY,
  category VARCHAR(120),
  name VARCHAR(150) NOT NULL,
  mrp NUMERIC(8,2),
  discountPercent NUMERIC(5,2),
  availableQuantity INTEGER,
  discountedSellingPrice NUMERIC(8,2),
  weightInGms INTEGER,
  outOfStock BOOLEAN,
  quantity INTEGER
);
```
### 2. Data Import
Loaded CSV using pgAdmin's import feature.

### 3. 🔍 Data Exploration
- Counted the total number of records in the dataset
- Viewed a sample of the dataset to understand structure and content
- Checked for null values across all columns
- Identified distinct product categories available in the dataset
- Compared in-stock vs out-of-stock product counts
- Detected products present multiple times, representing different SKUs

### 4. 🧹 Data Cleaning
- Identified and removed rows where MRP or discounted selling price was zero
- Converted mrp and discountedSellingPrice from paise to rupees for consistency and readability

### 5. 📊 Business Insights
- Found top 10 best-value products based on discount percentage
- Identified high-MRP products that are currently out of stock
- Estimated potential revenue for each product category
- Filtered expensive products (MRP > ₹500) with minimal discount
- Ranked top 5 categories offering highest average discounts
- Calculated price per gram to identify value-for-money products
- Grouped products based on weight into Low, Medium, and Bulk categories
- Measured total inventory weight per product category







