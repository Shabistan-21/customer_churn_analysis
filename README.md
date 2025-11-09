# Customer Churn Analysis & Prediction

## Overview
This project analyzes customer churn data from a telecom company to understand **why customers leave** and **predict who is likely to churn**.  
The insights can help improve retention strategies and reduce revenue loss.

---

## Project Structure
customer_churn_analysis/
├── data/
│ └── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── notebooks/
│ ├── 01_EDA_Churn_Analysis.ipynb
│ └── 02_Modeling_Churn_Prediction.ipynb
├── README.md
└── requirements.txt


##  Exploratory Data Analysis (EDA)
- Cleaned missing and inconsistent data  
- Examined churn distribution  
- Analyzed churn by gender, contract, payment method, monthly charges, and tenure  
- Found patterns showing **month-to-month contracts** and **higher monthly charges** increase churn


##  Modeling
- Encoded categorical features using Label Encoding  
- Trained multiple models:
  - Logistic Regression → baseline
  - Random Forest → best performance
- Evaluated with Accuracy, Precision, Recall, F1-score, ROC-AUC

**Sample Results:**
| Model | Accuracy | Precision | Recall | F1-score |
|-------|-----------|------------|---------|-----------|
| Logistic Regression | 0.79 | 0.72 | 0.68 | 0.70 |
| Random Forest | 0.83 | 0.77 | 0.74 | 0.75 |


##  Business Impact
- Identifying at-risk customers enables **targeted retention offers**.  
- Focus on **month-to-month** customers with **high charges** to reduce churn.  
- Insights can reduce churn rate by strategic interventions.


##  Tools & Libraries
- Python (pandas, numpy, matplotlib, seaborn)
- scikit-learn
- Jupyter Notebook


##  Next Steps
- Deploy model via Streamlit dashboard  
- Automate data pipeline with Airflow  
- Add SHAP analysis for explainability


Author: Shabistan Urankar
