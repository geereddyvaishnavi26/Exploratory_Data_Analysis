# Exploratory_Data_Analysis
# 📊 Telco Customer Churn Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Telco Customer Churn dataset to identify key patterns and factors that contribute to customer churn.  
The goal is to understand **customer behavior**, **service usage**, and **billing preferences** that influence whether a customer leaves the company.

The dataset contains **7,043 customer records** with **21 attributes**, covering demographics, services subscribed, and account-related details.

---

## 🎯 Objectives
- Identify factors influencing customer churn  
- Analyze customer demographics and service usage  
- Understand the impact of contract type and payment methods  
- Generate actionable business insights to reduce churn  

---

## 📂 Dataset Information
- **Total Records:** 7,043  
- **Total Features:** 21  
- **Target Variable:** `Churn` (Yes / No)

### Feature Categories
- **Demographics:** Gender, SeniorCitizen, Partner, Dependents  
- **Services:** PhoneService, InternetService, StreamingTV, TechSupport, etc.  
- **Account Info:** Contract, PaymentMethod, PaperlessBilling, MonthlyCharges, TotalCharges  

---

## 🛠️ Data Cleaning & Preprocessing
- Handled missing/blank values in `TotalCharges` by replacing them with `0` and converting the column to `float`
- Converted binary values in `SeniorCitizen` (0/1) to `Yes/No`
- Verified **no missing values** after cleaning
- Checked and confirmed **no duplicate CustomerID values**

---

## 📈 Exploratory Data Analysis
### Statistical Insights
- **Average tenure:** ~32 months  
- **Average monthly charges:** $64.76  
- **MonthlyCharges range:** $18.25 – $118.75  
- **Maximum TotalCharges:** $8,684.80  

### Analysis Performed
- Churn distribution analysis  
- Churn vs demographic factors  
- Churn vs service subscriptions  
- Churn vs contract types  
- Churn vs payment methods  

---

## 📊 Visualizations
- Count plots for churn comparison  
- Churn analysis across payment methods  
- Contract type vs churn distribution  
- Bar charts with value labels for clarity  

**Libraries Used:**
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

---

## 🔍 Key Insights
- Customers on **month-to-month contracts** show higher churn rates  
- **Electronic check** payment method is strongly associated with churn  
- Customers with **longer tenure** are less likely to churn  
- Value-added services (Tech Support, Online Security) may reduce churn  

---

## 📁 Project Structure
📦 Telco-Customer-Churn-EDA
├── data/
│ └── Telco-Customer-Churn.csv
├── notebooks/
│ └── churn_analysis.ipynb
├── images/
│ └── visualizations.png
├── README.md
└── requirements.txt


🚀 Future Improvements

- Feature engineering (CLV, tenure groups)

- Predictive modeling (Logistic Regression, Random Forest)

- Churn probability dashboard (Power BI / Streamlit)



  📌 Conclusion

This EDA provides meaningful insights into customer churn behavior and helps businesses design effective retention strategies using data-driven decisions.



📬 Contact

Author: Vaishnavi Reddy
📧 Feel free to connect on LinkedIn or GitHub
