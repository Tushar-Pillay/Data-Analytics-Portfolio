# 📊 Milestone 3 – Churn Prediction Model & Risk Scoring

## 📌 Objective
Build a predictive model to identify at-risk customers and estimate the financial impact of proactive retention strategies.

---

## 📁 Repository Contents

- **[M3_Churn_Prediction.xlsx](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Excel/churn-telecom-analysis/milestone-3/M3_Churn_Prediction.xlsx)**  
  Contains cleaned data, engineered features, pivot-table analysis, and churn segmentation outputs.

- **[M3_Prediction_Report.pdf](https://github.com/Tushar-Pillay/Data-Analytics-Portfolio/blob/main/Excel/churn-telecom-analysis/milestone-3/M3_Prediction_Report.pdf)**  
  A detailed analytical report covering methodology, visualizations, insights, and business interpretations.
  
---

## 🛠 Feature Engineering
Created new predictive variables:

- Tenure_Category (New, Developing, Established, Loyal)
- Contract_Risk (Month-to-month = High Risk)
- Payment_Risk
- Service_Engagement
- Price_per_Service
- Has_Family (0/1)
- Is_Senior (0/1)
- One-hot encoded categorical variables
- Standardized numerical features (Z-score scaling)

Both qualitative (contract, payment, service type) and quantitative (tenure, charges) factors were incorporated.

---

## 🤖 Model Development
- Model: Logistic Regression
- Train/Test Split: 70% / 30%
- Dataset Distribution:
  - Retained: 73.46%
  - Churn: 26.54%
- Multiple thresholds tested: 0.3, 0.5, 0.7
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score, ROC, AUC

---

## 📈 Model Performance

| Threshold | Recall | FPR | Interpretation |
|------------|--------|------|----------------|
| 0.5 | 96% | 90% | High recall, many false positives |
| 0.7 | 29% | 37% | Conservative, misses churners |
| AUC | 0.483 | - | Poor predictive power |

⚠️ The model shows limited discrimination (AUC < 0.5), requiring improvement.

---

## 🔍 Key Predictors
Top churn drivers:
1. Month-to-Month Contract
2. Electronic Check Payment
3. No Tech Support
4. No Online Security
5. Short Tenure
6. Senior Citizen Status

Protective factors:
- Automatic Payment
- Higher Service Engagement
- Family Presence

---

## 🎯 Customer Risk Scoring
Risk Score = Churn Probability × 100

| Risk Level | Score Range | Action |
|------------|------------|--------|
| High Risk | 70–100 | Immediate retention |
| Medium Risk | 40–70 | Proactive engagement |
| Low Risk | 0–40 | Standard monitoring |

Segments analyzed for customer count, churn probability, CLV, and revenue at risk.

---

## 💰 Business Impact & ROI

### Assumptions:
- Model Recall: 75%
- Retention Success Rate: 40%
- Retention Cost per Customer: ₹500
- Average CLV: ₹4,000

### Results:
- Customers Identified: 1,372
- Customers Saved: 549
- Revenue Saved: ₹21.94 lakhs
- Program Cost: ₹6.85 lakhs
- Net Benefit: ₹15.08 lakhs
- ROI: 220%

📌 Predictive retention delivers strong financial impact.

---

## ⚠️ Model Limitations
- Low AUC score
- Limited behavioral features
- Logistic regression assumptions
- Class imbalance impact
  
---

## 🚀 Recommendations
- Add behavioral & usage features
- Optimize threshold for higher recall
- Deploy in pilot phase before scaling

