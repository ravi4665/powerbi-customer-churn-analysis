# powerbi-customer-churn-analysis
A complete end-to-end Customer Churn Analysis project built using Power BI. Includes data cleaning, data modeling, DAX calculations, interactive dashboards, churn prediction insights, and business recommendations. The project identifies key churn drivers and helps organizations reduce churn using data-driven decisions.

🌐 Customer Churn Analysis – End-to-End Power BI Project

This repository contains a complete, end-to-end Customer Churn Analysis developed using Power BI, leveraging the widely used Telco Customer Churn dataset.
The project demonstrates advanced capabilities in data transformation, data modeling, DAX measure development, dashboard design, and business storytelling, aimed at identifying the key drivers behind customer churn and its financial impact.

This analysis empowers stakeholders with actionable insights to reduce churn, improve customer satisfaction, and optimize revenue.

📂 Repository Structure

The repository contains all core assets required to explore, replicate, and understand the full project:

├── Customer Churn Analysis.pbix          # Complete Power BI report

├── WA_Fn-UseC_-Telco-Customer-Churn.csv  # Original dataset

├── Dashboards/

│   ├── Executive Summary/

│   ├── Customer Demographics/

│   ├── Service Subscription/

│   ├── Contract & Billing/

│   ├── Churn Prediction & Key Drivers/

└── README.md


Each dashboard folder includes high-quality screenshots for quick reference without opening the PBIX file.

🎯 Project Purpose & Business Objective

Telecom companies face significant financial impact due to customer churn.
The objective of this project is to:

Understand factors influencing churn behavior

Identify high-risk customer segments

Estimate revenue loss and retention opportunities

Provide data-driven strategies to reduce churn

Enable decision-makers with clear and interactive insights

This Power BI solution replicates a real-world analytics environment, consolidating multiple customer dimensions—demographics, services, billing, and behavior—to produce meaningful and actionable visual storytelling.

📊 Dashboard Overview

The report is structured into five comprehensive dashboards, each addressing a unique analytical area.

1️⃣ Executive Summary Dashboard

A high-level overview designed for business leaders.
Key metrics include:

Total customers, total revenue, average monthly charges

Total churned customers and churn rate

Lost vs retained revenue

Gender distribution

Customers & churn by tenure bucket

Essential filters for demographic and service exploration

This dashboard summarizes the entire analysis in one cohesive view.

2️⃣ Customer Demographics Analysis

Provides an in-depth look at who the customers are.

Covered insights:

Male vs Female distribution

Churn among senior vs non-senior citizens

Tenure segmentation across the customer base

Churn rate trends by tenure groups

Relationship between monthly charges and tenure

Monthly charges vs tenure segmented by gender

Key customer metrics with dynamic filters

This dashboard helps understand whether specific demographic groups are more likely to churn.

3️⃣ Service Subscription Analysis

Focuses on customer behavior based on subscribed services.

This includes:

Phone service subscription (Yes/No)

Churn rate across internet types (DSL, Fiber optic, No internet)

Churned customers by add-on services

Impact of number of subscribed services on churn

Service combinations with highest churn probability

Fiber vs DSL vs No internet usage comparison

Filters for gender, senior citizen, internet type, and contract

These insights help identify problematic service categories and upselling opportunities.

4️⃣ Contract & Billing Insights

Evaluates churn patterns from a financial and contract perspective.

Key insights include:

Churn rate by contract type (Month-to-month, One-year, Two-year)

Payment method distribution & churn

Average monthly and total charges per billing group

Impact of paperless billing on churn

Tenure distribution for each contract type

Dynamic KPIs for billing performance

This dashboard highlights the influence of contract structure and payment behavior on churn.

5️⃣ Churn Prediction & Key Drivers

Powered by feature analysis and AI-like segmentation logic.

Contains:

Overall churn rate

Revenue impact (retained vs lost customers)

Churn by contract type, seniority, gender, internet type

Churn risk segmentation (Low, Medium, High)

Top churn drivers with conditional formatting

Revenue impact visualizations

This helps stakeholders understand who is at risk, why, and how much revenue is at stake.

🧠 Key Business Insights

A few major findings from the analysis:

Month-to-month contracts drive the highest churn (42%+).

Fiber optic users churn more aggressively than DSL or non-internet customers.

Senior citizens show significantly higher churn rate.

Customers with multiple add-on services are less likely to churn, indicating value-driven retention.

Electronic check payment method customers are at the highest risk of churn.

Churn is highest among low-tenure customers, suggesting weak early retention strategies.

The business is losing approximately $2.86M in revenue due to churn, while retaining $13.2M.

🛠 Technical Implementation
Tools Used

Power BI Desktop

Power Query for ETL

DAX for calculated columns and measures

Star Schema modeling

Modeling Overview

Fact table: Customer subscription & churn details

Dimension tables: Tenure buckets, add-on services, contract types, etc.

Measures: Churn rate %, revenue calculations, segmentation metrics

🚀 How to Explore the Project

Download the .pbix file from the repository.

Open in Power BI Desktop.

Use the slicers provided on each dashboard to deeply explore specific customer segments.

Switch between dashboards using navigation buttons.

🤝 Contributing & Feedback

Contributions are welcome!
Feel free to submit issues, feature suggestions, or improvements to enhance the analytical depth.

If you’re using this for learning, feel free to fork and modify the report to build your own version.

📧 Contact

For collaboration, portfolio review, or Power BI guidance, you can reach out anytime
