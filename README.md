# Data Cleaning Project

## Overview
This project focuses on cleaning a customer call list dataset to prepare it for analysis. The dataset originally contained missing values, empty fields, and inconsistencies. The cleaning process ensures:

- Removal of rows with missing or empty phone numbers.
- Retention of only customers who can be contacted (`Do_Not_Contact = 'N'`).
- Creation of a clean Excel file ready for further analysis.

---

## Project Structure
- **Customer_Call_List_Cleaned.xlsx** – Cleaned dataset ready for analysis  
- **scripts/** – Folder containing the Python script  
  - `data_cleaning_script.py` – Python script used for cleaning  
- **README.md** – Project documentation

---

## Cleaning Steps
1. Loaded the raw Excel dataset using Pandas.
2. Stripped extra spaces from key columns.
3. Dropped rows with missing or empty `Phone_Number`.
4. Filtered rows to keep only `Do_Not_Contact = 'N'`.
5. Reset the DataFrame index.
6. Saved the cleaned dataset as an Excel file.

---

## Technologies
- Python 3.x
- Pandas
- Excel

---

## How to Use
1. Clone the repository:
```bash
git clone https://github.com/amara2002/Data_Cleaning.git
