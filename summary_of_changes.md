# Summary of Changes — Excel Data Cleaning (Task 1)

| Step | Action | Description / Result |
|------|---------|----------------------|
| 1 | Missing values | 5 rows had blanks → numeric filled with average; categorical with “Unknown” |
| 2 | Duplicates | 3 duplicate rows removed using Data → Remove Duplicates |
| 3 | Text standardization | Gender column lower-cased (male, female); spaces trimmed |
| 4 | Date format | All dates converted to dd-mm-yyyy |
| 5 | Column headers | Renamed for clarity: “Customer ID” → customer_id, “Annual Income (k$)” → annual_income |
| 6 | Data types | Confirmed Age & Income numeric; Gender & City text |
| 7 | Output | Saved final Excel as cleaned_dataset.xlsx |

*Result:* Clean dataset with consistent formats and no duplicates or missing values.
