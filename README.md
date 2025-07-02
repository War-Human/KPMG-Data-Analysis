# 📊 KPMG Data Analysis using Excel
 
**Project Title:** KPMG Data Analysis using Excel

## 🧾 Project Overview
This project focuses on analyzing customer data to extract meaningful insights into business performance, customer behavior, and potential growth areas. Using **Microsoft Excel**, the project involves **data cleaning**, **segmentation**, **transaction analysis**, **customer lifetime value estimation**, and **strategic recommendations**. The analysis is based on a fictional dataset provided by KPMG.

---

## 📁 Dataset Details

### 1. Customer Address Dataset
Contains information about customers' addresses and property valuation.

| Column | Description |
|--------|-------------|
| `customer_id` | Unique identifier |
| `address` | Customer address |
| `postcode` | Postal code |
| `state` | State of residence |
| `country` | Country (all entries are Australia) |
| `property_valuation` | Property value (integer) |

---

### 2. Customer Demographic Dataset
Demographic and behavioral details about customers.

| Column | Description |
|--------|-------------|
| `customer_id` | Unique identifier |
| `first_name`, `last_name` | Name of the customer |
| `gender` | Gender |
| `past_3_years_bike_related_purchases` | Purchase count |
| `DOB` | Date of birth |
| `job_title` | Job title |
| `job_industry_category` | Industry category |
| `wealth_segment` | Wealth classification |
| `deceased_indicator` | Y/N |
| `default` | Default status |
| `owns_car` | Yes/No |
| `tenure` | Customer tenure |

---

### 3. Transactions Dataset
Data about individual transactions.

| Column | Description |
|--------|-------------|
| `transaction_id` | Unique transaction ID |
| `product_id`, `customer_id` | Identifiers |
| `transaction_date` | Date of transaction |
| `online_order`, `order_status` | Order details |
| `brand`, `product_line`, `product_class`, `product_size` | Product info |
| `list_price`, `standard_cost` | Pricing |
| `product_first_sold_date` | Product launch date |

---

### 4. New Customer List Dataset
Details about potential customers.

| Column | Description |
|--------|-------------|
| `first_name`, `last_name`, `gender`, `DOB` | Personal details |
| `past_3_years_bike_related_purchases` | Purchase history |
| `job_title`, `job_industry_category`, `wealth_segment` | Job & wealth |
| `deceased_indicator`, `owns_car`, `tenure` | Other demographics |
| `address`, `postcode`, `state`, `country` | Location |
| `property_valuation`, `Rank`, `Value` | Valuation & ranking |

---

## ✅ Tasks Overview

### 🧹 Task 1: Data Cleaning
- Remove duplicates
- Standardize formatting (state names, gender, missing values)
- Fix erroneous entries and ensure consistency

---

### 👥 Task 2: Customer Segmentation
- Segment by **wealth segment**, **gender**, and **industry**
- Calculate customer tenure, average purchases, and customer distribution

---

### 💰 Task 3: Transaction Analysis
- Sales trend over months
- Product and brand performance
- Identify top customers and average purchase behavior

---

### 🧩 Task 4: New Customer Insights
- Analyze new customer demographics and location
- Correlate property valuation with wealth
- Estimate potential revenue

---

### 📈 Task 5: Customer Lifetime Value (CLV) Analysis
**Formula:**  
`CLV = (Average Purchase Value × Purchase Frequency) × Customer Lifespan`

- CLV calculation using Excel formulas
- Segment CLV by wealth and analyze against demographics

---

### 📌 Task 6: Executive Summary and Recommendations
- Summarize insights from previous tasks
- Provide marketing, product, and expansion recommendations

---
