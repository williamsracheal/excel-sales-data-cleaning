# excel-sales-data-cleaning
Excel data cleaning project involving sales orders, customer IDs, missing values, duplicate checks, and numerical formatting.
# Sales Orders Data Cleaning Project | Microsoft Excel

## Project Overview

This project involved cleaning and standardizing a sales orders dataset using Microsoft Excel to improve data quality and prepare it for further analysis.

The project focused on numerical precision, missing-value handling, date standardization, identifier validation, and understanding repeated customer identifiers.

## Project Objectives

- Standardize numerical and date formats.
- Handle missing values in the coupon code column.
- Verify the uniqueness of order identifiers.
- Investigate repeated customer identifiers.
- Prepare a consistent dataset for further analysis.

## Tools Used

- Microsoft Excel

## Data Cleaning Process

### 1. Numerical Precision

Standardized the `UnitPrice` and `TotalPrice` columns to two decimal places to ensure consistent numerical presentation.

### 2. Missing Values

Filled blank entries in the `Coupon` column with `no_coupon` to distinguish orders without a recorded coupon code from other coupon entries.

### 3. Date Standardization

Standardized the `Date` column to a consistent year-month-day format (`YYYY-MM-DD`) to improve readability and consistency.
### 4. Order ID Validation

Checked the `OrderID` column to ensure each order identifier was unique. This helps maintain reliable order-level identification and supports accurate analysis.

### 5. Customer ID Investigation

Identified repeated values in the `CustomerID` column. Rather than treating these repetitions as errors, I retained them because the same customer may place multiple orders.

This decision preserves potentially valuable information for future analysis of repeat purchases and customer purchasing behaviour.

## Key Data Quality Decisions

| Data issue | Action taken |
|---|---|
| Inconsistent numerical precision | Standardized to two decimal places |
| Blank coupon entries | Replaced with `no_coupon` |
| Date formatting | Standardized the date representation |
| Repeated OrderIDs | Checked for uniqueness |
| Repeated CustomerIDs | Retained for potential customer analysis |

## Project Outcome

The dataset is now cleaned and standardized for further analysis. The process improved consistency while preserving meaningful customer-level information.

This project reinforced the importance of investigating data quality issues before modifying or removing records. Not every repeated value represents an error; understanding the meaning of each identifier is essential to making appropriate cleaning decisions.

## Potential Next Steps

The cleaned dataset can be used for further sales analysis, including:

- Sales performance and revenue trends.
- Product performance comparisons.
- Customer purchasing behaviour.
- Repeat-customer analysis.
- Coupon usage and its relationship with sales.

## Skills Demonstrated

- Data cleaning and standardization
- Missing-value handling
- Numerical formatting
- Identifier validation
- Data-quality assessment
- Analytical decision-making

## Author
Racheal Williams
Data Analyst | Excel | SQL | Python | Data Storytelling
**Racheal Williams**

Aspiring Data Analyst | Excel | SQL | Python | Data Storytelling
