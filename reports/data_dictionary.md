# Banking Customer Intelligence & Segmentation Analysis
## Dataset Dictionary

### Dataset
**Credit Card Customer Segmentation Dataset**

This dataset contains behavioral information about credit card customers and their financial activity over a period of time. Each row represents a single customer and their credit card usage behavior.

---

# Dataset Overview

| Attribute | Description |
|-----------|-------------|
| **Number of Records** | ~8,950 customers |
| **Number of Features** | 18 variables |
| **Data Type** | Numerical + ID |
| **Domain** | Banking / Financial Services |
| **Use Case** | Customer segmentation & financial behavior analysis |

---

# Analytical Relevance

These variables allow analysis of:

- Customer spending patterns
- Credit utilization behavior
- Payment discipline
- Financial activity frequency

This information is useful for:

- Customer segmentation
- Financial risk monitoring
- Personalized banking services

---

# Data Dictionary

| Variable | Data Type | Description |
|--------|-----------|-------------|
| **CUST_ID** | String | Unique identifier for each credit card customer |
| **BALANCE** | Float | Current balance amount in the customer’s credit card account |
| **BALANCE_FREQUENCY** | Float | Frequency of balance updates (between 0 and 1) |
| **PURCHASES** | Float | Total amount of purchases made using the credit card |
| **ONEOFF_PURCHASES** | Float | Total value of one-time purchases |
| **INSTALLMENTS_PURCHASES** | Float | Total value of purchases made in installments |
| **CASH_ADVANCE** | Float | Total cash advance amount taken by the customer |
| **PURCHASES_FREQUENCY** | Float | Frequency of purchase transactions |
| **ONEOFF_PURCHASES_FREQUENCY** | Float | Frequency of one-time purchase transactions |
| **PURCHASES_INSTALLMENTS_FREQUENCY** | Float | Frequency of installment purchases |
| **CASH_ADVANCE_FREQUENCY** | Float | Frequency of cash advance transactions |
| **CASH_ADVANCE_TRX** | Integer | Number of cash advance transactions |
| **PURCHASES_TRX** | Integer | Number of purchase transactions |
| **CREDIT_LIMIT** | Float | Maximum credit limit assigned to the customer |
| **PAYMENTS** | Float | Total payments made by the customer |
| **MINIMUM_PAYMENTS** | Float | Minimum payment amount due from the customer |
| **PRC_FULL_PAYMENT** | Float | Percentage of full payments made by the customer |
| **TENURE** | Integer | Number of months the customer has been using the credit card |

---

# Feature Categories

To simplify analysis, variables can be grouped into financial behavior categories.

## Spending Behavior
- **PURCHASES**
- **ONEOFF_PURCHASES**
- **INSTALLMENTS_PURCHASES**

## Credit Usage
- **BALANCE**
- **CREDIT_LIMIT**
- **CASH_ADVANCE**

## Transaction Frequency
- **PURCHASES_FREQUENCY**
- **CASH_ADVANCE_FREQUENCY**
- **PURCHASES_TRX**

## Payment Behavior
- **PAYMENTS**
- **MINIMUM_PAYMENTS**
- **PRC_FULL_PAYMENT**

## Customer Relationship
- **TENURE**
