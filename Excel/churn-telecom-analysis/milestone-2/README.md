# 📊 Telecom Customer Churn Analysis – Milestone 2
## Engagement Analysis & Statistical Testing

---

## 📌 Project Overview
Milestone 2 focuses on understanding **customer engagement patterns** and **statistically validating churn drivers** for TeleConnect, a telecommunications provider.  
Building on customer segmentation from Milestone 1, this phase applies **CLV analysis, engagement metrics, hypothesis testing, churn journey analysis, correlation analysis, and persona development** to generate actionable business insights.

---

## 🎯 Objectives of Milestone 2
- Analyze **Customer Lifetime Value (CLV)** and revenue impact of churn
- Measure customer engagement using **ARPU, service usage, and stickiness**
- Perform **statistical hypothesis testing** to validate churn drivers
- Identify **critical churn periods** across customer tenure
- Analyze **feature correlations** with churn
- Develop **customer personas** for targeted retention strategies
- Translate insights into **actionable retention recommendations**

---

## 📂 Dataset Description
- **Source:** Telecom Customer Churn Dataset
- **Records:** 7,043 customers
- **Key Variables:**
  - Demographics (gender, senior citizen, family status)
  - Services (internet, security, backup, streaming, support)
  - Account details (tenure, contract type, payment method)
  - Pricing (monthly charges, total charges)
  - Target variable: **Churn (Yes/No)**

---

## 🔢 Customer Lifetime Value (CLV) Analysis
- **Historical CLV:** Calculated using `TotalCharges`
- **Predicted CLV:** Estimated using monthly charges and expected lifetime
- CLV compared across:
  - Churned vs retained customers
  - Contract types
  - Engagement levels

**Key Finding:**  
Retained customers generate significantly higher CLV than churned customers. Long-term contracts contribute the highest lifetime value, while month-to-month customers show the greatest revenue risk.

---

## 📈 Engagement Metrics & Stickiness Analysis
- **ARPU (Average Revenue Per User):** Churned customers pay higher monthly charges but exit earlier
- **Service Count:** Slightly higher for retained customers, but not statistically significant
- **Stickiness Score:** Derived from contract duration, payment automation, and add-on services

**Key Finding:**  
Customers with higher stickiness (long-term contracts, automatic payments, support/security services) exhibit substantially lower churn.

---

## 🧪 Hypothesis Testing & Statistical Validation
The following statistical tests were conducted:

| Test | Variables | Test Type | Result |
|----|----------|----------|--------|
| Test 1 | Monthly Charges vs Churn | Two-sample t-test | Significant |
| Test 2 | Contract Type vs Churn | Chi-square test | Significant |
| Test 3 | Payment Method vs Churn | Chi-square test | Significant |
| Test 4 | Service Count vs Churn | ANOVA | Not Significant |

**Insight:**  
Pricing pressure, contract flexibility, and payment convenience are strong churn drivers, while the number of services alone does not significantly impact churn.

---

## 🚶 Churn Journey & Critical Periods
- Churn is **highest in the first 1–6 months** (above 45–60%)
- Churn steadily declines after 6 months and stabilizes over time
- Customers with **25+ months tenure** show very low churn (<15%)
- Minor churn spikes observed around **contract renewal points**

**Key Insight:**  
Early tenure is the most critical churn window and offers the highest ROI for retention efforts.

---

## 🔗 Feature Correlation Insights
Top correlations with churn:
- **Stickiness Score:** Moderate negative correlation
- **Tenure:** Moderate negative correlation
- **Monthly Charges:** Weak positive correlation
- **Total Charges:** Weak negative correlation
- **Service Count:** Negligible correlation

**Conclusion:**  
Engagement quality and tenure matter more than service quantity.

---

## 👥 Customer Persona Development
Customers were grouped into four personas:

| Persona | Customer Share |
|------|---------------|
| At-Risk Budget User | 27.94% |
| Value Seeker | 30.41% |
| Loyal Family User | 8.80% |
| Others | 32.84% |

Personas were defined using tenure, stickiness, pricing sensitivity, contract type, and payment behavior.

---

## 🎯 Retention Strategy Implications
- Focus retention efforts on **early-tenure customers**
- Encourage **long-term contracts** and **automatic payments**
- Promote **support and security services** to increase stickiness
- Use **persona-based offers** instead of uniform discounts
- Protect high-CLV customers with loyalty and upgrade programs

---

## 📊 Visualizations Included
- CLV comparison (Box plot)
- Churn journey by tenure (Line chart)
- Service adoption (Stacked bar chart)
- Stickiness score vs churn (Bar chart)
- Persona distribution (Pie chart)

---

## 🛠 Tools & Technologies Used
- **Microsoft Excel**
  - Pivot Tables
  - Data Analysis ToolPak
  - Statistical Tests
  - Charts & Visualizations

---

