# Task_1
# Super Store Data Cleaning – Task 1 (Data Analyst Internship)

This project involves cleaning and preprocessing the `super_store.xlsx` dataset as part of a data analyst internship task. The goal was to handle missing values, remove duplicates, standardize formats, and prepare the dataset for further analysis or modeling.

---

## Dataset Used
- **File Name:** `super_store.xlsx`
- **Source:** Uploaded dataset for internal internship use
- **Size:** Medium (multiple rows and columns with mixed types: dates, numbers, categories)

---

## Tools Used
- **Microsoft Excel** (for all data cleaning tasks)
- Basic Excel formulas: `PROPER()`, `UPPER()`, `IF()`, `ISBLANK()`, `SUBSTITUTE()`, etc.

---

## Summary of Cleaning Steps

| **Step** | **Action** | **Description** |
|---------|------------|-----------------|
| 1 | **Removed Duplicates** | Removed duplicate rows using Excel’s “Remove Duplicates” tool across all columns. |
| 2 | **Handled Missing Values** | Filled missing values in `Postal Code` column with `"Unknown"` to prevent data loss. |
| 3 | **Standardized Text Columns** | Used `PROPER()` and `UPPER()` functions to clean text fields like `Customer Name`, `Region`, `Segment`, and `Category`. |
| 4 | **Reformatted Dates** | Formatted `Order Date` and `Ship Date` columns uniformly to `DD-MM-YYYY`. |
| 5 | **Renamed Column Headers** | Renamed all headers to lowercase with underscores (e.g., `Order Date` → `order_date`) to follow naming conventions. |
| 6 | **Fixed Data Types** | - Set numeric columns (like `Sales`, `Profit`, `Quantity`) to **Number** format  
- Ensured **Date** columns were recognized as proper Excel dates  
- Set all categorical/text fields to **Text** format |
| 7 | **Applied Text Case Consistency** | Used `UPPER()` to convert values in fields like `Region` and `Segment` for consistency. |
| 8 | **Saved Output File** | Saved the cleaned version as `super_store_cleaned.xlsx` for submission and analysis. |

---

## 📌 Key Learnings
- Hands-on experience with Excel for data wrangling
- Importance of consistent formatting before analysis
- Exposure to common issues in real-world datasets like missing values and inconsistent naming

