# 🧹 Data Cleaning and Preprocessing Task

## Dataset:
[Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

## Objective:
To clean and prepare the dataset for analysis by handling missing values, duplicates, inconsistent formats, and standardizing fields.

## Steps Performed:

1. **Missing Values**  
   - Found 24 missing values in `Income`
   - Filled them using median income value

2. **Duplicates**  
   - Checked and removed any duplicate records

3. **Standardization**  
   - Lowercased and stripped whitespaces in categorical columns like `Education` and `Marital_Status`

4. **Date Format**  
   - Converted `Dt_Customer` to consistent `datetime` format

5. **Column Clean-Up**  
   - Renamed all column headers to lowercase with underscores

6. **Exported**  
   - Saved the final cleaned dataset to `cleaned_customer_data.csv`

## Tools Used:
- Python
- Pandas
- Jupyter Notebook

---

