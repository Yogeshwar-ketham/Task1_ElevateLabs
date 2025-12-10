# Task 1: Data Cleaning - Netflix Dataset

## 🎬 Objective
Prepare the **Netflix Movies and TV Shows** dataset for analysis by addressing missing values, inconsistent formats, and data types.

## 🛠️ Tools
- **Python** (Pandas)
- **Jupyter Notebook**

## 🧹 Key Steps Taken
1. **Missing Data Strategy:**
   - `Director`, `Cast`, `Country`: Filled missing values with "Unknown" to maintain dataset volume.
   - `Date_Added`: Dropped a small number of rows with missing dates.
2. **Date Conversion:** Parsed textual dates into `datetime` format (`%Y-%m-%d`).
3. **Column Standardization:** Renamed columns to lowercase for consistency.
4. **Sanity Check:** Verified unique entries and removed duplicates.

## 📂 Files
- `task1_netflix_cleaned.csv`: The final processed dataset.
- `Netflix_Cleaning_Script.ipynb`: The Python code used for cleaning.
