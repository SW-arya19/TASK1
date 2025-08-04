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
- Loaded dataset with correct tab separator (`sep='\t'`)
- Removed rows with missing `Income`
- Stripped and standardized text columns (`Education`, `Marital_Status`)
- Converted `Dt_Customer` and 'year_birth' to `datetime` format and standardized as `dd-mm-yyyy`
- Removed duplicates
- Renamed all columns to lowercase with underscores
- Added an `age` column derived from `year_birth`
  ## Files Included
- `task1.py`: Python script with cleaning steps
- `marketing_campaign.csv`: Raw dataset
- `cleaned_marketing_campaign.csv`: Final cleaned dataset
- `README.md`: This file
  https://drive.google.com/drive/folders/1ICLLbB_yuHxrkpmLGnapQlmKh9heEAl9?usp=sharing
