📊 Customer Churn & Risk Analysis | Power BI
📌 Project Overview

Customer churn is one of the most critical challenges for subscription-based businesses. This project analyzes customer churn patterns using the Telco Customer Churn dataset, focusing on who is leaving, why they are leaving, and how much revenue is at risk.

The project is built using Power BI, with strong emphasis on:

Churn behavior analysis

Revenue impact quantification

Identification of high-risk customer segments

The solution is divided into two focused dashboards:

Customer Churn Analysis

Customer Risk Analysis

📂 Dataset

Source: Telco Customer Churn (Kaggle)

Records: 7,043 customers

Key Fields:

Churn status

Tenure

Monthly & Total charges

Contract type

Payment method

Internet service

Subscribed services

🧹 Data Preparation & Modeling

Data preparation was performed using Power Query, including:

Cleaning and converting TotalCharges

Creating a binary churn indicator

Bucketing customers into tenure groups

Handling missing and inconsistent values

Key DAX Measures

Total Customers

Churned Customers

Churn Rate (%)

Total Revenue

Revenue Lost (Churned)

Average Monthly Charges (Churned vs Retained)

The model was intentionally kept simple and readable to ensure interpretability and performance.

📊 Dashboard 1: Customer Churn Analysis

Objective: Understand overall churn trends and quantify business impact.

Key Insights Provided

Overall churn rate and total churned customers

Revenue lost due to churn

Churn distribution across tenure groups

Churn rate by contract type

Comparison of average monthly charges between churned and retained customers

Impact of subscribed services on churn behavior

Business Value

This dashboard answers:

How severe is churn?

Which customer lifecycle stage is most vulnerable?

Which contracts and services drive higher churn?

🚨 Dashboard 2: Customer Risk Analysis

Objective: Identify high-risk customer segments and revenue exposure.

Key Insights Provided

Churn concentration by:

Payment method

Internet service type

Contract type

Customer distribution across services

Monthly charge exposure by internet service

Revenue at risk from churned customers

High-risk customer profiles using slicers and filters

Business Value

This dashboard helps decision-makers:

Pinpoint churn hotspots

Prioritize retention strategies

Target high-risk customers before revenue loss occurs

🧠 Key Findings

Month-to-month contracts have significantly higher churn

Fiber optic customers contribute the most to churn-related revenue loss

Early-tenure customers are the most vulnerable

Customers with higher monthly charges churn at a higher rate

Lack of support services (Tech Support, Online Security) correlates with churn

🛠 Tools & Technologies

Power BI Desktop

Power Query

DAX

Data Modeling

Interactive Visual Analytics

📈 Skills Demonstrated

Business-oriented data analysis

Churn and retention analytics

Revenue impact assessment

Dashboard design & storytelling

Data cleaning and transformation

KPI creation using DAX

📌 Conclusion

This project demonstrates how raw customer data can be transformed into actionable insights that directly support customer retention and revenue protection strategies. The dashboards are designed for both executive overview and operational risk analysis, making them suitable for real-world business use.
