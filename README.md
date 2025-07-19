# 📊 Telecom Churn Analysis Dashboard

## 📄 Project Description

This project analyzes customer churn behavior for a telecom company using an interactive Power BI dashboard. The aim is to identify churn drivers such as contract types, billing methods, internet services, and customer tenure. The insights help in building strategies to retain customers and improve service satisfaction.

---

## Dashboard Preview

<img width="1724" height="831" alt="Image" src="https://github.com/user-attachments/assets/8334a6ab-4728-4fbb-8136-cc9f4b20fb73" />
---

##  Table of Contents

1. [✨ Key Features](#-key-features)  
2. [📁 Files Included](#-files-included)   
3. [📈 Business Insights from the Dashboard](#-business-insights-from-the-dashboard)  
4. [📊 Visuals Used & Their Purpose](#-visuals-used--their-purpose)  
5. [✅ Overall Recommendations](#-overall-recommendations)  
6. [🛠 Tools & Skills Used](#-tools--skills-used)  
7. [📂 About the Dataset](#-about-the-dataset)  
8. [📬 Contact](#-contact)

---

## ✨ Key Features

- Dynamic dashboard to explore customer churn patterns.
- Slicers to filter by gender, contract, and payment method.
- Churn analysis by tenure, monthly charges, and service type.
- Color-coded visuals for intuitive storytelling.
- Key metrics like total churn rate, customer count, and churn breakdown.

---

## 📁 Files Included

- Telecom_Churn_Analysis.pbix – Power BI dashboard file  
- telecom_customer_churn.csv – Raw dataset used  
- README.md – Full documentation (this file)

---

1. Clone the repository:
   ```bash
   https://github.com/Adarshvr-96/Churn-Analysis
 

## 📈 Business Insights from the Dashboard

## 🧑‍🤝‍🧑 New Customers Have High Churn

The highest churn rate is seen in customers with 0–12 months tenure, especially the first 1–3 months.

Indicates poor onboarding or early dissatisfaction.


### 💸 Monthly Charge Drives Churn

Churn rate is:

20% for customers charged $0–$25

>70% for customers charged $75–$100

76% for customers charged over $100


Suggests customers with higher bills are more likely to leave.


### 🌐 Internet Service Matters

Fiber optic users have the highest churn rate (~41.9%).

DSL users show better retention.


### 🧾 Payment Method Insight

Electronic Check users have a churn rate of 45.3%, the highest among all methods.

Automatic payment methods like Credit Card or Bank Transfer have lower churn.


### 📝 Contract Type Insight

Month-to-Month contracts show a churn rate of 51%

One-Year: ~11% churn

Two-Year: ~2.8% churn

Shorter contracts lead to higher churn.



---

### 📊 Visuals Used & Their Purpose

Visual	Purpose

KPI Cards	Show Total Customers, Churned Customers, and Churn Rate instantly

Stacked Bar: Tenure vs Churn	Shows retention/churn across tenure groups


Bar: Internet Service Type vs Churn	Highlights which service types are prone to churn


Doughnut: Gender-wise Churn	Displays churn distribution across male/female


Bar: Payment Method	Compares churn rates based on how customers pay


Bar: Contract Type	Shows churn likelihood by contract duration


Combo Chart: Monthly Charges vs Churn	Reveals how billing amount affects churn behavior

---

### Detailed Explantion for Tenure Group 0-12 Months

<img width="1549" height="759" alt="Image" src="https://github.com/user-attachments/assets/5b8bc7fd-437e-48c2-970d-6ab9a13b4f73" />

## Observation:

From the dashboard analysis, it is evident that the highest churn rate is among new members (those with a tenure of 0–12 months). This group shows a significant portion of overall churn.

Additionally, when analyzing churn by monthly charges, customers paying between ₹75–₹100 and above ₹100 experience churn rates above 70%, while customers with lower monthly charges (₹0–₹25) have a much lower churn rate of only 20%.

Looking deeper into service preferences, new members using Fiber Optic Internet service show a notably high churn rate. Similarly, customers who use Electronic Check as their payment method are also more likely to churn.

Lastly, the churn rate is highest among customers on Month-to-Month contracts, with 51% churn, which is significantly higher compared to those on One-Year contracts.

---

## ✅ Overall Recommendations

#### 1. Improve Onboarding & Early Experience

New users churn more → Offer better welcome kits, support, and engagement.



#### 2. Encourage Long-Term Contracts

Provide discounts or rewards for upgrading from month-to-month to yearly plans.



#### 3. Review High Monthly Bill Plans

Offer loyalty perks or flexible pricing for high-paying users.



#### 4. Target Fiber Optic Users for Retention

Collect feedback and improve service reliability.



#### 5. Promote Auto-Pay Options

Reduce churn by promoting credit card or bank transfer over electronic checks.





---

### 🛠 Tools & Skills Used

Power BI – Data Modeling, DAX, Visuals, Relationships

Power Query – Data cleaning and transformation

Data Analysis – Exploratory analysis, trend spotting

Dashboard Design – Clean UI, storytelling approach

Churn Modeling – Understanding and interpreting churn patterns



---

## 📂 About the Dataset

Source: Public telecom churn dataset (Kaggle)

Rows: 7,043 customer records

Columns Include:

Customer ID

Gender

Senior Citizen

Tenure

Internet Service

Contract Type

Monthly Charges

Payment Method

Churn (Yes/No)




---

📬 Contact

Author: Adarsh Reji
📧 Email: adarshvr67@gmail.com

🔗 GitHub: https://github.com/Adarshvr-96

🌐 Portfolio: https://adarshvr-96.github.io/Portfolio


---

> ⭐ If you found this project useful, consider starring the repo or sharing feedback!



---
