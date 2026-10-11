 E-Commerce Data Analytics Project

 Project Overview

This project focuses on preparing and analyzing an "e-commerce sales and order dataset" for data analytics and visualization.

The project contains two versions of the dataset:

* Raw Dataset – Original, unprocessed e-commerce order data.
* Cleaned Dataset – Processed data with missing values handled and additional analytical columns created for easier analysis.

The dataset contains "1,200 orders" covering the period from "January 2023 to June 2025".

---

Raw Dataset

The raw dataset contains **14 columns**:

| Column            | Description                               |
| ----------------- | ----------------------------------------- |
| `OrderID`         | Unique identifier for each order          |
| `Date`            | Date on which the order was placed        |
| `CustomerID`      | Unique customer identifier                |
| `Product`         | Product purchased                         |
| `Quantity`        | Number of units purchased                 |
| `UnitPrice`       | Price per unit                            |
| `ShippingAddress` | Customer shipping address                 |
| `PaymentMethod`   | Payment method used                       |
| `OrderStatus`     | Current status of the order               |
| `TrackingNumber`  | Shipment tracking number                  |
| `ItemsInCart`     | Number of items in the customer's cart    |
| `CouponCode`      | Coupon applied to the order               |
| `ReferralSource`  | Source through which the customer arrived |
| `TotalPrice`      | Total value of the order                  |

---

## 🧹 Data Cleaning & Transformation

The raw dataset was processed to make it suitable for data analysis.

The cleaned dataset includes the original columns along with additional analytical fields.

### Additional Columns

| Column                 | Description                                         |
| ---------------------- | --------------------------------------------------- |
| `YEAR`                 | Year extracted from the order date                  |
| `MONTH`                | Month extracted from the order date                 |
| `MONTH-YEAR`           | Combined month and year for time-series analysis    |
| `CUSTOMER TYPE`        | Categorizes customers as New or Repeat Customers    |
| `ORDER VALUE CATEGORY` | Categorizes orders based on their total order value |

The cleaned dataset contains **19 columns** in total.

### Missing Data

The raw dataset contains missing values in the `CouponCode` field.

During cleaning, missing coupon values were handled so that the cleaned dataset contains no blank values in the dataset fields.

---

## 📈 Dataset Summary

* **Total Orders:** 1,200
* **Unique Customers:** 1,189
* **Products:** 7
* **Payment Methods:** 5
* **Order Statuses:** 5
* **Referral Sources:** 5
* **Date Range:** January 2023 – June 2025

### Products

The dataset includes:

* Laptop
* Monitor
* Phone
* Tablet
* Printer
* Desk
* Chair

### Order Statuses

* Pending
* Shipped
* Delivered
* Cancelled
* Returned

### Payment Methods

* Cash
* Credit Card
* Debit Card
* Gift Card
* Online

### Referral Sources

* Google
* Facebook
* Instagram
* Email
* Referral

---

## 🎯 Purpose of the Project

The cleaned dataset can be used to perform various data analytics tasks, including:

* Sales and revenue analysis
* Product performance analysis
* Customer behavior analysis
* New vs. repeat customer analysis
* Order value analysis
* Monthly and yearly sales trends
* Payment method analysis
* Order status analysis
* Coupon usage analysis
* Marketing/referral source analysis

---

## 🔍 Potential Business Questions

This dataset can help answer questions such as:

1. Which products generate the highest sales?
2. What are the monthly and yearly order trends?
3. Which payment methods are most commonly used?
4. Which referral sources bring in the most customers?
5. What percentage of customers are repeat customers?
6. Which products have the highest order quantities?
7. How are orders distributed across different value categories?
8. How frequently are orders cancelled or returned?
9. How does customer behavior change over time?
10. Which coupon codes are used most frequently?

---

## 🛠️ Tools & Technologies

This project can be analyzed using tools such as:

* **Microsoft Excel**
* **Power BI**
* **Python**
* **Pandas**
* **SQL**
* **Data Visualization Tools**

---

## 📂 Recommended Repository Structure

```text
E-Commerce-Data-Analytics/
│
├── Dataset/
│   ├── Dataset for Data Analytics RAW.xlsx
│   └── Dataset for Data Analytics CLEANED.xlsx
│
├── README.md
│
└── Analysis/
    └── [Analysis files / dashboards / notebooks]
```

---

## 🚀 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Missing Value Handling
     ↓
Data Transformation
     ↓
Feature Creation
     ↓
Cleaned Dataset
     ↓
Data Analysis & Visualization
     ↓
