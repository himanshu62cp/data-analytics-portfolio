---

## Tools & Skills Used
- **Programming:** Python (pandas, numpy)
- **Data Analysis:** Exploratory Data Analysis (EDA)
- **Machine Learning:** Random Forest Classifier
- **Model Evaluation:** Accuracy, ROC-AUC, Confusion Matrix
- **Business Skills:** Hypothesis testing, feature interpretation, executive summary writing

---

## Approach
1. Performed exploratory data analysis to understand customer behavior and pricing patterns  
2. Engineered features related to price sensitivity, consumption, margins, and customer tenure  
3. Trained a Random Forest classification model to predict customer churn  
4. Evaluated model performance using appropriate classification metrics  
5. Interpreted results to assess the role of price sensitivity in driving churn

---

## Key Results & Insights
- The churn prediction model achieved **~90% accuracy** with a **ROC-AUC of ~0.66**, indicating moderate but meaningful ability to distinguish churners from non-churners.
- Feature importance analysis showed that **net margin and energy consumption over 12 months** are the strongest drivers of churn.
- **Margin on power subscription** and **time-based factors** (customer tenure, months active, and time since last contract update) are also highly influential.
- **Price sensitivity is not the primary driver of churn**. Pricing-related features contribute to the model but act as **secondary factors** rather than dominant drivers.
- The engineered price sensitivity features validated the hypothesis that pricing plays a role in churn, but further experimentation is required to fully understand its interaction with other drivers.

---

## Business Takeaways
- Retention strategies focused solely on price discounts are unlikely to significantly reduce churn.
- Customers with **high consumption, high margin impact, and approaching contract renewal** should be prioritized for proactive retention efforts.
- The model provides a strong baseline for identifying at-risk customers and can be enhanced with additional features or tuning for improved performance.

