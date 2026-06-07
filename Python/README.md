# 🏠 Airbnb Listings EDA Project | New York 2024

<p align="center">
  <img src="https://images.unsplash.com/photo-1522708323590-d24dbb6b0267?w=1200" alt="Airbnb Banner" width="100%">
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Graphics-green?style=for-the-badge)

</p>

---

## 📖 Project Overview

This project presents a comprehensive **Exploratory Data Analysis (EDA)** of the **New York Airbnb Listings 2024** dataset. Using Python and popular data analytics libraries, this project uncovers pricing trends, host behavior, room type distributions, and geographical patterns to generate meaningful business insights.

The analysis follows a complete data analytics workflow including:

- 📥 Data Loading
- 🧹 Data Cleaning
- ⚙️ Feature Engineering
- 📊 Exploratory Data Analysis (EDA)
- 📈 Data Visualization
- 💡 Business Insights & Recommendations

---

# 🎯 Objective

The primary objectives of this project are to:

- Analyze Airbnb pricing trends across New York boroughs.
- Study room types and listing availability.
- Understand host behavior and listing patterns.
- Detect and handle outliers in rental prices.
- Visualize important business metrics.
- Generate actionable insights for guests and hosts.

---

# 📂 Dataset Information

The dataset contains approximately **20,765 Airbnb listings** with **22 features**.

### Key Features

| Feature | Description |
|----------|-------------|
| id | Unique listing identifier |
| name | Airbnb listing title |
| host_id | Unique host identifier |
| host_name | Host name |
| neighbourhood_group | Borough of the property |
| neighbourhood | Local neighborhood |
| latitude | Geographic latitude |
| longitude | Geographic longitude |
| room_type | Type of accommodation |
| price | Nightly rental price |
| minimum_nights | Minimum booking nights |
| number_of_reviews | Total guest reviews |
| reviews_per_month | Average monthly reviews |
| availability_365 | Available days per year |
| beds | Number of beds |
| bedrooms | Number of bedrooms |
| baths | Number of bathrooms |
| rating | Guest rating |

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

- Imported the Airbnb dataset using Pandas.
- Performed initial inspection of rows, columns, and data types.

---

## 2️⃣ Data Cleaning

### ✔ Missing Value Handling

- Removed rows containing null values.
- Ensured consistency across all features.

### ✔ Duplicate Removal

- Identified and removed duplicate records.

### ✔ Data Type Conversion

- Converted `id` and `host_id` into categorical (object) data types.

---

## 3️⃣ Feature Engineering

A new feature was created:

### Price Per Bed

```
Price Per Bed = Price / Beds
```

This metric provides a more realistic comparison between listings.

---

# 📊 Exploratory Data Analysis (EDA)

## 📈 Univariate Analysis

### Price Distribution

- Visualized using Histograms.
- Most listings fall within an affordable pricing range.

### Outlier Detection

- Used Boxplots to identify extreme prices.
- Filtered high-priced outliers for better analysis.

### Availability Distribution

- Studied yearly listing availability patterns.

---

## 📉 Bivariate Analysis

### Price vs Neighborhood Group

- Compared average prices across boroughs.
- Manhattan recorded the highest average prices.

### Price vs Room Type

- Entire homes/apartments are the costliest.
- Private rooms provide budget-friendly accommodation.

### Reviews vs Price

- Scatter plots used to analyze customer engagement and pricing.

---

## 🌍 Geographical Analysis

Using latitude and longitude coordinates:

- Visualized listing locations across New York.
- Observed high concentration in Manhattan and Brooklyn.

---

## 🔥 Correlation Analysis

Generated a heatmap for numerical features:

- Price
- Minimum Nights
- Number of Reviews
- Reviews Per Month
- Availability
- Beds
- Latitude
- Longitude

---

# 📊 Visualizations Included

- ✅ Boxplots
- ✅ Histograms
- ✅ Bar Charts
- ✅ Scatter Plots
- ✅ Pair Plots
- ✅ Correlation Heatmaps
- ✅ Geographical Distribution Maps

---

# 🔍 Key Findings & Insights

## 💰 Pricing Trends

- Manhattan has the highest average Airbnb prices.
- Brooklyn follows Manhattan in premium pricing.

## 🏡 Room Type Distribution

- Entire homes/apartments dominate the market.
- Private rooms offer affordable alternatives.

## 📍 Geographic Concentration

- Listings are densely concentrated in central boroughs.

## 🛏 Price Per Bed Analysis

- Manhattan has the highest average price per bed.
- This metric allows better comparison between listings.

## 📅 Availability Patterns

- Listings with higher availability generally receive more reviews.

## 👤 Host Behavior

- Several hosts manage multiple listings, indicating professional hosting.

---

# 🚀 How to Run This Project

## Clone the Repository

```bash
git clone https://github.com/yourusername/Airbnb-NewYork-EDA.git
```

## Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

## Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

# 💡 Recommendations

## For Guests

- Choose listings with strong reviews and ratings.
- Private rooms in Brooklyn and Queens provide better value.
- Compare listings using Price Per Bed.

## For Hosts

- Improve listing availability.
- Optimize pricing according to neighborhood trends.
- Encourage guest reviews for better visibility.

---

# 🔮 Future Enhancements

- Build a Machine Learning model for price prediction.
- Perform sentiment analysis on guest reviews.
- Create an interactive Power BI/Tableau dashboard.
- Deploy the project as a web application.

---

# 📁 Project Structure

```text
Airbnb-NewYork-EDA/
│
├── Airbnb_EDA.ipynb
├── new_york_listings_2024.csv
├── README.md
├── images/
│   ├── price_distribution.png
│   ├── room_type_distribution.png
│   ├── heatmap.png
│   ├── pairplot.png
│   └── geo_distribution.png
│
└── requirements.txt
```

---

# 📚 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis
- Feature Engineering
- Data Visualization
- Statistical Analysis
- Business Intelligence
- Python Programming

---

# 👨‍💻 Author

## Tushar Pillay

**Aspiring Data Analyst | Python | SQL | Power BI | Excel | Data Visualization**

### Connect with Me

- LinkedIn: *(Add your LinkedIn Profile)*
- GitHub: *(Add your GitHub Profile)*

---

## ⭐ If you found this project helpful, consider giving this repository a Star!
