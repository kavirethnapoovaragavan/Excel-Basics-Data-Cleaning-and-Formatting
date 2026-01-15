# Task 1 – Excel Data Cleaning & Formatting

## 📌 Objective
The objective of this task is to clean and standardize a real-world dataset using Excel so that it is ready for further analysis.

## 📂 Dataset Used
Netflix Movies and TV Shows Dataset (CSV format)

## 🛠 Tools Used
- Microsoft Excel

## 🔍 Steps Performed
1. Downloaded the dataset in CSV format and opened it in Excel.
2. Ensured the first row was treated as column headers and data was properly separated.
3. Applied Freeze Panes to lock the header row and enabled filters for all columns.
4. Identified missing values using filters and handled them appropriately:
   - Director → Filled as "Unknown"
   - Country → Filled as "Not Specified"
   - Rating → Filled as "Not Rated"
5. Created a backup sheet before removing duplicates.
6. Removed duplicate records using key columns (show_id and title).
7. Standardized text fields using Excel functions such as TRIM, PROPER, and UPPER.
8. Validated data formats for date and numeric columns.
9. Created a separate Cleaned_Data sheet to store the cleaned output.
10. Added a Data_Quality_Notes column to document data issues and cleaning decisions.
11. Saved the final dataset as both Excel and CSV formats.

## 📁 Files Included
- Raw_Data.xlsx
- Cleaned_dataset.xlsx
- cleaned_dataset.csv

## ✅ Outcome
A clean, structured dataset that follows professional data-cleaning practices and is ready for analysis or visualization.
