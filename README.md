# Task-01-DataCleaning
This repository contains the solution for Internship Task 1: Data Cleaning and Preprocessing.  It includes raw and cleaned datasets, a README report, and Excel screenshots as proof of work.
# Task 1 - Data Cleaning & Preprocessing

## Dataset: Netflix Titles
Source: Kaggle (netflix_titles.csv)
        

## Summary of Data Cleaning Steps

1. **Checked for Duplicates**  
   - Verified across all columns.  
   - No exact duplicate rows were found.  

2. **Handled Missing Values**  
   - Filled blanks in `director`, `cast`, `country`, `date_added`, `rating`, and `duration` with `"Unknown"`.  

3. **Date Formatting**  
   - Standardized `date_added` column into `dd-mm-yyyy` format for consistency.  

4. **Standardized Categorical Values**  
   - `type` column already contained only two categories (Movie, TV Show).  
   - `rating` column converted fully to uppercase for uniformity (e.g., `pg` → `PG`, `tv-14` → `TV-14`).  

5. **Renamed Column Headers**  
   - Converted all headers to lowercase and replaced spaces with underscores.  
   - Example: `Show Id` → `show_id`, `Release Year` → `release_year`.  

---

## Files in this Repository
- `netflix_titles12334.csv` → Raw dataset  
- `netflix_titles_cleaned.xlsx` → Cleaned dataset  
- `README.md` → Report (this file)  

---

## Key Learnings
- Learned how to identify and handle missing values.  
- Practiced duplicate checking (and confirmed none in this dataset).  
- Standardized inconsistent text and date formats.  
- Produced a clean dataset ready for further analysis or visualization.  
