# Customer Churn Risk Detection using Power BI and DAX

## Business Scenario

A retail company wants to identify customers who may stop purchasing in the future. By analyzing customer behavior such as credit score, purchase history, and the time since the last purchase, customers can be classified into churn risk categories.

Using Power BI and DAX logical functions, customers are segmented into High Risk, Medium Risk, and Low Risk groups to help the business take proactive retention actions.

---

## Tools Used

* Power BI
* DAX (Data Analysis Expressions)
* Excel
* Data Modeling

---

## Dataset Description

The dataset contains customer-level information including:

| Column              | Description                                      |
| ------------------- | ------------------------------------------------ |
| CustomerID          | Unique identifier for each customer              |
| Age                 | Customer age                                     |
| TenureMonths        | Duration of customer relationship                |
| TotalPurchases      | Total number of purchases                        |
| TotalSpend          | Total spending amount                            |
| CreditScore         | Customer credit rating                           |
| LoyaltyMember       | Indicates if customer is part of loyalty program |
| LastPurchaseDaysAgo | Number of days since last purchase               |

---

## Data Validation Process

Before performing the analysis, the following validation checks were performed:

* Verified column data types
* Checked for missing values
* Checked for duplicate records
* Reviewed outliers and unusual values
* Confirmed dataset structure

These validation steps ensure reliable analysis results.

---

## Business Logic Implementation

Logical business rules were implemented using DAX.

### Customer Activity Classification

Customers were classified as Active or Inactive based on purchase recency.

IF function was used to determine activity status.

---

### High Value Customer Identification

Customers with high spending and frequent purchases were identified using AND logic.

---

### Marketing Target Segmentation

Customers were identified as potential marketing targets using OR conditions based on credit score and inactivity.

---

### Churn Risk Classification

The primary objective of the project was to classify customers into three churn risk categories:

* High Risk
* Medium Risk
* Low Risk

This classification was implemented using the SWITCH and TRUE functions with business rule conditions.

---

## DAX Functions Used

This project demonstrates the following logical functions:

* IF()
* AND()
* OR()
* SWITCH()
* TRUE()

These functions are commonly used in real-world business analytics scenarios.

---

## Key Learning Outcomes

Through this project, the following skills were demonstrated:

* Data validation and quality checks
* Business rule implementation using DAX
* Customer segmentation logic
* Power BI data modeling workflow
* Logical function application in analytics

---

## Project Purpose

This project was developed as part of a data analytics learning portfolio to demonstrate practical DAX logic implementation and Power BI data analysis skills.

---

## Future Enhancements

Future improvements may include:

* Interactive dashboard visualizations
* KPI tracking
* Customer retention analysis
* Predictive churn modelling

---

## Author

Vidya Geetha
Aspiring Data Analyst | Power BI | SQL | Python | Data Visualization|API
