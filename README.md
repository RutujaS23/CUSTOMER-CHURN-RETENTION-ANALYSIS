# Customer Churn & Retention Analysis

## 📌 Project Overview
This project focuses on analyzing customer behavior, identifying inactive customers, and understanding customer retention and churn patterns. The goal is to identify factors affecting customer activity, analyze revenue trends, and generate meaningful business insights to improve customer retention.

## 🎯 Project Objectives
- Analyze customer transactions and purchasing behavior.
- Identify active and inactive customers.
- Calculate customer retention and churn.
- Analyze monthly revenue trends.
- Identify top-performing customers and products.
- Understand customer engagement through website visits and support tickets.
- Build an interactive Power BI dashboard.

## 🛠️ Tools & Technologies
- **SQL (MySQL):** Data querying, JOINs, GROUP BY, CTEs, subqueries, and aggregations.
- **Microsoft Excel:** Data cleaning, formulas, Pivot Tables, and analysis.
- **Python (Pandas):** Data cleaning, preprocessing, and exploratory data analysis.
- **Power BI:** Interactive dashboards and data visualization.

## 📂 Dataset Description
The project uses customer, transaction, and engagement data.

### 1. Customers
- customer_id
- customer_name
- city

### 2. Transactions
- transaction_id
- customer_id
- amount
- transaction_date
- payment_method

### 3. Engagement
- customer_id
- website_visits
- support_tickets

## 🔍 Analysis Performed

### SQL Analysis
- Total revenue analysis.
- Top 5 customers by spending.
- Revenue by city and month.
- Average transaction value.
- Transactions per customer.
- Customers without transactions using LEFT JOIN.
- Customer segmentation using CASE WHEN.
- Monthly revenue analysis using aggregations.

### Excel Analysis
- Data cleaning and formatting.
- Customer spending analysis.
- IF and IFS formulas.
- SUMIFS and COUNTIFS.
- VLOOKUP.
- Pivot Tables and Charts.
- Customer segmentation.

### Python (Pandas)
- Data loading and inspection.
- Handling missing values.
- Removing duplicate records.
- Data type conversion.
- Customer-level aggregation.
- Monthly revenue analysis.
- Exploratory Data Analysis (EDA).

## 📊 Power BI Dashboard

The interactive dashboard includes:

1. **Monthly Revenue:** Line Chart.
2. **Revenue by Payment Method:** Pie Chart.
3. **Revenue by City:** Bar Chart.
4. **Customer Segmentation:** Pie Chart.
5. **Website Visits:** Column Chart.
6. **Top Products:** Product performance analysis.
7. **Repeat Customers:** Customer retention analysis.

### Key Performance Indicators (KPIs)
- Total Revenue
- Total Customers
- Total Transactions
- Average Transaction Value
- Active Customers
- Inactive Customers
- Repeat Customers

## 💡 Business Insights
The analysis helps businesses:
- Identify customers who may stop purchasing.
- Understand customer purchasing patterns.
- Identify high-value customers.
- Track monthly revenue performance.
- Improve customer engagement.
- Develop better customer retention strategies.

## 📁 Project Structure

```text
Customer-Churn-Retention-Analysis/
│
├── Dataset/
│   ├── customers.csv
│   ├── transactions.csv
│   └── engagement.csv
│
├── SQL/
│   └── churn_analysis.sql
│
├── Excel/
│   └── customer_analysis.xlsx
│
├── Python/
│   └── customer_analysis.ipynb
│
├── PowerBI/
│   └── churn_dashboard.pbix
│
└── README.md
```

## 🚀 Conclusion
This project demonstrates practical data analytics skills using SQL, Excel, Python, and Power BI. It transforms raw customer data into meaningful insights that help businesses understand customer behavior, monitor retention, and make data-driven decisions.

## 👩‍💻 Author
**Rutuja Sukale**  
Aspiring Data Analyst
