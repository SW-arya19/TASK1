# TASK1
## Dataset Used
- **Name**: Customer Personality Analysis
- **Source**: [Kaggle Dataset]/kaggle/input/customer-personality-analysis/marketing_campaign.csv
- **File**: `marketing_campaign.csv`
## Objective
Clean and prepare the dataset by:
- Handling missing values
- Removing duplicates
- Standardizing text columns
- Converting date formats
- Renaming columns
- Ensuring correct data types
## Tools Used
- Python (Pandas)
## Cleaning Steps Performed
- Loaded dataset with correct tab separator (`sep='\t'`) and for excel included the delimiter option of comma and space to shift them into different coloumns.
- Removed rows with missing `Income` and used Filter option in Excel to check for blank rows.
- Stripped and standardized text columns (`Education`, `Marital_Status`)
- Converted `Dt_Customer` and 'year_birth' to `datetime` format and standardized as `dd-mm-yyyy` and simply changed their formats in excel to Short Date format from General
- Removed duplicates using df = df.drop_duplicates() and in ecel using remove duplicates option in data grid
- Renamed all columns to lowercase with underscores usig excel function =LOWER()
- Added an `age` column derived from `year_birth` by simply subtracting 2025-birth year coloumn
  ## Files Included
- `task1.py`: Python script with cleaning steps
- `marketing_campaign.csv`: Raw dataset
- `cleaned_marketing_campaign.csv`: Final cleaned dataset
- `README.md`: This file
  https://drive.google.com/drive/folders/1ICLLbB_yuHxrkpmLGnapQlmKh9heEAl9?usp=sharing