Business Insights
```

---

## 📌 Key Takeaway

The main objective of this project is to transform raw e-commerce transaction data into a **clean, structured, and analysis-ready dataset**.

The cleaned dataset provides additional time-based and customer/order classification fields, making it easier to perform exploratory data analysis, build dashboards, identify trends, and generate actionable business insights.

---

## 👤 Author

**SUMIT PRASAD SHOW**

This project was created as part of a **Data Analytics project** to demonstrate data cleaning, transformation, analysis, and visualization skills.






# Project 2: Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on an e-commerce dataset using Microsoft Excel. The main objective is to understand data patterns, trends, distributions, and outliers using descriptive statistics, PivotTables, charts, and logical insights.

EDA helps transform raw data into meaningful information that can support better business decisions.

## 🎯 Project Objectives

- Calculate basic descriptive statistics such as mean, median, count, minimum, and maximum.
- Analyze product performance and order values.
- Identify trends and patterns in the dataset.
- Examine payment methods, referral sources, coupon usage, and order statuses.
- Analyze customer types and order value categories.
- Identify potential outliers using the Interquartile Range (IQR) method.
- Summarize key findings and provide logical business insights.

## 📂 Dataset Description

The dataset contains 1,200 order records and 19 columns related to e-commerce transactions.

Some important columns include:

- `OrderID` – Unique order identifier
- `Date` – Order date
- `CustomerID` – Customer identifier
- `Product` – Product purchased
- `Quantity` – Quantity ordered
- `UnitPrice` – Price per unit
- `TotalPrice` – Recorded order value
- `PaymentMethod` – Payment method used
- `OrderStatus` – Status of the order
- `CouponCode` – Coupon associated with the order
- `ReferralSource` – Source through which the customer arrived
- `CUSTOMER TYPE` – Customer classification
- `ORDER VALUE CATEGORY` – Order value classification

The dataset covers the period from January 2023 to June 2025.

## 🛠️ Tools and Techniques Used

- Microsoft Excel
- Data exploration and quality checks
- Descriptive statistics
- PivotTables and PivotCharts
- Bar charts
- Line charts
- Histograms
- Box-and-whisker plots
- Interquartile Range (IQR) outlier detection

## 📊 Analysis Performed

### 1. Descriptive Statistics

Calculated the count, mean, median, minimum, and maximum for numerical variables such as Quantity, UnitPrice, ItemsInCart, and TotalPrice.

### 2. Product Performance Analysis

Compared products based on order frequency and total recorded order value to identify differences in product demand and value.

### 3. Payment Method Analysis

Examined the frequency of different payment methods and compared average recorded order values across payment categories.

### 4. Referral Source Analysis

Analyzed order counts and recorded order values across referral sources to understand how customers arrive at the business.

### 5. Coupon Usage Analysis

Examined the frequency of coupon codes to understand coupon usage patterns.

### 6. Order Status Analysis

Analyzed the distribution of orders across statuses such as Cancelled, Returned, Pending, Shipped, and Delivered.

### 7. Customer Type Analysis

Examined the distribution of records classified as new and repeat customers to identify areas for further investigation into customer purchasing behaviour.

### 8. Time-Based Trend Analysis

Analyzed monthly recorded order values to identify higher-value and lower-value periods over time.

### 9. Outlier Detection

Applied the IQR method to identify unusually high or low order values that may require further investigation.

## 🔍 Key Findings and Logical Insights

- **Dataset size:** The dataset contains 1,200 order records.
- **Average order value:** The mean `TotalPrice` is approximately 1,053.97, while the median is approximately 823.62.
- **Product performance:** Printer has the highest order count, with 181 orders.
- **Recorded order value by product:** Chair has the highest combined `TotalPrice`, at approximately 195,620.11.
- **Payment methods:** Credit Card has the highest average recorded order value among the payment methods analyzed.
- **Referral sources:** Instagram has the highest recorded order count among the referral sources analyzed.
- **Customer types:** Only 22 records are classified as Repeat Customer, which warrants further investigation.
- **Monthly trends:** June 2024 has the highest recorded monthly order value in the analysis.
- **Outliers:** The IQR analysis identified eight potential high-value outliers in `TotalPrice`.

These findings describe the available dataset and should be validated before being used to make firm business decisions.

## 💡 Business Insights

1. Product performance should be evaluated using both order frequency and total recorded order value.
2. Differences in average order values across payment methods can help identify patterns in purchasing behaviour, but they do not establish causation.
3. Referral sources can be compared by order count and recorded order value. Marketing profitability requires additional cost data.
4. Coupon usage should be evaluated alongside discounts, order values, and profitability to understand its effectiveness.
5. The distribution of order statuses should be investigated to understand cancellations and returns.
6. The low number of records labelled Repeat Customer suggests a need to validate customer classifications and investigate repeat purchasing.
7. Potential outliers should be checked for data errors or legitimate high-value orders before any records are removed.

## 📈 Project Outcome

This project demonstrates how Exploratory Data Analysis can be used to understand an e-commerce dataset through descriptive statistics, visualizations, trend analysis, and outlier detection.

The analysis provides an initial understanding of product demand, order values, payment preferences, referral sources, and customer classifications. It also identifies areas that require additional investigation.

## ⚠️ Limitations

- `TotalPrice` represents recorded order value and should not automatically be interpreted as realized revenue.
- The dataset includes multiple order statuses, so revenue calculations require appropriate status validation.
- The year 2025 covers only January through June in this dataset.
- Potential outliers are not necessarily errors and should not automatically be deleted.
- Observed relationships do not establish cause and effect.
- Currency is not explicitly specified in the dataset.

## 📁 Repository Contents

- `PROJECT 2 EDA.xlsx` – Excel workbook containing the dataset, statistical summaries, charts, and insights.
- `README.md` – Project documentation, objectives, methodology, findings, and conclusion.

## 🏁 Conclusion

The EDA project helped identify patterns and differences in product demand, recorded order values, payment methods, referral sources, and customer classifications.

By combining descriptive statistics, PivotTables, charts, and outlier detection, the project demonstrates how raw data can be converted into useful analytical observations.

Further analysis of customer retention, order outcomes, marketing costs, and purchasing behaviour could provide deeper insights into business performance.

---

**Project:** Exploratory Data Analysis (EDA)  
**Domain:** Data Analytics  
**Tool:** Microsoft Excel  
**Author:** SUMIT PRASAD SHOW
