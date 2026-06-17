# 🍔 Nutritional Analysis and Strategic Menu Engineering for McDonald's India

![IIT Madras](https://img.shields.io/badge/IIT%20Madras-BDM%20Capstone-orange)
![Business Analytics](https://img.shields.io/badge/Domain-Business%20Analytics-blue)
![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-green)
![Data Analytics](https://img.shields.io/badge/Focus-Decision%20Making-red)

![McDonald's India](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Excel/BDM%20Capstone%20Project-%20IIT%20Madras/image_afdf3c13.png)
---

# 🎓 IIT Madras BDM Capstone Project

This project was completed as part of the **Business Data Management (BDM) Subject** under the **IIT Madras**.

The BDM Capstone Project is designed to help students apply business analytics concepts to real-world business problems. Students are required to identify a business challenge, collect and analyze relevant data, derive meaningful insights, and propose actionable recommendations using analytical techniques.

This project demonstrates the practical application of:

* Business Analytics
* Data Management
* Statistical Analysis
* Decision Support Systems
* Business Intelligence
* Data-Driven Strategy Formulation

---

# 📖 Project Overview

The Quick Service Restaurant (QSR) industry is experiencing a significant shift as consumers increasingly prioritize health, nutritional transparency, and informed food choices.

McDonald's India, one of the largest QSR chains in the country, serves millions of customers through its extensive network of restaurants. While menu engineering has traditionally focused on taste, affordability, and operational efficiency, growing consumer awareness has created a need to evaluate nutritional efficiency across menu offerings.

This project performs a comprehensive nutritional analysis of McDonald's India menu items using business analytics techniques. The objective is to identify nutritional inefficiencies, develop healthier meal combinations, create a health scoring framework, and provide strategic recommendations that balance customer satisfaction and business performance.

---

# 🏢 Organization Overview

McDonald's India is a leading Quick Service Restaurant (QSR) brand operating across India.

### Key Highlights

* Over 800 outlets nationwide
* Presence in 75+ cities
* Operates through a unique "Glocal" strategy
* Customized Indian menu offerings
* Strong supply chain and operational network
* Millions of customers served annually

---

# 🚨 Business Problem

The project addresses what is termed as the:

## Health-Profit Paradox

While several menu items contribute significantly to sales, they may also present nutritional concerns due to:

* High calorie density
* Excessive sodium levels
* Low protein efficiency
* Lack of healthy bundle offerings
* Absence of a unified health scoring system

The challenge is to balance profitability with increasing consumer demand for healthier menu choices.

---

# 🎯 Project Objectives

## Objective 1: Menu Pruning

Identify nutritionally inefficient menu items characterized by:

* High Sodium
* High Fat
* Low Protein

using statistical outlier detection techniques.

---

## Objective 2: Healthy Bundle Optimization

Develop healthier meal combinations that satisfy:

* Total Energy < 500 kCal
* Protein > 12 g

while maintaining customer appeal.

---

## Objective 3: Satiety Efficiency Analysis

Evaluate whether larger serving sizes provide meaningful nutritional value by analyzing the relationship between:

* Serving Size
* Protein Content

---

## Objective 4: Nutrient Density Index (NDI)

Develop a custom nutritional scoring model that classifies menu items into:

* Premium Health
* Balanced
* High-Risk

categories.

---

# 📂 Dataset Information

### Dataset Source

[Kaggle](https://www.kaggle.com/datasets/deepcontractor/mcdonalds-india-menu-nutrition-facts)

### Dataset

[McDonald's India Menu Nutrition Dataset](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Excel/BDM%20Capstone%20Project-%20IIT%20Madras/India_Menu.csv)

### Excel Analysis

[Excel_File](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Excel/BDM%20Capstone%20Project-%20IIT%20Madras/Indian_Menu%20Excel%20Analysis.xlsx)

### Dataset Characteristics

* 141 Menu Items
* Multiple Product Categories
* Structured Nutritional Data
* Secondary Data Source

### Variables Used

| Variable         | Description      |
| ---------------- | ---------------- |
| Energy (kCal)    | Total Calories   |
| Protein (g)      | Protein Content  |
| Total Fat (g)    | Fat Content      |
| Sodium (mg)      | Sodium Content   |
| Total Sugars (g) | Sugar Content    |
| Per Serve Size   | Serving Size     |
| Menu Category    | Product Category |

---

# 🛠️ Tools & Technologies

* Microsoft Excel
* Power Query
* Data Analysis ToolPak
* Excel Solver
* Pivot Tables
* Correlation Analysis
* Z-Score Analysis
* Dashboard Visualization

---

# ⚙️ Project Methodology

## Step 1: Data Cleaning & Preparation

* Data import using Power Query
* Unit removal (g/ml)
* Numeric conversion
* Missing value treatment
* Data validation

---

## Step 2: Descriptive Statistics

Calculated:

* Mean
* Median
* Standard Deviation
* Variance
* Range

to understand the overall nutritional profile.

---

## Step 3: Outlier Detection

Applied Z-Score Analysis:

Z = (x − Mean) / Standard Deviation

Purpose:

Identify nutritionally extreme menu items.

---

## Step 4: Correlation Analysis

Pearson Correlation Analysis was conducted between:

* Serving Size
* Protein Content

Result:

Correlation = -0.0906

Finding:

Increasing serving size does not proportionally increase protein content.

---

## Step 5: Healthy Bundle Optimization

Meal combinations were generated based on:

* Energy < 500 kCal
* Protein > 12g

to identify healthier alternatives.

---

## Step 6: Nutrient Density Index (NDI)

Formula:

NDI = (Protein / Energy) × 100 − (Sodium / 1000)

Purpose:

Provide a unified nutritional ranking system.

---

# 📊 Key Findings

## Nutritional Outliers

Several menu items were identified as nutritional outliers due to extremely high sodium and fat levels.

Example:

* Ghee Rice with McSpicy Fried Chicken
* Chicken Maharaja Mac
* Chicken Cheese Lava Burger

---

## Satiety Efficiency

Correlation:

-0.0906

Key Finding:

Larger serving sizes do not guarantee higher protein value.

---

## Healthy Bundle Opportunities

The optimization model successfully identified multiple meal combinations that satisfy calorie and protein constraints.

These combinations can support a future:

### Nutri-Bundle Strategy

---

## Nutrient Density Index Results

| Category       | Percentage |
| -------------- | ---------- |
| High-Risk      | 63%        |
| Balanced       | 23%        |
| Premium Health | 14%        |

The majority of menu items fall into the High-Risk category.

---

# 💡 Strategic Recommendations

### 1. Menu Pruning

Review nutritionally inefficient menu items.

### 2. Nutri-Bundle Launch

Introduce curated healthy meal combinations.

### 3. Nutritional Labelling

Implement NDI-based menu classification.

### 4. Product Rebalancing

Increase the proportion of Premium Health offerings.

---

# 📈 Business Impact

This project demonstrates how business analytics can be leveraged to:

* Improve nutritional transparency
* Enhance menu engineering
* Support healthier customer choices
* Strengthen brand positioning
* Improve strategic decision-making

---

# 🚀 Future Scope

* Customer Purchase Behaviour Analysis
* Machine Learning Recommendation Systems
* Dynamic Health Scoring
* Real-Time Menu Optimization

---

# 📸 Project Visualizations

### Scatter Plot: Protein vs Satiety Efficiency

[Fig](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Excel/BDM%20Capstone%20Project-%20IIT%20Madras/Scatter%20plot.png)

### Average Protein by Category

[fig](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Excel/BDM%20Capstone%20Project-%20IIT%20Madras/Average%20protein%20vs%20menue.png)

### Healthy Bundle Optimization

[fig](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Excel/BDM%20Capstone%20Project-%20IIT%20Madras/Healthy%20Bunddle.png)

### Health Tier Distribution

[fig](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Excel/BDM%20Capstone%20Project-%20IIT%20Madras/Healthy%20tier%20Distribution.png)

---

# 📑 Project Documents

## 📄 Proposal Report

[View Proposal Report](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Excel/BDM%20Capstone%20Project-%20IIT%20Madras/Proposal%20file%20-%20Github.pdf)

## 📄 Final Report

[View Final Report](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Excel/BDM%20Capstone%20Project-%20IIT%20Madras/Final%20report.pdf)

## 📄 Viva Presentation

[View Presentation](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Excel/BDM%20Capstone%20Project-%20IIT%20Madras/PPT%20Github.pdf)

---






⭐ If you found this project interesting, consider giving the repository a star.

