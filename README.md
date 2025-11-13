Data Cleaning & Preprocessing
Data Analyst Internship – Balaji Fast Food Sales Dataset

📌 Objective
Clean and preprocess a raw sales dataset by handling missing values, fixing inconsistent formats, removing duplicates, and creating a clean dataset ready for analysis.

🧹 Steps Performed
1. Loaded the Dataset

Used Pandas to read "Balaji Fast Food Sales.csv".

2. Checked Data Quality

Missing values using .isnull().sum()

Duplicate records using .duplicated().sum()

3. Standardized Date Column

Converted date format to: 👉 dd-mm-yyyy Handled errors using errors='coerce'.

4. Filled Missing Transaction Type

Used mode() to fill missing values in transaction_type.

5. Fixed Missing Item Prices

Separated rows with null item_price.

Applied a custom function to assign correct prices based on item name.

Merged back with non-null rows.

6. Fixed Missing Item Type

Categorized items into:

Fastfood

Beverages

Filled missing values using a mapping function.

7. Exported Final Cleaned Dataset

Exported as Sales cleaned_data.csv with:

No missing values

No duplicates

Standardized formats

Correct item prices & types
