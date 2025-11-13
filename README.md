# Task 1 — Data Cleaning and Pre-Processing (Excel Version)

*Internship:* Data Analyst Internship  
*Tool Used:* Microsoft Excel  
*Objective:* Clean and prepare a raw dataset by removing missing values, duplicates, and inconsistent formats, then standardize column names.

---

## ⚙ Steps Performed

1. *Opened raw dataset*
   - Imported CSV into Excel.
   - Turned on Filter to inspect all columns.

2. *Handled missing values*
   - Highlighted blanks using Conditional Formatting.
   - For numeric fields (Age, Income, etc.) → filled with *average value*.
   - For categorical fields → filled with *most frequent value or “Unknown”*.

3. *Removed duplicates*
   - Used *Data → Remove Duplicates* on all columns.

4. *Standardized text*
   - Applied LOWER() + TRIM() formulas for consistency (e.g., Male → male).
   - Replaced inconsistent spellings manually.

5. *Converted dates to uniform format*
   - Used *Format Cells → Date (dd-mm-yyyy)*.

6. *Renamed columns*
   - Changed headers to clear, lowercase, underscore-based names  
     (e.g., “Customer ID” → “customer_id”).

7. *Verified data types*
   - Ensured numbers were numeric and text fields were text type.

8. *Saved outputs*
   - Saved final cleaned file as cleaned_dataset.xlsx.
   - Captured screenshots of before/after cleaning.

---

## 📊 Files in this repository
| File | Description |
|------|--------------|
| cleaned_dataset.xlsx | Final cleaned dataset (Excel) |
| summary_of_changes.md | Short report summarizing cleaning steps |
| /screenshots/ | Folder containing before/after screenshots |

---

## 📝 How to Reproduce
1. Download cleaned_dataset.xlsx.  
2. Open in Excel → review filters, column formats, and filled cells.  
3. Compare with screenshots to see applied changes.

---

## ✅ Outcome
- All missing values handled  
- All duplicates removed  
- Consistent text & date formats  
- Readable, standardized headers  
- Data ready for analysis or visualization

---

## 💡 Key Concepts
Data cleaning · Handling missing values · Removing duplicates · Standardization · Excel data preprocessing
