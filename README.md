🧼 Customer Data Cleaning with Pandas

This project demonstrates a comprehensive data cleaning pipeline using Python's `pandas` library. It involves transforming a messy dataset into a standardized and analysis-ready format.

---

## 📁 Dataset Overview

The original dataset included:
- Inconsistent text capitalization
- Special characters in names
- Merged address fields
- Unformatted phone numbers
- Null and placeholder values
- Irregular "Yes/No" indicators
- Unwanted rows (e.g., "Do Not Contact", missing phone numbers)

---

## 🧰 Tools Used

- Python 3
- pandas
- Jupyter Notebook / Google Colab

---

## 🚀 Cleaning Process

### 1. Load Data

### 2. Initial Inspection
 - Checked column names, null values, and unique value types

 - Used .head(), .info(), .isnull().sum() to preview structure

### 3. Clean Individual Columns
 - Name Cleanup
 - Phone Number Standardization
 - Split Address into Components
 - Normalize Columns

### 4. Replace Placeholder Strings

### 5. Fill Nulls

### 6. Remove Unwantwd Rowa

### 7. Final Formating

## ✅ Final Result

- Clean and standardized dataset

- Phone numbers and customer status validated

- Only reachable customers with valid numbers remain

- Index reset and ready for export or analysis



