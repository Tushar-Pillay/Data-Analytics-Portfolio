# 🍽️ Zomato Restaurant Data Analysis Using Python

<p align="center">
  <img src="https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Python/Zomato-Restaurant-Data-Analysis/image_1bb06b15.png" alt="Zomato Restaurant Analysis Banner" width="100%">
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Graphics-green?style=for-the-badge)

</p>

---

# 📖 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Zomato restaurant data to uncover customer preferences, restaurant performance, online ordering trends, and pricing behavior.

Using Python libraries such as **Pandas, NumPy, Matplotlib, and Seaborn**, the project transforms raw restaurant data into meaningful business insights through statistical analysis and visualization.

---

# 🎯 Objectives

- Analyze restaurant categories and customer preferences.
- Study restaurant ratings and customer voting patterns.
- Understand the impact of online ordering on ratings.
- Explore customer spending behavior.
- Generate actionable business insights through data visualization.

---

# 📂 Dataset Information

The dataset contains restaurant-related information including:

| Feature | Description |
|----------|-------------|
| name | Restaurant Name |
| online_order | Online Ordering Availability |
| rate | Restaurant Rating |
| votes | Number of Customer Votes |
| approx_cost(for two people) | Average Cost for Two |
| listed_in(type) | Restaurant Category |

---

# 📊 Dataset Source

The data for this project is sourced from the Kaggle dataset:
   #### 🔗Dataset Link:[Zomato](https://www.kaggle.com/datasets/rajeshrampure/zomato-dataset)
   #### 🔗[Downloaded Dataset](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Python/Zomato-Restaurant-Data-Analysis/Zomato%20data.csv)
---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📚 Python Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

# 🔄 Project Workflow

## 1️⃣ Data Loading

- Imported the Zomato dataset using Pandas.
- Examined rows, columns, and data types.

## 2️⃣ Data Cleaning

### Rating Conversion

Converted restaurant ratings from string format into numerical values.

```python
def handleRate(value):
    value = str(value).split('/')
    value = value[0]
    return float(value)

df['rate'] = df['rate'].apply(handleRate)
```

---

## 3️⃣ Exploratory Data Analysis (EDA)

### 🍴 Restaurant Type Analysis

- Analyzed restaurant categories using count plots.
- Identified the most preferred restaurant types.

### ⭐ Ratings Analysis

- Studied restaurant rating distributions.
- Determined common customer satisfaction levels.

### 🗳️ Votes Analysis

- Examined customer engagement through voting behavior.
- Identified highly popular restaurant categories.

### 💰 Cost Analysis

- Analyzed spending preferences of customers.
- Explored average dining costs for two people.

### 📱 Online Ordering Analysis

- Compared ratings between restaurants offering online ordering and those that do not.
- Studied customer ordering behavior.

### 🔥 Correlation & Pattern Analysis

- Used heatmaps and visualizations to uncover hidden trends.

---

# 📈 Visualizations Included

✔ Count Plot

✔ Histogram

✔ Line Plot

✔ Box Plot

✔ Heatmap

---

# 🔍 Key Findings

## 🍽️ Restaurant Preferences

- Dining restaurants are the most preferred category.
- They receive the highest customer engagement and votes.

## ⭐ Rating Trends

- Most restaurant ratings fall between **3.5 and 4.0**.
- High-rated restaurants tend to attract more customers.

## 💰 Customer Spending Behavior

- Most customers prefer restaurants with moderate pricing.
- Average spending is approximately **₹300 for two people**.

## 📱 Online Ordering Insights

- Restaurants offering online ordering generally receive better ratings.
- Cafes benefit significantly from online delivery services.

## 🗳️ Voting Behavior

- Restaurants with higher customer engagement receive more votes and better visibility.

---

# 💡 Business Recommendations

## For Restaurant Owners

- Enable online ordering to increase customer reach.
- Encourage customer reviews and engagement.
- Maintain competitive pricing strategies.

## For Food Delivery Platforms

- Promote highly-rated restaurants.
- Provide personalized restaurant recommendations.

---

# 🎯 Conclusion

This project successfully analyzed Zomato restaurant data to uncover customer preferences, restaurant performance patterns, pricing behavior, and online ordering trends. Through Exploratory Data Analysis (EDA), valuable insights were generated regarding restaurant categories, customer engagement, and rating distributions.

The findings indicate that dining restaurants are the most preferred category, restaurants offering online ordering generally achieve higher ratings, and customers tend to favor moderately priced dining options. These insights can help restaurant owners optimize pricing strategies, improve customer experience, and enhance business performance.

Overall, this project demonstrates practical applications of **Data Cleaning, Data Visualization, Statistical Analysis, and Business Intelligence** using Python to transform raw restaurant data into actionable insights.

---

# 🛠️ Skills Demonstrated

- Data Analysis
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Data Visualization
- Statistical Analysis
- Business Analytics
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Insight Generation
- Problem Solving

---
