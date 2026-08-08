# Task 3: Data Cleaning & Preprocessing

## 📌 Project Overview
This project focuses on executing end-to-end professional data cleaning on a raw, messy dataset. The goal is to systematically audit, transform, and document all data quality issues to yield an analysis-ready dataset.

## 🛠️ Tech Stack
- Language: Python
- Libraries: Pandas, NumPy

## 📋 Feature Checklist & Analytical Workflow
1. Initial Data Quality Report: Inspected dataset shape, data types, missing value distributions, duplicate rows, and value range anomalies.
2. Missing Data Handling: Applied customized strategies (mean/median/mode imputation or row deletion) with explicit markdown documentation justifying each choice.
3. Duplicate Removal: Identified and eliminated duplicate records while logging total removed rows.
4. Data Standardization: Normalized text formatting inconsistency (e.g., gender categories) and converted string date representations into standard datetime objects.
5. Outlier Detection & Management: Utilized the Interquartile Range (IQR) method to detect extreme outliers and applied capping thresholds.
6. Data Type Correction: Corrected object types into explicit string, float, and datetime64 dtypes.
7. Before vs. After Summary: Generated a comprehensive comparison matrix detailing missing counts, duplicate counts, and memory usage before and after transformation.
8. Clean Data Export: Exported the finalized cleaned dataset to a new CSV file (cleaned_dataset.csv).

## 📁 Repository Structure
- Task3_Data_Cleaning.ipynb: Complete Jupyter Notebook containing data cleaning pipeline, code, and documentation cells.
- cleaned_dataset.csv: Processed analysis-ready dataset.
