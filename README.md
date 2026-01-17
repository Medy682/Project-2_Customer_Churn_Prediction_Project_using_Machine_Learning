
Customer Churn Prediction using Machine Learning

✅ Project Overview

Customer churn is a major challenge for subscription-based businesses, where losing existing customers can significantly impact revenue.  
This project builds an end-to-end machine learning pipeline to predict customer churn and demonstrate how predictive insights can support proactive retention strategies.

The project follows a structured data science workflow, from business understanding and exploratory data analysis (EDA) to model evaluation and business impact interpretation.

---

✅ Business Objective

The goal of this project is to identify customers who are at risk of churning so that the business can take early retention actions such as discounts, loyalty incentives, or proactive engagement.

Given the higher cost of losing a customer compared to contacting a loyal one, recall for churned customers was prioritised during model evaluation.

---

✅ Dataset

- Simulated customer churn dataset sourced from Kaggle  
- Originally used for academic coursework  
- Represents common customer behaviour patterns in subscription-based businesses  

While the data does not belong to a real organisation, it is suitable for demonstrating churn prediction techniques and decision-making logic.

---

✅ Methodology

The project follows these steps:

1. Business understanding and problem framing  
2. Data cleaning and preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature engineering  
5. Train-test split to prevent data leakage  
6. Scaling and encoding using `ColumnTransformer.`  
7. Model training and optimisation using GridSearchCV  
8. Model evaluation using classification metrics  
9. Business impact analysis and decision threshold discussion  

---

✅ Models Trained

Three machine learning models were evaluated:

- Logistic Regression  
- Random Forest  
- XGBoost  

In addition to accuracy, precision, recall, F1-score, and ROC AUC were used to evaluate the effectiveness of each model in identifying churned customers

---

✅ Model Performance Summary

- **XGBoost** achieved the highest recall, F1-score, and ROC-AUC, making it the strongest overall performer for churn detection and ranking customers by churn risk.
- **Random Forest** achieved the highest precision, indicating a conservative approach that minimises false positives.
- **Logistic Regression** offered interpretability but showed limited recall compared to the other models.

Model selection was aligned with business objectives rather than accuracy alone.

---

✅ Business Impact

Assuming a customer base of 5,000 with a 20% churn rate:
- The XGBoost model correctly identifies approximately 43% of churners (≈430 customers).
- If 50% of these identified customers are successfully retained, approximately 215 customers could be saved.
- With an estimated customer value of R2,000 per year, this translates to potential annual savings of approximately **R430,000**.

---

✅ Limitations & Future Improvements

- The dataset is simulated and does not include customer lifetime value (CLV).
- Future improvements could include CLV-based prioritisation, threshold optimisation using business costs, and real-time deployment.

---

 🛠️ Tools & Technologies

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost
-logistic regression
-Random Forest 

---

👨‍🎓 Author

**Kidima Medy Masuka**  
Aspiring Data Scientist | Data Analyst  

Focused on data-driven decision-making, risk analytics, and machine learning


Usage & Attribution

This project is shared for educational and portfolio purposes.  
If reused or adapted, appropriate credit must be given to the author.

📰This project is part of my personal data science portfolio ✅
