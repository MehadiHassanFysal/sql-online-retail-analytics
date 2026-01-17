## 📊 SQL Online Retail Analytics

**(Cohort Analysis, Customer Retention & Customer Lifetime Value)**

This project analyzes an online retail transaction dataset using **SQL (MySQL)** to understand customer behavior over time. The focus is on **data cleaning**, **cohort-based retention analysis**, and **customer lifetime value (CLV)** using SQL views and CTEs.

### 🔹 Dataset

* Large online retail transactional database (~521K+ records)
* Contains invoice-level purchase data with customer IDs, quantities, prices, and timestamps
* Due to GitHub file size limits, the full database is provided via **Google Drive (linked below)**

### 🔹 Key Steps

1. **Data Exploration**

   * Record count and anomaly detection
   * Identified invalid rows (null customer IDs, zero/negative quantity or price)

2. **Data Cleaning**

   * Created a reusable SQL **VIEW (`RETAIL_CLEANED`)**
   * Converted invoice dates to proper datetime format
   * Calculated sales per transaction

3. **Customer Cohort & Retention Analysis**

   * Assigned customers to cohorts based on their **first purchase month**
   * Calculated month-wise customer retention using SQL window functions and CTEs

4. **Customer Lifetime Value (CLV)**

   * Aggregated sales by cohort and month offset
   * Measured revenue contribution over customer lifecycle

### 🔹 SQL Concepts Used

* CTEs (WITH clause)
* Window functions
* Views
* Date transformations
* Conditional aggregation
* Cohort indexing logic

### 🔹 Files

* `Online_Retail (Cohort Analysis, Customer Retention, Customer Lifetime Value).sql` – complete SQL analysis
* Database download link provided below

📎 **Dataset (Google Drive):**
Online Retail (DATABASE).csv
https://drive.google.com/file/d/1cqaCUBQC_D0NQkiagh2UUoyyS5CGDGyw/view?usp=drive_link
