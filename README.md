# Churn-Analytics
📊 Customer Churn Analytics – End-to-End Data Project
🔎 Why This Project Is Needed

In today’s competitive market, acquiring customers is expensive — but losing them is even more costly.

Customer churn directly impacts:

Revenue stability

Marketing ROI

Customer acquisition cost

Long-term business growth

For telecom companies especially, where subscription-based revenue models dominate, even a small increase in churn can significantly reduce profitability.

This project focuses on identifying:

Who is churning

Why they are churning

Which customer segments are high-risk

What business actions can reduce churn

By leveraging structured ETL processes, SQL-based data modeling, Python-driven exploratory analysis, and Power BI dashboards, this project transforms raw customer data into actionable business intelligence.

🛠 Tech Stack & End-to-End Workflow

This project follows a complete analytics lifecycle:

1️⃣ Data Source

Raw customer data in CSV format

Includes:

Demographics

Account details

Services used

Contract information

Payment method

Churn status

2️⃣ SQL Server – Data Storage & ETL

Imported CSV data into SQL Server

Created structured database tables

Performed:

Data validation

Null handling

Aggregations

Calculated churn metrics

Group-based segmentation

SQL was used to:

Extract clean datasets

Build intermediate tables

Prepare analytics-ready data

3️⃣ Python (EDA & Validation)

Using:

Pandas

NumPy

Matplotlib

Seaborn

Performed:

Data cleaning

Outlier detection

Distribution analysis

Correlation checks

Churn pattern exploration

Segment-level analysis

Python helped:

Validate SQL transformations

Identify hidden churn drivers

Prepare insights before dashboard development

4️⃣ Power BI – Visualization & Business Intelligence

Built an interactive dashboard including:

KPI cards

Churn segmentation visuals

Geographic churn distribution

Service-level churn insights

Contract & tenure analysis

5️⃣ DAX – Data Transformation & Measures

Used DAX for:

Churn Rate %

% of Total calculations

Dynamic KPI updates

Conditional formatting

Segment comparison metrics

Tooltip-driven drill insights

DAX allowed advanced calculations directly inside Power BI for dynamic reporting.

📊 Dashboard Structure
1️⃣ KPI Overview

Total Customers

New Joiners

Total Churn

Churn Rate %

2️⃣ Demographic Analysis

Gender – Churn Rate

Age Group – Total Customers & Churn Rate

3️⃣ Account Information

Payment Method – Churn Rate

Contract Type – Churn Rate

Tenure Group – Total Customers & Churn Rate

4️⃣ Geographic Analysis

Top 5 States – Churn Rate

5️⃣ Churn Distribution

Churn Category – Total Churn

Tooltip: Churn Reason – Total Churn

6️⃣ Services Used

Internet Type – Churn Rate

Additional Services – % of Total Churn Status

🔍 Key Analytical Insights

Month-to-month contracts show significantly higher churn rates compared to long-term contracts.

Customers with tenure less than 12 months are at the highest risk of attrition.

Fiber optic users have higher churn probability compared to DSL users.

Certain payment methods correlate with higher churn behavior.

Specific geographic regions show disproportionately higher churn rates.

📈 Business Value & Impact

If implemented in a real telecom business environment, this analysis could:

🎯 1️⃣ Reduce Early-Tenure Churn

Targeting customers within first 6–12 months through retention campaigns could reduce churn by an estimated 5–8%.

🎯 2️⃣ Contract Optimization Strategy

Encouraging long-term contracts via discounts could reduce month-to-month churn segment by 10–15%.

🎯 3️⃣ Service-Based Retention Campaigns

Identifying high-churn internet users allows targeted service improvement campaigns, potentially reducing churn by 6–9% in that segment.

🎯 4️⃣ Geographic Marketing Allocation

Focusing retention marketing budgets on top 5 high-churn states could improve ROI efficiency by 12–18%.

🎯 5️⃣ Revenue Protection

A 3–5% churn reduction in a telecom company with 6,000+ customers could translate to:

Significant annual revenue preservation

Improved customer lifetime value

Lower acquisition replacement cost
