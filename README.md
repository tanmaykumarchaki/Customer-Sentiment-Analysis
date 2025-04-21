# Customer-Sentiment-Analysis

## Aim of the Task 
- To clean a raw data 
- Removing Null values 
- Removing Duplicates 
- Correcting Data Formats
- Renaming the Columns


## Tool Used
- Python Programming language 
- Python Library - Pandas 

## Tasks Performed 
- STEP 1:The Data was displayed on the notebook using `read_csv()` .
- STEP 2:Then EDA was Performed such as Checking Null Values `df.isnull()` , Index Size `df.set_index()`, Duplicates `df.duplicated()` and Total Columns `df.columns`.
- STEP 3:Dropped all null values using `dropna()` function in Pandas.
- STEP 4:Then some raw columns were modified by name to understand the data clearly using `df.rename(columns=())`.
- STEP 5:Then the 'Date of Completion' column's datatype was converted from object to datetime64[ns]. Here `df.dtypes` used for spectating datatypes and `pd.to_datetime()` was used to convert the Datatype.
- STEP 6:Lastly Saved the Modified CSV file using `df.to_csv()`.
