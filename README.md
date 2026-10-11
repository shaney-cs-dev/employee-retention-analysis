# employee-retention-analysis
Predicting employee attrition using HR analytics
# Employee Retention Analysis – Salifort Motors

## Overview
This project explores factors influencing employee attrition at Salifort Motors.  
The goal is to answer the question: **What’s likely to make an employee leave the company?**  
We use HR data to identify key drivers of turnover and provide actionable recommendations to improve retention.

---

## Methods
- **Exploratory Data Analysis (EDA):** Visualizations of satisfaction, workload, tenure, and department attrition.
- **Modeling Approaches:** Logistic Regression, Decision Tree, and Random Forest.
- **Evaluation Metrics:** Accuracy, precision, recall, F1‑score, and confusion matrix.
- **Feature Importance:** Random Forest identified `last_evaluation`, `tenure`, `number_project`, `overworked`, `salary_low`, and `work_accident` as most predictive.

---

## Key Insights
- **Satisfaction level** is the strongest predictor of attrition.
- **Workload imbalance** (too few or too many projects/hours) increases turnover risk.
- **Tenure effect:** Employees around 4 years of service show higher dissatisfaction.
- **Salary:** Low salary groups are more likely to leave.
- **Evaluation scores:** High scores tied only to extreme workloads can demotivate others.

---

## Recommendations
- Cap the number of projects per employee to prevent overload.
- Investigate dissatisfaction among 4‑year tenured employees; consider promotion or career development opportunities.
- Clarify overtime policies and workload expectations.
- Reward contributions proportionately, not just extreme hours.
- Hold company‑wide and team‑level discussions to improve work culture.

---

## Files Included
- `employee_retention.ipynb` → Full analysis and modeling notebook.
- `executive_summary.pptx` → Presentation summarizing findings and recommendations.
- `README.md` → Project documentation.

---

## Next Steps
- Compare logistic regression with ensemble models for improved accuracy.
- Address class imbalance to better capture attrition cases.
- Extend analysis to demographics, promotion history, and survival modeling.
