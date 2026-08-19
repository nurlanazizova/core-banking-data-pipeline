# CORE BANKING DATA PIPELINE

## 📌 Project Overview

A simplified Core Banking Data Pipeline developed using Oracle SQL and PL/SQL.

This project simulates a real-world banking data flow, including customer management, account operations, transaction processing, balance tracking, data analysis, and automated processes.

## 🛠️ Technologies

- Oracle Database
- SQL
- PL/SQL
- Views
- Materialized Views
- Analytic Functions
- Stored Procedures
- Functions
- Packages
- Triggers
- DBMS_SCHEDULER
- EXPLAIN PLAN
- Indexing

## 🗂️ Database Structure

The project includes the following main entities:

- Customers
- Accounts
- Transactions
- Daily Balances
- Branches

Primary keys and foreign keys are used to maintain data integrity and relationships between tables.

## 🔄 Main Features

- Customer and account management
- Deposit and withdrawal transaction processing
- Account balance validation
- Transaction status validation
- Running balance calculation
- High-value transaction detection
- Suspicious activity analysis
- Statistical transaction analysis
- Daily account balance reporting
- Automated data processing

## ⚙️ PL/SQL Implementation

The project includes a `process_transaction` procedure that:

- Validates account status
- Checks available balance
- Processes deposits and withdrawals
- Updates account balances
- Uses transaction control with `COMMIT` and `ROLLBACK`
- Handles exceptions using PL/SQL exception handling

## 📊 SQL Analysis

Advanced SQL techniques are used, including:

- JOIN operations
- Common reporting queries
- Analytic functions
- `SUM() OVER`
- `ROW_NUMBER()`
- `RANK()`
- `DENSE_RANK()`
- Aggregation functions

## 🚀 Performance Optimization

Query performance was analyzed using `EXPLAIN PLAN`.

Indexes were created on frequently filtered and joined columns to reduce unnecessary full table scans and improve query performance.

## ⏰ Automation

`DBMS_SCHEDULER` is used to automate:

- Daily balance refresh
- Scheduled transaction processing
- Periodic data processing tasks

## 👩‍💻 Author

**Nurlana Azizova**

Oracle SQL & PL/SQL Developer