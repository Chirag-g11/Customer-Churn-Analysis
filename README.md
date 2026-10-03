# 📊 Customer Churn Prediction & Retention Analysis

An end-to-end data analytics project focused on analyzing telecom customer churn behavior, identifying key attrition drivers, and building an executive-level business intelligence dashboard to aid customer retention strategies.

---

## 🚀 Project Overview
Customer attrition (churn) is one of the most critical business challenges in subscription-based industries. This project analyzes the **Telco Customer Churn** dataset to uncover patterns related to customer contracts, tenure, demographics, and technical service adoption. The solution spans data cleaning, exploratory data analysis (EDA), relational database management via SQL, and an interactive 3-page dark-mode Power BI dashboard.

---

## 🛠️ Tech Stack & Tools
* **Programming Language:** Python (Pandas, NumPy, Matplotlib, Seaborn)
* **Database & Querying:** SQLite (SQL integration for data extraction and metrics aggregation)
* **Data Visualization & BI:** Power BI Desktop (DAX measures, custom multi-page dashboarding)
* **Version Control:** Git & GitHub

---

## 📂 Project Structure
```text
├── Datasets/
│   ├── Telco-Customer-Churn.csv              # Raw Dataset
│   └── Cleaned_telco_churn.csv               # Processed Dataset
├── Python/
│   └── Telco_Customer_Churn_EDA.ipynb        # Data Cleaning & Python EDA
├── Database/
│   └── telecom_churn_project.db              # SQLite Database
├── PowerBI/
│   └── Churn Prediction Analysis.pbix        # Power BI Multi-Page Report
├──Dashboards/                                # PowerBi Dashboard Images
|   ├── Executive Overview.png
|   └── Demographic Insights.png
|   └── Services and Add-ons.png
└── README.md
```
🔍 Key Phases & Methodology
Data Cleaning & Preprocessing (Python):

Handled missing values and converted data types (e.g., parsing TotalCharges into numeric format).

Created custom categorical indicators (Churn_Numeric) for aggregation and DAX metric calculations.

Database Integration & SQL Analysis:

Loaded the cleaned dataset into an SQLite database.

Executed SQL queries to compute segmented churn rates across various dimensions (Contract type, Payment methods, Tenure groups).

Power BI Executive Dashboard (3-Page Suite):

Page 1 (Executive Overview): High-level KPI cards (Total Customers, Churned Customers, Average Monthly Charges, Churn Rate %) and trend charts highlighting contract-level vulnerability.

Page 2 (Demographics & Profile): Analyzed churn risk across Senior Citizen status, Gender, and Family/Dependents support alongside a tenure timeline.

Page 3 (Services & Add-ons Impact): Evaluated technical services such as Internet type (Fiber Optic vs. DSL) and the retention benefits of Tech Support add-ons.

📊 Dashboard Preview
<img width="1292" height="726" alt="Demograpiv Insights" src="https://github.com/user-attachments/assets/2632341c-e4a4-4376-b49d-6a0425fb6af4" />
<img width="1292" height="722" alt="Executive Overview" src="https://github.com/user-attachments/assets/311c0185-b658-4be4-b76c-ebb2d17487ac" />
<img width="1293" height="725" alt="Services and Add-ons" src="https://github.com/user-attachments/assets/d89348a2-7d83-4964-a48b-218b365a64d1" />

📈 Key Business Insights
Contract Vulnerability: Month-to-month contracts experience significantly higher churn rates compared to one-year or two-year commitments.

Tenure Risk Window: New customers (0–10 months tenure) exhibit the highest attrition risk, indicating a need for improved onboarding programs.

Service Impact: Customers utilizing Fiber Optic internet service without security or technical support add-ons show elevated churn tendencies.


👤 Author
Chirag Goyal

B.Tech Information Technology Student

[GitHub Profile](https://github.com/Chirag-g11) | [Linkedin Profile](https://www.linkedin.com/in/chirag-goyal-a7715a289/)
