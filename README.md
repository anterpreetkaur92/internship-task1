Dataset: Customer Personality Analysis (Kaggle)

Objective: Clean and prepare the dataset for analysis.

Summary of Changes:

Step	Action	Details
1	Missing Values	Filled Income missing values with median.
2	Duplicates	Removed 15 duplicate rows.
3	Date Format	Converted Dt_Customer to datetime (dd-mm-yyyy).
4	Column Names	Renamed columns to lowercase with underscores.
5	Data Types	Converted year_birth to int and verified numeric fields.
6 Drop Column dropped the dt_customer column due to data imbalance.
6	Export	Saved final cleaned file as cleaned_customer_personality.csv.
