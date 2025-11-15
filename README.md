# powerbi-customer-churn-analysis
A complete end-to-end Customer Churn Analysis project built using Power BI. Includes data cleaning, data modeling, DAX calculations, interactive dashboards, churn prediction insights, and business recommendations. The project identifies key churn drivers and helps organizations reduce churn using data-driven decisions.

📊 Customer Churn Analysis – Power BI Project

A complete end-to-end Power BI analytics project designed to understand why customers churn, identify high-risk customer segments, and provide actionable insights to reduce churn and increase revenue.

This repository contains the Power BI Dashboard, dataset, documentation, and analysis assets.

📁 Repository Structure
├── Customer Churn Analysis.pbix     # Power BI Report

├── WA_Fn-UseC_-Telco-Customer-Churn.csv   # Dataset

├── Screenshots/                     # Dashboard images

│      ├── Executive_Summary.png

│      ├── Customer_Demographics.png

│      ├── Service_Subscription.png

│      ├── Contract_Billing.png

│      ├── Churn_Prediction.png

└── README.md

🧠 Project Objective

Telecom companies face increasing customer churn, leading to revenue loss and rising acquisition costs.
This project aims to:

🎯 Identify key drivers of customer churn
📉 Measure revenue lost vs retained
📌 Understand which customer segments churn the most
📊 Help business teams reduce churn through data-backed decisions
📝 Business Problem

The telecom company is experiencing a 26.58% churn rate, causing a significant revenue loss of $2.86M.
The management needs a clear understanding of:

Who is churning?

Why are they churning?

Which services drive the highest churn?

What demographics are most at risk?

Which customer groups should be prioritized for retention campaigns?

This dashboard provides a data-driven foundation for churn reduction strategies.

🧩 Key Features of the Analysis
✔ Comprehensive multi-page Power BI report:

Executive Summary Dashboard

Customer Demographics Dashboard

Service Subscription Dashboard

Contract & Billing Insights Dashboard

Churn Prediction & Key Drivers Dashboard

✔ 30+ visuals including:

Bar charts, column charts, donut charts, scatter plots, KPI cards, matrix visuals, heatmaps, distribution plots, drill-through, bookmarks, page navigation & more.

✔ Interactive Analysis using:

Gender slicers

Senior citizen slicers

Internet service type filters

Contract type filters

Payment method filters

📂 Dataset Overview

Source: Telco Customer Churn Dataset
Rows: 7043 customers
Columns: 21 attributes

Includes:

Demographics (gender, senior citizen, dependents)

Tenure & subscription details

Internet & phone service info

Contract & billing details

Monthly & total charges

Churn label (Yes/No)

📸 Dashboard Screenshots

⚠ Replace the image links below with your GitHub raw URLs after uploading images to /Screenshots/

1️⃣ Executive Summary Dashboard

2️⃣ Customer Demographics Analysis

3️⃣ Service Subscription Analysis

4️⃣ Contract & Billing Insights

5️⃣ Churn Prediction & Key Drivers

🔍 Major Insights Discovered
🧍‍♂️ 1. Customer Demographics

Customer base is 51% male, 49% female.

Senior citizens churn at 41.68%, almost double non-senior customers.

Long-tenure customers churn far less (49+ months → 9.51% churn).

📡 2. Service Subscription Findings

Fiber Optic users have the highest churn (41.89%).

Customers with more add-on services have higher retention.

Phone service alone does not influence churn much.

💳 3. Contract & Billing

Month-to-month contracts have 42.71% churn – highest risk.

Auto-pay and credit card users show lower churn.

Paperless billing customers churn more.

🔥 4. Key Drivers of Churn

Based on the heatmap:

Driver	Impact
Add-On Services	High
Internet Service	High
Number of Services	High
Contract Type	Very High
Senior Citizen	Very High
💰 5. Revenue Impact

Retained Revenue: $13.19M

Lost Revenue: $2.86M

Each 1% churn reduction can save ~$110K annually.

🚀 How to Use This Project
1. Clone the repository
git clone https://github.com/<your-username>/customer-churn-analysis.git

2. Open the Power BI file
Customer Churn Analysis.pbix

3. Load the dataset if required

File:

WA_Fn-UseC_-Telco-Customer-Churn.csv

4. Explore dashboards using slicers and navigation buttons
🛠 Tools Used
Tool	Purpose
Power BI Desktop	Data modeling & dashboard creation
DAX	Measures, KPIs & calculations
Power Query	Data cleaning & transformation
Python (optional)	Exploratory data analysis
GitHub	Version control & project hosting
📌 Key DAX Measures Used

✔ Total Customers
✔ Churned Customers
✔ Churn Rate %
✔ Total Revenue
✔ Lost Revenue
✔ Retained Revenue
✔ Tenure Buckets
✔ Add-on Service Counts
✔ Churn Rate by Category
✔ Customer Segment KPIs

(Add more if needed)

🏁 Conclusion

This project delivers a holistic churn analysis system that helps the telecom company:

Understand churn drivers

Identify high-risk customer segments

Predict churn more accurately

Recover potential revenue

Improve retention strategies

It is a production-ready dashboard suitable for business presentations, stakeholder reviews & data analytics portfolios.
