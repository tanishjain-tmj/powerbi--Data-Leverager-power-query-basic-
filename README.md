# 📊 Data Leverager – Power Query Transformation Project

---

## 🔹 Project Objective

To simulate a real-world data engineering workflow using Power BI’s Power Query Editor to extract, clean, transform, and combine data from multiple sources.

---

## 🔹 Tools Used

* Microsoft Power BI
* Power Query Editor
* Microsoft Excel

---

# 🚀 Step-by-Step Implementation

---

## ✅ Step 1: Data Extraction

### 🔸 1.1 Load HTML Table from Web

* Used **Get Data → Web**
* Loaded data from Wikipedia (GDP table)

📸 Screenshot:

---

### 🔸 1.2 Load Multiple Excel Files (Jan, Feb, Mar)

* Used **Get Data → Folder**
* Combined files using append

📸 Screenshot:

---

### 🔸 1.3 Load Employee Dataset

* Loaded Excel file containing employee details

📸 Screenshot:

---

## ✅ Step 2: Basic Transformations

Performed the following operations:

* Removed blank rows and columns
* Promoted first row as headers
* Renamed columns
* Changed data types (with locale)
* Removed duplicates
* Filtered null values

📸 Screenshot:

---

## ✅ Step 3: Text Cleaning

Applied text functions:

* UPPER()
* LOWER()
* TRIM()
* CLEAN()
* REPLACE()
* Split Column by Delimiter

📸 Screenshot:

---

## ✅ Step 4: Numeric Transformations

* Rounded revenue values to 2 decimal places
* Created new column:

  * Profit = Revenue – Cost

📸 Screenshot:

---

## ✅ Step 5: Date & Time Transformations

* Extracted:

  * Day
  * Month
  * Year
  * Quarter

* Created:

  * Fiscal Month column
  * Age column from Birthdate

📸 Screenshot:

---

## ✅ Step 6: Conditional Columns & Indexing

* Created **Sales Category**:

  * High (≥ 10,000)
  * Medium (5,000–9,999)
  * Low (< 5,000)

* Added:

  * Index column (0-based and 1-based)

📸 Screenshot:

---

## ✅ Step 7: Pivoting & Unpivoting

* Converted monthly columns into rows using **Unpivot Columns**
* Normalized dataset structure

📸 Screenshot:

---

## ✅ Step 8: Merging & Appending

* Merged:

  * Sales data with Employee data using EmployeeID/Region

* Appended:

  * Monthly sales data (Jan–Apr)

📸 Screenshot:

---

## ✅ Step 9: Grouping & Aggregation

Grouped data by Region and calculated:

* Total Sales
* Average Order Value
* Transaction Count

📸 Screenshot:

---

## ✅ Step 10: Data Profiling & Quality

Used:

* Column Profile
* Column Distribution
* Column Quality

To:

* Identify missing values
* Detect errors
* Analyze unique values

📸 Screenshot:

---

## ✅ Step 11: Parameters & Data Source Settings

* Created **FolderPath parameter**
* Linked parameter to folder source
* Configured data source credentials

📸 Screenshot:

---

## ✅ Step 12: Refresh Simulation

* Added new file: **Sales_Apr.xlsx**
* Clicked **Refresh**
* Verified automatic data update

📸 Screenshot:

---

# 📈 Final Outcome

* Successfully built a complete ETL pipeline
* Automated data loading using parameters
* Combined multiple data sources
* Prepared clean dataset for analysis

---

# 🎯 Conclusion

This project demonstrates the practical implementation of data transformation and integration using Power Query, simulating real-world data engineering processes.

---

# 💬 Viva Statement

“I performed end-to-end ETL operations using Power Query, including dynamic data loading, transformation, and refresh automation.”

---
