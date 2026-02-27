# QuickBite Crisis Recovery Analysis
# Problem Statement

This project is based on a resume challenge from Codebasics.

QuickBite Express is a Bengaluru-based food-tech startup that faced a major crisis in June 2025 due to:

Food safety violations by partner restaurants

Delivery outages during monsoon

Increased competition pressure

This led to:

Massive customer churn

Decline in orders and revenue

Drop in customer satisfaction

Loss of restaurant partners

The goal of this project is to analyze the crisis impact and provide data-driven insights to support business recovery and strategic decision-making.

# Objectives

Identify recoverable vs lost customers

Analyze order trends across pre-crisis and crisis phases

Evaluate delivery performance (SLA, delays, cancellations)

Recommend customer retention & marketing strategies

Assess restaurant partner performance

Analyze customer sentiment and feedback trends

# Tech Stack

Python (Pandas, NumPy) → Data Cleaning & Preprocessing

PostgreSQL → Data Storage 

Power BI → Data Visualization & Dashboarding

# Data Pipeline

Cleaned  datasets using Python (Pandas)

Loaded processed data into PostgreSQL database

Connected PostgreSQL to Power BI

Built interactive dashboards for business insights

# Dashboard Overview

The dashboard is divided into 5 key sections:

1️⃣ Crisis Overview

Orders drop ~69%

Revenue drop ~71% (₹37.62M → ₹10.94M)

Bengaluru & Mumbai drop ~70%

2️⃣ Customer Analysis

Total Customers: 105K+

Churned: 73K (~70%)

Retained: 14K

New Customers: 18K

Active During Crisis: 32K

3️⃣ Delivery & Operations

Avg Delay: 5.71 mins

SLA Compliance: 36%

Cancellation Rate: ~7% (doubled)

Delivery Partners: 15K

4️⃣ Restaurant Analysis

Active restaurants dropped significantly

Top restaurants saw 60–85% decline in orders

Cuisine-level demand shifted

5️⃣ Customer Sentiment Analysis

Ratings dropped from ~4.6 → ~2.3

Negative sentiment increased

Key issues:

Food safety

Packaging

Poor service

# Key Business Insights

Orders declined by ~69%, and revenue dropped by ~71%, indicating a severe demand shock.

73K customers churned, highlighting a major trust breakdown.

Despite 18K new users, active users dropped to 32K, showing weak retention.

Metro cities (Bengaluru & Mumbai) drove most of the decline.

Delivery performance collapsed:

SLA drop to 36%

Delays increase to 5.71 mins

Cancellations nearly doubled

Customer sentiment turned negative due to food safety and service issues.

# Root Cause Analysis (WHY)

Trust Failure: Food safety incident led to negative sentiment and churn

Operational Breakdown: Poor SLA, high delays, inefficient delivery allocation

High-Value Market Impact: Metro cities decline amplified revenue loss

Weak Retention Strategy: Loyal customers not effectively retained

Platform Reputation Damage: Entire ecosystem affected

# Recommendations
 Customer Strategy

Run win-back campaigns for churned users

Introduce loyalty programs & personalized offers

 Operations

Optimize delivery partner allocation

Implement real-time routing & SLA tracking

 City Strategy

Focus on Bengaluru & Mumbai for faster recovery

 Restaurant Strategy

Retain top-performing partners

Enforce food safety standards

 Customer Experience

Improve packaging & food quality

Introduce real-time feedback monitoring

# Conclusion

The crisis was not just operational but a trust-driven failure, where food safety issues triggered customer churn and operational inefficiencies amplified the impact.

Recovery requires rebuilding customer trust + operational excellence.

# Key Learnings

End-to-end data pipeline (Python → SQL → Power BI)

Business storytelling with data

Customer segmentation & churn analysis

KPI design for real-world business problems

🔗 Acknowledgement

Dataset and problem statement provided by Codebasics as part of a resume challenge.
