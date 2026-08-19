Banking Data Analysis — SQL & Power BI

Project Overview

This project focuses on analyzing a banking dataset using Oracle SQL and Microsoft Power BI.

The project combines SQL-based data quality assessment, exploratory data analysis (EDA), customer and account analysis, transaction analysis, branch performance analysis, and loan portfolio analysis with an interactive Power BI dashboard.

The objective is to transform raw banking data into meaningful business insights that can support understanding of customers, accounts, transactions, branches, and loans.

---

Tools & Technologies

- Oracle SQL — Data quality checks, analysis, queries, views, procedures, and triggers
- Microsoft Power BI — Interactive dashboards and data visualization
- Microsoft Excel — Data preparation and supporting analysis
- GitHub — Project documentation and portfolio management

---

Dataset Overview

The banking dataset contains information related to:

- Customers
- Branches
- Accounts
- Bank Transactions
- Loans

The SQL analysis identified the following overall dataset size:

Data Category| Records
Customers| 100
Branches| 10
Accounts| 150
Transactions| 1,000
Loans| 100

The dataset also contains a total bank balance of 29,812,500 and total deposits of 250,500 based on the SQL analysis.

---

SQL Analysis

The SQL analysis was organized into several areas.

1. Data Quality Assessment

Data quality checks were performed before analysis, including:

- Duplicate record checks
- Null-value checks
- Age validation
- Income validation
- Account balance validation
- Transaction amount validation
- Foreign-key/orphan record checks

The checks reported no duplicate records, no null values in the checked customer fields, and no invalid or orphan records in the validation checks.

2. Database Overview & EDA

The exploratory analysis calculated:

- Total customers
- Total branches
- Total accounts
- Total transactions
- Total loans
- Total deposits
- Average account balance
- Highest and lowest transaction amounts
- Total bank balance

3. Customer Analysis

Customer-level analysis includes:

- Customer distribution by city
- Customer distribution by gender
- Average income by occupation
- Top 10 high-value customers
- Customers with multiple accounts
- Customer account and balance summaries

One notable finding was that engineers had the highest average income in the analyzed customer data, at 76,000.

4. Account & Transaction Analysis

The project analyzes:

- Account type distribution
- Balance by account type
- Transaction count by transaction type
- Transaction amount by channel
- Recent transactions
- Top 10 deposit transactions

The analysis showed an equal distribution of the three account types, with 50 Savings, 50 Current, and 50 Business accounts.

Transaction activity was also evenly distributed, with 250 transactions for each transaction type.

Online banking recorded the highest total transaction amount by channel.

5. Branch Analysis

Branch-level analysis includes:

- Branch-wise account performance
- Total customers by branch
- Total accounts by branch
- Total balance managed by branch
- Branch ranking by total balance
- Branch ranking by number of customers

The analysis identified Hyderabad branch as the branch with the highest total balance.

6. Loan Analysis

Loan analysis includes:

- Loan amount by loan type
- Loan portfolio analysis
- Loan status analysis
- Total loans
- Total loan amount
- Average loan amount
- Outstanding balance

Home loans contributed the largest portion of the loan portfolio.

Loan statuses were almost evenly distributed:

- Pending: 34
- Approved: 33
- Closed: 33

---

Oracle SQL Development

In addition to analytical queries, the project includes Oracle database programming concepts.

Trigger

An account audit trigger was created to record:

- Account ID
- Action performed
- User who performed the action
- Date and time of the action

The trigger captures INSERT, UPDATE, and DELETE operations on the Accounts table and provides an audit trail for account changes.

Procedure

A stored procedure named "get_account_details" was created to retrieve account information using "ACCOUNT_ID".

It returns:

- Account type
- Opening date
- Balance
- Account status

Views

The project also includes analytical views for:

- Branch performance
- Loan analysis

These database objects demonstrate the use of Oracle SQL beyond basic SELECT queries.

---

Power BI Dashboard

The SQL analysis was complemented by an interactive Power BI dashboard designed to present banking insights visually.

The dashboard contains five major sections:

1. Executive Dashboard
2. Customer Dashboard
3. Transaction Dashboard
4. Branch Dashboard
5. Loan Dashboard

The dashboards provide interactive visual analysis of customers, accounts, transactions, branches, and loans.

---

Key Business Insights

Some of the major insights identified through the analysis include:

- The dataset contains 100 customers, 150 accounts, 1,000 transactions, and 100 loans.
- Savings, Current, and Business accounts are equally represented.
- Savings accounts hold the highest share of account balances.
- Online banking is the leading transaction channel by transaction value.
- Engineers represent the highest-average-income occupation in the dataset.
- Several customers maintain multiple accounts.
- Hyderabad branch manages the highest total balance.
- Home loans contribute the largest portion of the loan portfolio.
- Loan statuses are almost evenly distributed, with pending loans slightly higher.
- Account activity can be tracked through the Oracle audit trigger.

---

Project Structure

banking-data-analysis-sql-powerbi/
│
├── README.md
│
├── SQL/
│   └── Banking_SQL_Analysis.pdf
│
├── PowerBI/
│   └── BANKINGDASHBOARD.pbix
│
├── Dashboard_Screenshots/
│   ├── Executive_Dashboard.png
│   ├── Customer_Dashboard.png
│   ├── Transaction_Dashboard.png
│   ├── Branch_Dashboard.png
│   └── Loan_Dashboard.png
│
└── Documentation/
    └── Banking_SQL_Analysis.pdf

---

Skills Demonstrated

- SQL querying
- Data quality assessment
- Exploratory Data Analysis
- Data validation
- Aggregation and grouping
- Joins
- Subqueries
- Common Table Expressions (CTEs)
- Window functions
- Ranking
- Oracle stored procedures
- Oracle triggers
- Oracle views
- Business intelligence
- Power BI dashboard development
- Data visualization
- Business insight generation

---

Project Outcome

The project demonstrates how banking data can be analyzed using SQL and transformed into interactive business intelligence dashboards using Power BI.

It combines data quality assessment, SQL analysis, Oracle database programming, and dashboard visualization into a single end-to-end banking analytics project.
