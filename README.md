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
<img width="1841" height="951" alt="Screenshot 2026-04-05 175154" src="https://github.com/user-attachments/assets/49f55e26-e55b-4ad5-9271-f5d421375186" />


### 🔸 1.2 Load Multiple Excel Files (Jan, Feb, Mar)

* Used **Get Data → Folder**
* Combined files using append
  

### 🔸 1.3 Load Employee Dataset

* Loaded Excel file containing employee details

📸 Screenshot:
<img width="1722" height="828" alt="Screenshot 2026-04-05 180516" src="https://github.com/user-attachments/assets/80daca6e-d264-4873-afcd-304252536564" />



## ✅ Step 2: Basic Transformations

Performed the following operations:

* Removed blank rows and columns
* Promoted first row as headers
* Renamed columns
* Changed data types (with locale)
* Removed duplicates
* Filtered null values

📸 Screenshot:
<img width="1712" height="854" alt="Screenshot 2026-04-05 180630" src="https://github.com/user-attachments/assets/b8b76ab7-f8e9-47fa-9837-1ec090a82e4b" />


## ✅ Step 3: Text Cleaning

Applied text functions:

* UPPER()
* LOWER()
* TRIM()
* CLEAN()
* REPLACE()
* Split Column by Delimiter

 Screenshot:
📸<img width="1712" height="855" alt="Screenshot 2026-04-05 181724" src="https://github.com/user-attachments/assets/45427c5b-bd7c-4406-ad18-860e4cb26a74" />

---

## ✅ Step 4: Numeric Transformations

* Rounded revenue values to 2 decimal places
* Created new column:

  * Profit = Revenue – Cost

📸 Screenshot:
<img width="1705" height="860" alt="Screenshot 2026-04-05 182028" src="https://github.com/user-attachments/assets/8fda5b5f-c6aa-49fa-883b-adb01766ce9a" />
<img width="1713" height="852" alt="Screenshot 2026-04-05 182315" src="https://github.com/user-attachments/assets/6b8aa231-e27f-470c-b394-2039d629205f" />

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
<img width="1745" height="877" alt="Screenshot 2026-04-05 183201" src="https://github.com/user-attachments/assets/8d75e290-0411-4725-a936-b00ce676abb6" />
<img width="1715" height="849" alt="Screenshot 2026-04-05 184054" src="https://github.com/user-attachments/assets/72144de1-ee85-4730-b52f-2bfced76eda4" />

---

## ✅ Step 6: Conditional Columns & Indexing

* Created **Sales Category**:

  * High (≥ 10,000)
  * Medium (5,000–9,999)
  * Low (< 5,000)

* Added:

  * Index column (0-based and 1-based)

📸 Screenshot:
<img width="1742" height="842" alt="Screenshot 2026-04-05 183727" src="https://github.com/user-attachments/assets/a87b2e6a-93be-4d03-acf7-80be16e715b9" />

---

## ✅ Step 7: Pivoting & Unpivoting

* Converted monthly columns into rows using **Unpivot Columns**
* Normalized dataset structure


## ✅ Step 8: Merging & Appending

* Merged:

  * Sales data with Employee data using EmployeeID/Region

* Appended:

  * Monthly sales data (Jan–Apr)

📸 Screenshot:
<img width="1735" height="838" alt="Screenshot 2026-04-05 184301" src="https://github.com/user-attachments/assets/ea10ee3c-e78b-4807-a869-270dc014bba6" />
<img width="1725" height="842" alt="Screenshot 2026-04-05 191541" src="https://github.com/user-attachments/assets/8535b4f8-4039-4f96-b9b0-458103324c6c" />


---

## ✅ Step 9: Grouping & Aggregation

Grouped data by Region and calculated:

* Total Sales
* Average Order Value
* Transaction Count

📸 Screenshot:
<img width="1704" height="846" alt="Screenshot 2026-04-05 184648" src="https://github.com/user-attachments/assets/dd4c4ee7-5a9e-4a93-98a4-0fc695580bcd" />

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
<img width="1746" height="908" alt="Screenshot 2026-04-05 185003" src="https://github.com/user-attachments/assets/002b77dc-5983-4f61-b909-9d7a3f55b344" />

---

## ✅ Step 11: Parameters & Data Source Settings

* Created **FolderPath parameter**
* Linked parameter to folder source
* Configured data source credentials


## ✅ Step 12: Refresh Simulation

* Added new file: **Sales_Apr.xlsx**
* Clicked **Refresh**
* Verified automatic data update


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
