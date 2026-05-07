📱 PhonePe Data Analysis: Digital Payment Ecosystem Insights Dashboard
A comprehensive, interactive Power BI dashboard built to analyze PhonePe's digital payment ecosystem—focusing on transaction patterns, service performance, payment success rates, and revenue distribution across Insurance, Loans, Money Transfer, and Recharge & Bills.

Purpose
The PhonePe Data Analysis Dashboard is a visually engaging and analytical Power BI report designed to help stakeholders explore and analyze 300,000 transactions worth ₹3.33 billion across PhonePe's four major service categories throughout 2024. The dashboard focuses on highlighting payment success rates, failure reasons, service-wise revenue contribution, temporal trends, and user engagement metrics. This tool is intended for use by business analysts, product managers, operations teams, financial strategists, and data-driven decision-makers who seek to understand transaction patterns and optimize PhonePe's digital payment services.

🛠️ Tech Stack
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Main data visualization platform used for interactive dashboard creation
📂 Power Query – Data transformation and cleaning layer for data preparation and quality checks
🧠 DAX (Data Analysis Expressions) – Used for calculated measures, KPIs, success rate calculations, and conditional logic
📝 Data Modeling – Relationships established among 6 tables (All_Users, All_Transactions, Recharge_Bills, Money_Transfer, Loans, Insurance) to enable cross-filtering and aggregation
🎨 Custom Branding – PhonePe purple color theme (#590066) applied throughout for brand consistency
📁 File Format – .pbix for development, .png for dashboard screenshots, .docx for documentation

📊 Data Source
Source: PhonePe Transaction Database (Educational Dataset)  
Dataset: Phonepe-Final-Dataset.xlsx (35 MB)
Coverage: 300,000 transaction records across 6 interconnected sheets:

All_Users (107,658 users) – User demographics including age, join date
All_Transactions (300,000 records) – Central fact table with transaction details, payment status, and dates
Recharge_Bills (50,000 records) – Mobile, DTH, Cable TV, Electricity bill payments
Money_Transfer (150,000 records) – UPI, QR Code, Self Account, Mobile Number transfers
Loans (50,000 records) – Auto Loan, Mutual Fund, Gold Loan, Credit Score transactions
Insurance (50,000 records) – Bike, Car, Family, Health insurance premium payments

Time Period: January 1, 2024 to December 30, 2024 (Full Year)
Data Quality: 0 missing values, 0 duplicates, 100% clean dataset

🎯 Features / Highlights
• Business Problem
The digital payments industry processes billions in transactions daily, yet fintech companies often struggle to:

Identify revenue drivers across multiple service verticals
Monitor and reduce payment failures that result in lost revenue
Understand user behavior patterns across different payment services
Track service performance in real-time for operational optimization
Make data-driven decisions for resource allocation and marketing strategies

Key questions such as:

Which service generates the most revenue despite lower transaction volume?
What are the primary reasons for payment failures?
How do success rates vary across different services?
What are the seasonal trends in transaction patterns?

...are difficult to answer quickly without an intuitive analytical tool.

 Goal of the Dashboard
To deliver an interactive visual analytics tool that:

✅ Enables stakeholders to explore 300,000 transactions across 4 service categories
✅ Supports business decisions such as resource allocation, failure reduction strategies, and marketing focus
✅ Uncovers revenue patterns, success rates, and failure reasons by service and time period
✅ Provides self-service analytics through interactive filters and drill-through capabilities
✅ Identifies opportunities for operational improvement and revenue optimization

• Walkthrough of Key Visuals
📍 Page 1: Home Page – Executive Overview
Key KPIs (Top Section)

Total Amount: ₹3,333M (₹3.33 Billion)
Total Transactions: 300K
Successful Transactions: 288K (96.0%)
Failed Transactions: 12K (4.0%)

Interactive Filters

Date Range Slicer – Filter all visuals by custom date range (Jan 2024 - Dec 2024)

Service vs Amount (Bar Chart)

Vertical bar chart comparing revenue contribution:

Loans: ₹102M (Dominant revenue driver)
Insurance: ₹22M
Money Transfer: ₹15M
Recharge & Bills: ₹2M

Payment Status (Donut Chart)

Visual breakdown of successful vs. failed payments
Shows 96% success rate with color-coded segments

Failed Payment Reason (Donut Chart)

Detailed breakdown of failure categories:

Insufficient amount: 43.76% (Primary failure reason)
Server error: 27.52%
Wrong PIN: 27.61%
Wrong Info: 5.83%
Bank Denied: 5.28%

Date vs Amount (Area Chart)

Monthly trend analysis showing transaction volume fluctuations
Highlights peak months: March (₹13.70M), July (₹13.05M)
<img width="1330" height="740" alt="image" src="https://github.com/user-attachments/assets/4f8ad832-4fd2-4b93-b02c-3a458b3c4f10" />

📍 Page 2: Recharge & Bills – Utility Payments Analysis
Total Amount KPI: ₹51M
Service Breakdown (Horizontal Bars with Icons)

Electricity: 12.82M transactions, ₹0.52M
DTH: 12.64M transactions, ₹0.52M
Mobile Recharge: 12.63M transactions, ₹0.48M
Cable TV: 50.69M transactions, ₹0.48M

Payment Success Rate: 96.16% (Highest among all services)
Failed Payment Distribution:

Server error: 34.41%
Wrong PIN: 32.17%
Insufficient amount: 33.42%

Date vs Amount Trend:

Monthly pattern from Jan (₹149K) to Dec (₹130K)
Identifies seasonal utility payment patterns

📍 Page 3: Money Transfer – P2P Payments Analysis
Total Money Transferred: ₹378M
Transfer Type Distribution (Horizontal Bars - Dark Navy Theme)

To UPI ID: ₹3.9M (Most popular method)
To QR Code: ₹3.8M
To Self Account: ₹3.7M
To Mobile Number: ₹3.6M

Success Rate: 95.98%
Failed Payment Reasons:

Insufficient amount: 30.5%
Server error: 22.63%
Wrong PIN: 22.71%

Temporal Analysis:

Peak in January (₹1,418K)
Consistent volume through year
Ending December at ₹1,218K

📍 Page 4: Loans – Financial Services Analysis
Total Loan Amount Disbursed: ₹2,533M (₹2.53 Billion)
Revenue Contribution: 76% of total PhonePe revenue (Key finding!)
Loan Type Breakdown (Horizontal Bars with Icons)

Gold Loan: 632.41M transactions, ₹27M
Auto Loan: 643.64M transactions, ₹26M
Mutual Fund: 634.21M transactions, ₹26M
Credit Score: 622.24M transactions, ₹23M

Approval Rate: 95.95%
Unique Failure Pattern:

Wrong Info: 34.53% (Credit verification issues)
Bank Denied: 34.14% (Credit/eligibility issues)
Server error: 31.33%

Note: Loan failures are primarily credit-related, not user errors like other services
Monthly Trend:

August spike: ₹10.16M (Potential back-to-school/festival season)
Valleys in May (₹7.78M) and October (₹7.43M)

📍 Page 5: Insurance – Premium Collection Analysis
Total Premium Collected: ₹512.92M
Insurance Type Breakdown (Horizontal Bars with Icons)

Bike Insurance: 128.10M transactions, ₹5.9M
Car Insurance: 129.35M transactions, ₹5.7M
Family Insurance: 128.86M transactions, ₹5.5M
Health Insurance: 126.61M transactions, ₹5.1M

Payment Success Rate: 95.75%
Failed Payment Reasons:

Wrong PIN: 33.76%
Server error: 32.58%
Insufficient amount: 33.66%

Temporal Pattern:

Peak in October (₹2.12M) – Year-end insurance renewals
Drop in December (₹1.78M)





