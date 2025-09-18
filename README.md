# 📊 Telco Customer Churn Analysis & Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow) 
![Python](https://img.shields.io/badge/Language-Python-blue) 
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## 📌 Project Overview
This project analyzes customer churn for a fictional Telco company.  
The goal is to **identify key drivers of churn** and present insights in both **Python (EDA)** and a **Power BI dashboard**.  

Churn is a critical business problem — retaining customers is often cheaper than acquiring new ones.  
By understanding the factors influencing churn, businesses can reduce customer loss and improve profitability.

---

## 🗂️ Dataset
- **Source**: Telco Customer Churn dataset (CSV file).  
- **Rows**: ~7,000 customers  
- **Columns**: Customer demographics, account information, services subscribed, billing, and churn status.  
- **Target Variable**: `Churn` (Yes/No)

Key fields include:
- **Demographics**: Gender, SeniorCitizen, Partner, Dependents  
- **Services**: InternetService, OnlineSecurity, StreamingTV, etc.  
- **Billing**: Contract, PaymentMethod, MonthlyCharges, TotalCharges  
- **Tenure**: Number of months customer stayed with the company  

---

## 🔧 Tools & Technologies
- **Python** → Data cleaning, preprocessing, and exploratory data analysis (EDA)  
- **Pandas, Matplotlib, Seaborn** → Data wrangling & visualization  
- **Power BI** → Interactive dashboard for churn analysis  
- **DAX** → Custom measures (Churn Rate, Avg Tenure, etc.)

---

## 📊 Power BI Dashboard
The interactive dashboard highlights:
1. **KPIs**: Total Customers, Churn Rate, Avg Tenure, Avg Monthly Charges  
2. **Churn Distribution**: Percentage of customers who left vs stayed  
3. **Churn by Contract**: Month-to-month customers show the highest churn  
4. **Churn by Internet Service**: Fiber optic users are most likely to churn  
5. **Payment Method**: Electronic check has the highest churn rate  
6. **Heatmap**: Churn % by Contract & Internet Service  
7. **Customer Detail Drillthrough**: View churn risk by individual customer  

📸 *Screenshots of the dashboard should be added here* (replace with your PNG files).  

---

## 📈 Key Insights
- Churn rate is **~26–27%** (1 in 4 customers leaves).  
- **Month-to-month contracts** → highest churn, long-term contracts → lowest churn.  
- **Fiber optic users** churn more compared to DSL users.  
- **Electronic check payments** are strongly linked with churn.  
- Customers with **higher monthly charges** and **lower tenure** are more likely to churn.  

---

## 🎯 Business Recommendations
- Promote **long-term contracts** with discounts.  
- Focus retention on **fiber optic users, senior citizens, and electronic check payers**.  
- Improve **new customer onboarding** (early tenure customers churn more).  
- Review **pricing strategy** for high-charge plans.  

---

## 🚀 How to Run the Project
1. **Python EDA Notebook**
   - Open `Telco_Customer_Churn_Analysis.ipynb`  
   - Run step-by-step to see data cleaning, visualizations, and insights  

2. **Power BI Dashboard**
   - Open `Telco_Customer_Churn.pbix` in Power BI Desktop  
   - Interact with slicers (Contract, InternetService, Gender, etc.)  

---

## 📂 Repository Structure
