# Customer Segmentation Using SQL (RFM Analysis)

## Project Overview

This project demonstrates how SQL can be used to perform customer segmentation using **Recency, Frequency, and Monetary (RFM) Analysis** on a banking dataset. The objective is to identify valuable customers, inactive customers, and customers at risk by analyzing their account balances and transaction history.

The solution transforms raw customer, account, and transaction data into meaningful business insights using advanced SQL techniques. The entire analysis is built using Common Table Expressions (CTEs), aggregate functions, conditional logic, and joins to create a clean and scalable data transformation pipeline.

## Business Problem

Banks and financial institutions need to understand customer behavior to improve retention, personalize marketing campaigns, and identify high-value customers. Instead of treating every customer the same, this project segments customers based on:

* Account balance
* Transaction frequency
* Total transaction value
* Most recent transaction date

These insights help business teams prioritize customer engagement and retention strategies.

## Dataset

The project uses three relational tables:

* **Customers** – Customer demographic information.
* **Accounts** – Account details and current balances.
* **Transactions** – Transaction history including transaction amount and transaction date.

## SQL Concepts Used

* Common Table Expressions (CTEs)
* INNER/LEFT JOINs
* Aggregate Functions (SUM, COUNT, MAX)
* GROUP BY
* CASE Statements
* Date Functions (DATEDIFF)
* Conditional Customer Segmentation
* Data Aggregation
* Business Rule Implementation

## Project Workflow

1. Join customer, account, and transaction tables.
2. Aggregate customer-level metrics such as total balance, total transactions, and transaction amount.
3. Calculate customer recency using the latest transaction date.
4. Apply business rules to classify customers into meaningful segments:

   * Premium Customers
   * Dormant Customers
   * At Risk Customers
   * Inactive Customers
5. Generate a final customer segmentation table for business reporting and downstream analytics.

## Business Value

* Identifies high-value customers for premium banking services.
* Detects inactive customers for re-engagement campaigns.
* Highlights customers at risk of churn.
* Provides a foundation for targeted marketing and customer retention strategies.
* Supports data-driven decision-making using SQL alone.

## Key Learning Outcomes

* Designed a multi-stage SQL data transformation pipeline using CTEs.
* Applied business logic to solve a real-world customer segmentation problem.
* Improved query readability and maintainability through modular SQL design.
* Practiced translating business requirements into analytical SQL queries.

## Technologies Used

* SQL (MySQL)
* Relational Database
* Git & GitHub

## Future Enhancements using RFM Analysis

* Implement complete RFM scoring using SQL window functions (`NTILE()`).
* Build an interactive Power BI dashboard for customer segmentation analysis.
* Add customer lifetime value (CLV) calculation.
* Create churn prediction and retention KPIs.
* Optimize query performance using indexes and execution plan analysis.
