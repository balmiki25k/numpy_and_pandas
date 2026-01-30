# Pandas Data Analysis

This repository contains a Google Colab notebook (`pandas.ipynb`, `data overview.ipynb`, and `first_3_rows.csv`). The goal was to practice fundamental data manipulation and exploration techniques using the `pandas` library.

## Files in this Repository

*   `student_dataset.csv`: This is the random (sample practice data) primary dataset I used for the analysis.
*   `first_3_rows.csv`: This file was generated during the analysis, containing the first 3 rows of the `student_dataset.csv`.
*   `train.csv`: This dataset contains the Titanic survival data

## Analysis Performed

During this exercise, I performed the following steps:

1.  **Data Loading**: Loaded the `student_dataset.csv` into a Pandas DataFrame.
2.  **Initial Data Exploration**: Used `head()`, `tail()`, and `sample()` to get a quick overview of the data.
3.  **Data Export**: Extracted the first 3 rows of the DataFrame and saved them to a new CSV file (`first_3_rows.csv`).
4.  **Feature Engineering**: Created a new column named `Total_Score` by summing the `ID` and `Marks` columns.
5.  **Data Quality Check**: Examined missing values using `isnull()`, reviewed data types and non-null counts with `info()`, and generated descriptive statistics using `describe()`.
6.  **Data Selection**: Practiced selecting rows and columns using both label-based (`loc`) and integer-location-based (`iloc`) indexing.

This project served as a hands-on practice for essential Pandas operations. Feel free to explore the notebook for the code implementation of these steps.

