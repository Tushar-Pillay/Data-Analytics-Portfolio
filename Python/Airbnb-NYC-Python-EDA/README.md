# 🏠 Airbnb Listings EDA Project | New York 2024

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Graphics-green?style=for-the-badge)

</p>

<p align="center">
  <img src="https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Python/Airbnb-NYC-Python-EDA/image_1c674873.png" alt="Airbnb Banner" width="100%">
</p>

---

# 📖 Project Overview

This project presents a comprehensive **Exploratory Data Analysis (EDA)** of the **New York Airbnb Listings 2024** dataset using Python.

The project explores pricing trends, room types, host behavior, listing availability, and geographical distribution to generate meaningful business insights.

---

# 🎯 Objectives

- Analyze Airbnb pricing trends.
- Study room type distributions.
- Understand host behavior.
- Detect price outliers.
- Perform feature engineering.
- Generate business recommendations.

---

# 📂 Dataset Information
   
**Dataset Name:**
New York Airbnb Listings 2024

**Total Records:** 20,765

**Total Features:** 22

### Important Features

- Listing ID
- Host ID
- Host Name
- Neighbourhood Group
- Room Type
- Price
- Reviews
- Availability
- Beds
- Bedrooms
- Baths
- Ratings

---

# 📊 Dataset Source

The data for this project is sourced from the Kaggle dataset:
   #### 🔗Dataset Link:[Airbnb Dataset](https://www.kaggle.com/datasets/vrindakallu/new-york-dataset)
   #### 🔗[Downloaded Dataset](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Python/Airbnb-NYC-Python-EDA/datasets.csv)

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# ⚙️ Project Workflow

## Data Cleaning

- Removed missing values
- Removed duplicate records
- Converted data types

## Feature Engineering

Created a new feature:

```
Price Per Bed = Price / Beds
```

## Exploratory Data Analysis

### Univariate Analysis

- Price Distribution
- Availability Distribution
- Outlier Detection

### Bivariate Analysis

- Price vs Neighborhood
- Price vs Room Type
- Reviews vs Price

### Geographical Analysis

- Airbnb Listings across New York

### Correlation Analysis

- Heatmap of numerical features

---

# 📈 Visualizations

✔ Boxplots

✔ Histograms

✔ Bar Charts

✔ Scatter Plots

✔ Pair Plots

✔ Correlation Heatmaps

✔ Geographical Distribution Maps

---

# 🔍 Key Findings

## 💰 Pricing

- Manhattan has the highest average prices.
- Brooklyn follows Manhattan.

## 🏠 Room Types

- Entire homes are the most expensive.
- Private rooms are budget-friendly.

## 👤 Host Behavior

- Some hosts manage multiple properties.

## 📍 Location Insights

- Most listings are concentrated in Manhattan and Brooklyn.

## 🛏 Price Per Bed

- Manhattan records the highest average price per bed.

---

# 💡 Recommendations

## For Guests

- Choose listings with high ratings.
- Private rooms offer better value.
- Compare properties using Price Per Bed.

## For Hosts

- Optimize pricing.
- Increase availability.
- Encourage guest reviews.

---

## 🎯 Conclusion

This project successfully explored and analyzed the **New York Airbnb Listings 2024** dataset using Exploratory Data Analysis (EDA) techniques. Through data cleaning, feature engineering, statistical analysis, and visualization, valuable insights were uncovered regarding pricing trends, room type distributions, listing availability, host activity, and neighborhood-level patterns.

The analysis revealed that **Manhattan commands the highest average listing prices**, while **Brooklyn offers a balance between affordability and demand**. Entire homes and apartments dominate the market, whereas private rooms provide budget-friendly accommodation options. The introduction of the **Price Per Bed** metric further enhanced the evaluation of listing value across different property types.

By leveraging Python libraries such as **Pandas, NumPy, Matplotlib, and Seaborn**, this project transformed raw Airbnb data into actionable insights that can benefit both guests and hosts. Guests can make more informed booking decisions, while hosts can optimize pricing and availability strategies based on market trends.

Overall, this project demonstrates key Data Analytics competencies, including **Data Cleaning, Data Visualization, Feature Engineering, Exploratory Data Analysis (EDA), and Business Insight Generation**. Future enhancements may include predictive price modeling, sentiment analysis, and interactive dashboard development to provide even deeper insights into the Airbnb marketplace.





