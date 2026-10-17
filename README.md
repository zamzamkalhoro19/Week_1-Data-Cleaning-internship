# Week_1-Data-Cleaning-internship
## Task Overview
This repository contains Week 1 task of NextGen Learners Data Science Internship. The goal was to clean a messy dataset `applicants.csv`.

### Dataset
- Original File: applicants.csv (with missing values, duplicates, inconsistent formats)
- Cleaned File: applicants_cleaned.csv (final analysis-ready data)

### Data Cleaning Steps Performed
1.  **Checked Data:** Used `df.info()`, `df.isnull().sum()`, `df.duplicated()`
2.  **Handled Missing Values:** Filled/Removed null values in important columns
3.  **Removed Duplicates:** Used `df.drop_duplicates()`
4.  **Standardized Text:** Fixed 'Web Dev' to 'Web Development', 'ML' to 'Machine Learning' etc.
5.  **Fixed Data Types:** Converted application_date to datetime format
6.  **Trimmed Spaces:** Removed extra spaces from text columns

### Tools & Libraries
- Python
- Pandas
- Google Colab / Jupyter Notebook

### How to Run
1. Open Google Colab
2. Upload applicants.csv
3. Run cleaning script

### Output
Cleaned dataset is saved as `applicants_cleaned.csv` and uploaded in this repo.
