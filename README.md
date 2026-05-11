# Customer-Target-Analytics-Dashboard
An interactive Customer Retention Analytics Dashboard in Power BI using Target’s customer data.

# Project Title: Retail Customer Retention Analytics

# Project Overview:

Target Corporation, one of the largest retail chains in the United States, operates through
hypermarkets, discount department stores, and e-commerce platforms. With growing
competition from Walmart, Amazon, and Costco, retaining loyal customers has become a
crucial challenge.

Target collects extensive data from customer transactions, loyalty memberships, and online
interactions, but its current reporting lacks analytical depth to:

● Understand why customers are churning.

● Identify loyal vs. at-risk customers.

● Measure the impact of loyalty tiers, promotions, and influencer-driven campaigns.

● Guide region- and channel-specific retention strategies.

You are hired as a Power BI Analyst to design a Customer Retention Dashboard for Target that
consolidates fragmented data and delivers real-time, actionable insights.

# Project Objective:

Develop an interactive Customer Retention Analytics Dashboard in Power BI using Target’s
customer data that will:

● Consolidate customer demographics, purchase history, store/e-commerce performance,
and loyalty data.

● Enable dynamic segmentation of high-value, repeat, and churned customers.

● Provide actionable insights to improve retention, loyalty engagement, and regional
strategies.

## Dataset used:

-<a href="https://github.com/Ayushh1512/Customer-Target-Analytics-Dashboard/blob/main/Customer_Demographics.csv">Dataset1</a>
-<a href="https://github.com/Ayushh1512/Customer-Target-Analytics-Dashboard/blob/main/Churn_Labelled_Customers.csv">Dataset2</a>
-<a href="https://github.com/Ayushh1512/Customer-Target-Analytics-Dashboard/blob/main/Customer_Transactions.csv">Dataset3</a>
-<a href="https://github.com/Ayushh1512/Customer-Target-Analytics-Dashboard/blob/main/Loyalty_Program.csv">Dataset4</a>
-<a href="https://github.com/Ayushh1512/Customer-Target-Analytics-Dashboard/blob/main/Store_Locations.csv">Dataset5</a>

# Tasks:

## Task 1: Data Modeling & Cleaning

● Load and transform datasets in Power Query

● Handle duplicates, missing values, and ensure correct data types

● Create calculated columns:
○ Membership_Duration = Today – Membership_Since
○ Extract Transaction_Year, Transaction_Month

● Create a basic Data Model view
○ One-to-Many: Customer_Demographics → Transactions, Loyalty_Program, Churn_Labelled_Customers
○ Many-to-One: Transactions → Store_Locations

## Task 2: Churn & Retention Metrics

● Create Churn Rate KPI = (Churned Customers / Total Customers) * 100

● Visualize churn rate by:
○ Region
○ Income Group
○ Channel (Store/Online)
○ Loyalty Tier

● Funnel Chart: Total Customers → Repeat Customers → Churned

## Task 3: Repeat Purchase Analysis

● Segment customers:
○ Low-Tier: 0–3 purchases
○ Mid-Tier: 4–8 purchases
○ High-Tier: 9+ purchases

● Compare avg. purchase frequency by Region, Age Group, Loyalty Tier

● Identify most purchased product categories by loyal customers

## Task 4: Promotion & Loyalty Impact

● Calculate % of transactions with promotion applied.
 
● Compare average purchase amount with vs. without promotions.

● Analyze churn rate across loyalty tiers.

● Visualize Points Earned vs. Redeemed by Tier (Clustered Column Chart).

● Give recommendations to improve redemption & retention.

## Task 5: Store & Channel Performance vs Retention 

● Merge store data with transactions

● Visualize:
○ Avg. transaction amount by Store Type
○ Churn rate by store type
○ Correlation between store opening year & retention

## Task 6: Customer Lifetime Value (CLV) Analysis

● CLV = Total Amount Spent / Membership Duration (Years)

● Segment customers into Low, High CLV
○ Above Average CLV as High
○ Below Average CLV value- Low

● Visualize:
○ CLV vs Days Since Last Purchase
○ CLV by Loyalty Tier & Region

## Task 7: Final Dashboard & Executive Summary

● Multi-page Power BI Report:
○ Page 1: KPIs (Churn, CLV, Repeat Rate)
○ Page 2: Loyalty & Promotion Impact
○ Page 3: Store/Channel Insights
○ Page 4: Segmentation (Churned, Repeat, High-Value)

● Slicers: Region, Channel, Income, Loyalty Tier

● Provide Top 3 Recommendations for Target:
○ Which customers to prioritize for retention?
○ Which channels are underperforming?
○ How to strengthen loyalty engagement?

## Task 8: Video explanation: Expressing the finding and actionable insights

# Solution in PPT: 

-<a href="https://github.com/Ayushh1512/Customer-Target-Analytics-Dashboard/commit/037d8d853b1a51fbc1d647595b158022399e268b">PPT</a>

## Few Dashboard Pictures: 

<img width="851" height="480" alt="Screenshot 2026-04-17 125205" src="https://github.com/user-attachments/assets/2e816eec-4e40-4b3b-b2aa-eda588a29e34" />


