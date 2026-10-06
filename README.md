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
