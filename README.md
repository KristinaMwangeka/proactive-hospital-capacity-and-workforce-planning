# From Reactive to Proactive: A Data-Driven Strategy for Health Resource Management 

📖 Project Overview

This project transforms raw CDC hospitalization data into a strategic Decision Support System for healthcare management. Instead of reacting to patient surges after they happen, this dashboard uses historical trends of COVID-19 and Influenza to forecast demand, optimize nursing resource allocation, and implement proactive emergency staffing plans.



📂 Data & Methodology
1. Data Source
Origin: Respiratory Virus Response (RVR) United States Hospitalization data (via Kaggle / CDC National Healthcare Safety Network).

Scope: Originally 75,000+ rows and 106 columns.

2. Data Cleaning & Transformation (Excel & Power Query)
- Feature Selection: Reduced dimensionality from 106 columns to 19 essential features (Age demographics, COVID/Influenza Weekly & Daily Admissions, Date, Location).

- Filtering: Focused analysis on Tennessee (TN) and surrounding/regional states (GA, AL, MO, MS, KY, NC, AK) to identify cross-border infection trends.

Preprocessing:

- Handled missing values using Excel formulas.

- Standardize data types in Power BI (Power Query) for consistency.

3. Data Modeling
Built a Relational Model in Power BI connecting:

- Fact Table: Admissions Data

- Dimension Table: Calendar/Date Table

- Established relationships.
  

💡 Key Questions Answered

This dashboard visualizes answers to four critical operational questions:

- Regional Risk: What is the infection rate of our neighboring states? (Used to predict incoming spread).

- Resource Allocation: Which nursing department do we need? (Based on age-group admission demographics).

- Trend Analysis: What is the seasonal trend for COVID-19 vs. Influenza?

- Strategic Action (Applied Critical Thinking): What is the emergency plan to handle employee shortages?

Includes a tiered "Action Plan" (Low/Medium/Critical) to trigger voluntary overtime vs. mandatory measures based on capacity thresholds.



📸 Dashboard Visuals
<img width="1373" height="763" alt="image" src="https://github.com/user-attachments/assets/47a4428f-1bc2-4d0f-9712-6c672024746c" />

<img width="1022" height="765" alt="image" src="https://github.com/user-attachments/assets/98e583d2-2644-4ea4-9d29-5af891a2e631" />

🛠 Tools Used

- Microsoft Excel: Initial data cleaning and imputation.

- Power BI: Data transformation (ETL), Data Modeling, DAX Measures, and Visualization.

👤 Authors
- Kristina Mwangeka, BI Developer
- Aba Okyere, Data, Strategy Lead
- Eunice Ashalley, Business Analyst

Connect with me on LinkedIn: [https://www.linkedin.com/in/kristinamwangeka/]
