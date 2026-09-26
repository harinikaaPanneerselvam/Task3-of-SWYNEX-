# Task 1 - Data Cleaning and Preparation

## Dataset
Startup Funding Dataset with information about startup name, industry, country,
funding stage, amount raised, funding date and number of employees.

## Objective
Clean and prepare a raw dataset for analysis by checking:
- Missing values
- Duplicate records
- Incorrect data types
- Inconsistent categorical values
- Invalid numeric/date values

## Tools Used
- Python
- Pandas
- Excel

## Cleaning Steps
1. Removed completely blank rows.
2. Removed exact duplicate records.
3. Trimmed extra spaces from text fields.
4. Converted `Amount Raised (USD)` and `Number of Employees` to numeric types.
5. Converted `Funding Date` to a proper date type.
6. Checked all columns for missing values.
7. Checked duplicate records.
8. Validated Industry, Country and Funding Stage against the values present in the dataset.
9. Checked that funding amount and employee counts are positive.

## Final Validation
- Rows: 2000
- Columns: 7
- Missing values: 0
- Duplicate rows remaining: 0
- Invalid categorical values: 0
- Invalid numeric values: 0
- Invalid funding dates: 0

## Files
- `cleaned_startup_funding_dataset.xlsx` - final Excel dataset with Quality Report
- `cleaned_startup_funding_dataset.csv` - cleaned CSV version
- `cleaning_log.txt` - cleaning actions and validation summary

## LinkedIn Video
For the required Task 1 LinkedIn video, briefly show:
1. The original dataset/problem statement.
2. Missing-value check.
3. Duplicate check.
4. Data-type validation.
5. Cleaning steps.
6. Final cleaned dataset and Quality Report.

Suggested post text:

Completed Task 1: Data Cleaning and Preparation

I cleaned and prepared a startup funding dataset for analysis using Python,
Pandas and Excel. I checked missing values, duplicate records, data types,
inconsistent categorical values and invalid values, then validated the final
dataset.

Key result:
2000 rows | 7 columns | 0 missing values | 0 duplicate rows remaining

#DataAnalytics #Python #Pandas #Excel #DataCleaning #Internship #Learning

## Submission
Upload this folder to a GitHub repository and submit the repository URL in the
internship Task Submission Link field. Then publish the LinkedIn video post and
paste the LinkedIn post URL in the second required field.
