# online-retail-data-cleaning-week1
Week 1 internship project on data cleaning, preprocessing, feature engineering, and sales analysis using Python and Pandas.

## Project Overview

This project was completed as part of my Week 1 internship assignment. The project focuses on cleaning, preprocessing and analyzing the UCI Online Retail Dataset using Python and Pandas.

## Dataset

The dataset used in this project is the **Online Retail Dataset** from the UCI Machine Learning Repository.

It contains transaction information such as:

- Invoice number
- Product code
- Product description
- Quantity
- Invoice date
- Unit price
- Customer ID
- Country

## Data Cleaning and Preprocessing

The following steps were performed:

- Checked the structure and data types of the dataset
- Identified and removed duplicate records
- Handled missing values
- Identified cancelled transactions
- Removed non-positive UnitPrice values
- Checked Quantity and UnitPrice for invalid values
- Examined outliers using boxplots
- Created a `TotalAmount` feature
- Extracted Year, Month, Day and Hour from InvoiceDate
- Performed final data validation

## Exploratory Data Analysis

The cleaned dataset was analyzed to understand:

- Overall sales metrics
- Country-wise sales
- Product-wise sales
- Monthly sales trends

## Final Dataset

After preprocessing:

- **Rows:** 392,692
- **Columns:** 13
- **Missing values:** 0
- **Duplicate rows:** 0
- **Total Sales:** Approximately 8.89 million
- **Total Quantity Sold:** 5,152,002
- **Unique Transactions:** 18,532

## Files Included

- `Online Retail.xlsx` – Original dataset
- `Online_Retail_Cleaned.csv` – Cleaned dataset
- `Week 1 - Online Retail Data Cleaning.ipynb` – Google Colab/Jupyter Notebook
- `Week 1 - Online Retail Data Cleaning Report.docx` – Detailed project report

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Dataset Source

UCI Machine Learning Repository – Online Retail Dataset

https://archive.ics.uci.edu/dataset/352/online+retail
