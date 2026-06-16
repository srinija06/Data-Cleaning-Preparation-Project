# Data Cleaning & Preparation Project

## Overview

This project focuses on data cleaning and preparation using Microsoft Excel. The objective was to identify missing values, verify duplicate records, validate date formats, and ensure overall data quality before analysis.

---

## Dataset Information

* Total Rows: 1200
* Total Columns: 14

### Dataset Columns

* OrderID
* Date
* CustomerID
* Product
* Quantity
* UnitPrice
* ShippingAddress
* PaymentMethod
* OrderStatus
* TrackingNumber
* ItemsInCart
* CouponCode
* ReferralSource
* TotalPrice

---

## Project Objectives

The primary goals of this project were to:

* Identify and handle missing values.
* Verify the uniqueness of records.
* Validate and standardize data formats.
* Ensure data consistency and quality.
* Prepare the dataset for further analysis and reporting.

---

## Data Cleaning Process

### 1. Missing Value Handling

#### Observation

Missing values were identified in the **CouponCode** column.

#### Action Taken

Blank CouponCode entries were replaced with:

```text
No Coupon
```

#### Reason

A blank CouponCode indicates that the customer did not apply a coupon during the purchase process rather than representing missing information.

---

### 2. Duplicate Verification

#### Observation

The **OrderID** column was checked for duplicate values.

#### Result

No duplicate OrderIDs were found.

#### Action Taken

No records were removed.

---

### 3. Date Format Validation

#### Observation

The **Date** column was reviewed to ensure formatting consistency.

#### Result

All dates follow the format:

```text
YYYY-MM-DD
```

#### Action Taken

No corrections were required.

---

### 4. Data Consistency Check

The following columns were reviewed for consistency:

* PaymentMethod
* OrderStatus
* ReferralSource

#### Result

All values were already standardized and consistently formatted.

#### Action Taken

No modifications were required.

---

## Validation Summary

| Validation Check          | Result |
| ------------------------- | ------ |
| Missing Values Identified | Yes    |
| Missing Values Handled    | Yes    |
| Duplicate IDs Found       | 0      |
| Incorrect Date Formats    | 0      |
| Text Consistency Issues   | 0      |

---

## Tools Used

* Microsoft Excel

---

## Files Included

* Cleaned Dataset for Data Analytics.xlsx
* DATA ANALYTICS PROJECT1 REPORT.pdf
* README.md

---

## Key Learnings

Through this project, the following data cleaning concepts were applied:

* Missing value handling
* Duplicate verification
* Data format validation
* Data consistency checking
* Data quality assessment

---

## Conclusion

The dataset was successfully cleaned and validated according to the project requirements. Missing values were handled appropriately, duplicate Order IDs were verified to be absent, date formats were confirmed to be consistent, and text fields were reviewed for standardization.

The final dataset is clean, reliable, and ready for further analysis and reporting.
