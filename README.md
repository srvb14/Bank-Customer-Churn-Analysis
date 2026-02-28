# Bank-Customer-Churn-Analysis
Exploratory Data Analysis (EDA) on bank churn dataset using Python, featuring quantile-based segmentation and multi-variable interaction analysis.

# Bank Customer Churn Analysis

## Project Overview

Customer churn is a critical problem in the banking industry as it directly impacts revenue and long-term growth.  

This project analyzes customer behavior data to identify key demographic and behavioral factors driving churn using Python-based exploratory data analysis (EDA).

The goal is to uncover high-risk customer segments and provide actionable retention insights through structured segmentation analysis.

---

## Dataset Information

- Total Records: **10,000 customers**
- Features: 14 demographic and behavioral attributes
- Target Variable: `Exited`
  - 1 → Customer churned
  - 0 → Customer retained
- Overall Churn Rate: **~20%**

---

## Key Objectives

- Identify high-risk churn segments
- Analyze demographic and behavioral churn patterns
- Perform quantile-based customer segmentation
- Compare churn intensity vs churn volume
- Generate actionable business insights

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**

---

## Analytical Framework

The project follows a KPI-driven exploratory data analysis framework:

1. **Define Core KPI**
   - Churn Rate (%)

2. **Univariate Analysis**
   - Age
   - Gender
   - Geography
   - Credit Score
   - Estimated Salary
   - Number of Products

3. **Bivariate Analysis**
   - Balance vs Churn
   - Activity Status vs Churn
   - Products vs Churn

4. **Quantile-Based Segmentation**
   - Balance Quartiles (Q1–Q4)
   - Salary Segmentation
   - Zero vs Non-Zero Balance Separation

5. **Multi-Dimensional Risk Profiling**
   - Female + Germany + Age > 45
   - Inactive + 1 Product
   - Balance × Activity interaction analysis

---

## Key Insights

### High-Risk Demographic Segment
- **Female customers in Germany above 45 years**
- Churn Rate: **66%**
- Over 3x higher than portfolio average (20%)

---

### High-Volume Structural Risk Segment
- **Inactive + Single Product customers**
- Churn Rate: **36%**
- 2,500+ customers in this segment
- Major contributor to overall churn volume

---

### Balance-Based Segmentation Insight
- Medium-balance inactive customers showed higher churn (~35%) than high-balance customers.
- Churn does not increase linearly with balance.
- Zero-balance customers had lower churn than expected.

---

### Weak Predictors
- Estimated Salary
- Credit Score
- Credit Card Ownership

These variables showed minimal impact on churn probability.

---

## Business Implications

- Customer inactivity is a stronger churn driver than income level.
- Moderate engagement customers are more unstable than high-balance premium customers.
- Retention efforts should prioritize:
  - Inactive single-product users
  - High-risk demographic clusters
- Segmentation-based targeting can reduce churn more effectively than blanket retention campaigns.

---

## Measurable Outcomes

- Identified a 66% churn micro-segment.
- Isolated a 36% churn high-volume customer segment.
- Demonstrated behavioral risk stacking through multi-variable interaction analysis.
- Translated data findings into retention-focused strategic recommendations.

---

## Future Improvements

- Predictive churn modeling (Logistic Regression / XGBoost)
- Customer Lifetime Value (CLV) analysis
- A/B retention strategy simulation
- Dashboard visualization (Power BI / Tableau)


