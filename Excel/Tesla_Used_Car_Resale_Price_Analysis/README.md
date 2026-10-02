# 🚗 Tesla Used Car Resale Price Analysis

### Business Analytics | Statistical Analysis | Regression | Hypothesis Testing

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python">
  <img src="https://img.shields.io/badge/Excel-Analysis-green?logo=microsoft-excel">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas">
  <img src="https://img.shields.io/badge/SciPy-Statistics-orange">
  <img src="https://img.shields.io/badge/Status-Completed-success">
</p>

---

## 📌 Project Overview

This project analyzes **1,579 used Tesla vehicle sales records from the United States** to identify the key factors associated with Tesla resale prices.

The analysis focuses on three major vehicle characteristics:

- 🚘 Vehicle Model
- 📅 Manufacturing Year
- 🛣️ Mileage

The project applies multiple statistical techniques to understand pricing patterns and determine whether these factors are significantly associated with resale price.

### Research Question

> **What factors significantly influence the resale price of Tesla vehicles?**

The analysis was conducted as part of a **Business Analytics academic project at SCMHRD**.

---

## 🎯 Project Objectives

1. Analyze the distribution and variation of Tesla resale prices.
2. Examine the relationship between mileage, vehicle year, and resale price.
3. Measure the strength and direction of relationships using correlation analysis.
4. Perform simple regression to examine individual relationships with resale price.
5. Build a multiple regression model using model, year, and mileage.
6. Test whether resale prices differ across Tesla models.
7. Apply both parametric and non-parametric hypothesis testing.
8. Translate statistical findings into relevant business implications.

---

## 📊 Dataset

### Dataset Name

**Daily Used Tesla Car Sales for United States**

### Dataset Source

The dataset was obtained through **Kaggle** and was published by **Saturn Data Cloud**.

The publisher describes the underlying data as daily used Tesla vehicle sales data collected from publicly available Tesla.com listings.

### Dataset Size

- **Records:** 1,579
- **Variables:** 16
- **Period:** August 2022
- **Geography:** United States

### Key Variables

| Variable | Description |
|---|---|
| `vin` | Vehicle Identification Number |
| `year` | Manufacturing year |
| `model` | Tesla vehicle model |
| `color` | Exterior color |
| `miles` | Vehicle mileage |
| `trim` | Vehicle trim |
| `sold_price` | Used vehicle selling price |
| `interior` | Interior specification |
| `wheels` | Wheel specification |
| `features` | Vehicle features |
| `country` | Country |
| `location` | Vehicle location |
| `metro` | Metropolitan area |
| `state` | U.S. state |
| `currency` | Currency |
| `sold_date` | Sale date |

---

# 🔬 Methodology

The project uses a combination of descriptive, inferential, and predictive statistical techniques.

### Analytical Framework

```text
                    Tesla Used Car Dataset
                             │
                             ▼
                    Data Preparation
                             │
                             ▼
                  Descriptive Statistics
                             │
                ┌────────────┴────────────┐
                ▼                         ▼
          Visualization             Correlation
                                          │
                                          ▼
                                  Simple Regression
                                          │
                                          ▼
                                 Multiple Regression
                                          │
                         ┌────────────────┴───────────────┐
                         ▼                                ▼
                       ANOVA                       Kruskal–Wallis
                         │                                │
                         └────────────────┬───────────────┘
                                          ▼
                               Integrated Findings
                                          │
                                          ▼
                              Business Implications
