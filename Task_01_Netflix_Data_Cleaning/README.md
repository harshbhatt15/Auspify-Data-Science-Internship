# Netflix Data Cleaning & Preprocessing

## Objective
Clean and preprocess the Netflix dataset to make it suitable for further data analysis and machine learning.

## Dataset Overview
- Original Records: 8,790
- Final Records: 8,786
- Original Columns: 10
- Final Columns: 12

## Data Cleaning Steps
1. Inspected dataset structure and data types.
2. Identified missing and placeholder values.
3. Removed leading and trailing whitespace.
4. Converted "Not Given" placeholders into missing values.
5. Identified and removed 4 duplicate content records.
6. Converted `date_added` into datetime format.
7. Extracted numerical duration and duration units into separate columns.

## Final Results
- Final dataset shape: 8,786 × 12
- Duplicate rows: 0
- Missing director values: 2,587
- Missing country values: 287

## Technologies Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Output
`netflix_cleaned.csv`

## Conclusion
The dataset was successfully cleaned and transformed while preserving records with unavailable information. The resulting dataset is ready for exploratory data analysis.