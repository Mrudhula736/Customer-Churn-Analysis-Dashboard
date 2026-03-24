# 📊 Customer Churn Analysis Dashboard (Power BI)

## 📌 Project Overview

This project focuses on analyzing customer churn behavior in a telecom company using Power BI. The objective is to identify key factors influencing customer churn and provide actionable insights to improve customer retention and business performance.

---

## 🎯 Objectives

* Analyze customer demographics and behavior
* Identify key drivers of customer churn
* Evaluate the impact of services, contracts, and billing on churn
* Provide data-driven insights to reduce churn and improve retention

---

## 📂 Dataset Description

The dataset contains customer-level information including:

* **Demographics:** Gender, Senior Citizen, Partner, Dependents
* **Account Information:** Tenure, Contract Type, Payment Method
* **Services:** Phone Service, Internet Service, Add-ons (Security, Backup, etc.)
* **Billing:** Monthly Charges, Total Charges, Paperless Billing
* **Target Variable:** Churn (Yes/No)

---

## 🧹 Data Cleaning & Transformation

* Converted `TotalCharges` to numeric and handled missing values
* Standardized categorical values (Yes/No format)
* Created new columns:

  * Tenure Group
  * Churn Flag
  * Senior Citizen Category
  * Total Services
* Removed inconsistencies and ensured data quality

---

## 📊 Dashboard Features

### 1️⃣ Customer Demographics Analysis

* Gender distribution of customers
* Senior citizen churn comparison
* Customer segmentation by tenure
* Churn trends across tenure groups
* Relationship between tenure and monthly charges

---

## 📈 Key Insights

* Customers with **short tenure (0–12 months)** have the highest churn rate
* **Month-to-month contracts** show significantly higher churn
* Customers without **tech support or online security** are more likely to churn
* **Senior citizens** tend to have a slightly higher churn rate
* Long-term customers exhibit **higher retention and loyalty**

---

## 🛠️ Tools & Technologies

* **Power BI** – Dashboard creation and data visualization
* **DAX** – Calculated columns and measures
* **Power Query** – Data cleaning and transformation

---

## 📌 Conclusion

This dashboard provides a comprehensive view of customer churn behavior, enabling businesses to identify at-risk customers and implement targeted retention strategies. The insights derived from this analysis can help improve customer satisfaction and reduce revenue loss.

---

## 🚀 Future Improvements

* Implement machine learning models for churn prediction
* Add real-time data integration
* Enhance dashboard interactivity with advanced filters

---

