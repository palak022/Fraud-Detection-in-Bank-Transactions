📊 Fraud Detection in Bank Transactions

(Excel • SQL • Power BI • Python)

This project analyzes 10,000+ bank transactions to identify potential fraud patterns using a complete data analytics workflow. It includes data cleaning, rule-based checks, SQL analysis, EDA, and dashboard creation.

⭐ Project Overview

Cleaned and transformed raw transaction data

Applied rule-based fraud detection

Performed exploratory data analysis (EDA)

Wrote SQL queries for deeper insights

Built an interactive Power BI dashboard

Used Python for visual analysis and optional ML modeling

🗂 Dataset Columns

transaction_id

customer_id

transaction_amount

transaction_type (Card, UPI, Wallet, NetBanking)

transaction_time

location (City + Country)

is_international

account_balance

merchant

label (0 = genuine, 1 = fraud)

🧹 Data Cleaning (Excel + Python)

Removed extra spaces using TRIM()

Fixed Date-Time formatting

Split City and Country

Standardized transaction type values

Verified numeric columns (ISNUMBER)

Handled missing values

🔍 Fraud Detection Rules (Excel)

High amount transactions (> ₹50,000)

Transactions during odd hours (1 AM – 5 AM)

Multiple rapid transactions

Low account balance after payment

New merchant + high amount

International + high value combination

Each rule contributes to a combined fraud score

📈 Exploratory Data Analysis (Python)

Transaction distribution

Fraud vs Non-fraud comparison

Amount trends

Time-based patterns

Merchant and location insights

Libraries: pandas, numpy, matplotlib, seaborn

🛢 SQL Analysis

Transaction count by type

Top merchants with fraud cases

Hour-wise fraud pattern

International vs Domestic comparison

High-risk customers

Average amount per transaction type

📊 Power BI Dashboard Includes

KPIs (Total Fraud, Total Transactions)

Fraud vs Genuine visualization

Transaction type breakdown

City & Country fraud map

Hourly and daily patterns

Merchant-level analysis

📁 Project Structure
/data
/excel
/sql
/python
/powerbi
README.md

🧠 Skills Used

Excel

SQL

Power BI

Python

Data Cleaning

EDA

Visualization

Fraud Analytics

Dashboard Creation
