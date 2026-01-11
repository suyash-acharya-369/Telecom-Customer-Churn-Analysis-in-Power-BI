# 📊 Customer Churn & Risk Analysis | Power BI

## 📌 Project Overview

Customer churn is one of the most critical challenges for subscription-based businesses.  
This project analyzes customer churn patterns using the **Telco Customer Churn dataset**, focusing on **who is leaving, why they are leaving, and how much revenue is at risk**.

The analysis is implemented in **Power BI** with an emphasis on business-driven insights rather than just visualizations.

The project consists of **two focused dashboards**:
1. **Customer Churn Analysis**
2. **Customer Risk Analysis**

---

## 📂 Dataset

- **Source:** Telco Customer Churn (Kaggle)
- **Total Records:** 7,043 customers
- **Key Attributes:**
  - Customer churn status
  - Tenure (customer lifetime)
  - Monthly & total charges
  - Contract type
  - Payment method
  - Internet service
  - Subscribed services

---

## 🧹 Data Preparation & Modeling

Data transformation was performed using **Power Query**, including:
- Cleaning and type conversion of `TotalCharges`
- Handling missing and inconsistent values
- Creating churn indicators
- Grouping customers into tenure buckets

### 🔢 Key DAX Measures
- Total Customers  
- Churned Customers  
- Churn Rate (%)  
- Total Revenue  
- Revenue Lost (Churned)  
- Average Monthly Charges (Churned vs Retained)

The data model was intentionally kept simple to ensure clarity, performance, and interpretability.

---

## 📊 Dashboard 1: Customer Churn Analysis

**Objective:** Analyze overall churn trends and quantify business impact.

### Key Insights
- Overall churn rate and churned customer count
- Revenue lost due to churn
- Churn distribution across tenure groups
- Churn rate by contract type
- Average monthly charges comparison (Churned vs Retained)
- Impact of subscribed services on churn behavior

### Business Questions Answered
- How severe is customer churn?
- Which customer lifecycle stage is most vulnerable?
- Which contracts and services are driving churn?

---

## 🚨 Dashboard 2: Customer Risk Analysis

**Objective:** Identify high-risk customer segments and revenue exposure.

### Key Insights
- Churn by payment method
- Churn by internet service type
- Churn by contract type
- Customer distribution across internet services
- Monthly charge exposure by service type
- Revenue at risk from churned customers

### Business Questions Answered
- Which customer segments pose the highest churn risk?
- Where is the maximum revenue leakage occurring?
- Which factors should retention strategies prioritize?

---

## 🧠 Key Findings

- Month-to-month contracts show the highest churn rates
- Fiber optic customers contribute the most to churn-related revenue loss
- Customers in early tenure stages are significantly more likely to churn
- Higher monthly charges correlate strongly with churn
- Lack of support services (Tech Support, Online Security) increases churn probability

---

## 🛠 Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Interactive Dashboards**

---

## 📈 Skills Demonstrated

- Customer churn analysis
- Revenue impact assessment
- Business-oriented dashboard design
- Data cleaning & transformation
- KPI development using DAX
- Analytical storytelling with visuals

---

## 📌 Conclusion

This project demonstrates how customer data can be transformed into **actionable insights** that support **customer retention and revenue protection strategies**.  
The dashboards are designed to serve both **executive-level overview** and **operatio**
