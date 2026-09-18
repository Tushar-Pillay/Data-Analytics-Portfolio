# 📱 Product Sentiment Analysis & Feature Roadmap Prioritization | FitLife

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![NLTK](https://img.shields.io/badge/NLTK-NLP-green?style=for-the-badge)
![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikit-learn)
![VADER](https://img.shields.io/badge/VADER-Sentiment%20Analysis-red?style=for-the-badge)

</p>

---

# 📖 Project Overview

This project focuses on **Product Sentiment Analysis and Feature Roadmap Prioritization** for Health & Fitness applications using Python.

User reviews from Google Play Store are analyzed to understand **customer sentiment, frequently discussed topics, and potential product improvement areas**.

The project combines **VADER Sentiment Analysis, TF-IDF feature extraction, and the RICE prioritization framework** to convert customer feedback into actionable business insights.

---

# 🎯 Objectives

- Analyze user reviews of Health & Fitness applications.
- Classify reviews into Positive, Negative, and Neutral sentiments.
- Identify important terms and topics using TF-IDF.
- Prioritize potential improvement areas using the RICE framework.
- Generate data-driven product recommendations.

---

# 📂 Dataset Information

**Dataset Name:**  
Google Play Store Apps and Reviews Dataset

**Application Category:**  
Health & Fitness

**Health & Fitness Apps:** 254

**Top Apps Selected:** 30

**Apps with Matched Reviews:** 8

**Final Reviews Analyzed:** 272

**Average Review Length:** 147.33 characters

### Review Features

- App
- Translated Review
- Sentiment
- Sentiment Polarity
- Sentiment Subjectivity

---

# 📁 Project Files & References

The data for this project is sourced from Kaggle:

#### 🔗 Dataset Link:
[Google Play Store Apps Dataset](https://www.kaggle.com/datasets/lava18/google-play-store-apps)
The dataset contains Google Play Store application information and user reviews.

### 🐍 Python Analysis
- [Python Project File / Jupyter Notebook](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Python/Google-Play-Store-App-Sentiment-Analysis/Python%20file.ipynb)

### 📄 Project Report
- [Final Project Report](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Python/Google-Play-Store-App-Sentiment-Analysis/Product_Sentiment_Analysis_Final_Report.pdf)

### 📝 Project Synopsis
- [Project Synopsis](./Product_Sentiment_Analysis_Synopsis.pdf)

### 📊 Project Presentation
- [Project PPT](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Python/Google-Play-Store-App-Sentiment-Analysis/Product_Sentiment_Analysis_Project_Presentation.pdf)

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK / VADER
- Scikit-learn
- Jupyter Notebook / Google Colab

---

# ⚙️ Project Workflow

## Data Collection

- Imported Google Play Store application and review datasets.
- Selected applications from the **Health & Fitness** category.

## Data Cleaning

- Removed missing reviews.
- Removed duplicate reviews.
- Removed very short reviews.
- Cleaned application data.

## Review Selection

- Selected the top 30 Health & Fitness applications based on review count.
- Matched available reviews with the selected applications.
- Final dataset contained 272 reviews from 8 applications.

## Sentiment Analysis

Used **VADER Sentiment Analysis** to classify reviews into:

- Positive
- Negative
- Neutral

## Feature Extraction

Used **TF-IDF (Term Frequency–Inverse Document Frequency)** to identify important terms from user reviews.

## Feature Prioritization

Used the **RICE Framework**:

to prioritize extracted terms.

---

# 🔍 Key Findings

## 😊 Sentiment Analysis

Out of 272 reviews:

- Positive: **192 (70.6%)**
- Negative: **50 (18.4%)**
- Neutral: **30 (11.0%)**

The majority of analyzed reviews were positive.

## 📝 Review Analysis

The average review length was approximately:

**147.33 characters**

## 🔤 TF-IDF Analysis

Important terms identified included:

- App
- Like
- Great
- Good
- Day
- Work
- Easy
- Love
- Track
- Workout
- Calories
- Food

## 📊 RICE Prioritization

The RICE framework was applied to the top TF-IDF terms.

The highest RICE scores were associated with frequently occurring terms such as:

- App
- Work
- Like
- Great
- Day

> Note: Impact, Confidence, and Effort were kept constant in this analysis, so the RICE ranking is primarily influenced by Reach.

---

# 💡 Business Insights

## 📱 Product Improvement

Frequently discussed terms can help identify areas that users commonly mention in their reviews.

## 😊 Customer Experience

Sentiment analysis helps understand whether users are generally satisfied or dissatisfied with the application.

## 🎯 Feature Prioritization

RICE provides a structured framework for prioritizing areas based on their potential reach and assumed impact.

## 📊 Data-Driven Decisions

Combining sentiment analysis, TF-IDF, and RICE helps transform unstructured customer reviews into structured product insights.

---

# 🧠 Methodology

The project follows the pipeline:

```text
Data Collection
       ↓
Data Cleaning
       ↓
Health & Fitness Filtering
       ↓
Top 30 Application Selection
       ↓
Review Matching
       ↓
Review Analysis
       ↓
VADER Sentiment Analysis
       ↓
TF-IDF Feature Extraction
       ↓
RICE Prioritization
       ↓
Business Insights


