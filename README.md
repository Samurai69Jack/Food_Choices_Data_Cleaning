# 🍽️ Food Survey Cleaning Project

This project contains the cleaning and preprocessing of an open-ended survey dataset on **comfort food preferences, habits, and demographics**.

## 📊 Dataset
- **Raw data**: [`food_coded.csv`](food_coded.csv) (original uncleaned file).
- **Cleaned data**: [`food_coded_clean.csv`](food_coded_clean.csv) (after preprocessing).

The raw data contains:
- Open-ended responses with messy separators (`/, \, \n, \r, ...`).
- Mixed data types (e.g., weights recorded as text).
- Missing values and inconsistent formatting.

The cleaned data provides:
- Consistent separators (`,`).
- Numeric values extracted and imputed where appropriate.
- Missing values handled with strategies like mean/median/mode imputation.
- Text fields normalized.

## ⚙️ Cleaning Process
The main cleaning steps included:
1. Handling missing values (`NaN`).
2. Normalizing open-ended responses (comfort foods, hobbies, etc.).
3. Extracting numeric values (e.g., weight in pounds).
4. Replacing inconsistent separators with commas.
5. Removing duplicates, extra spaces, and trailing characters.

All transformations are reproducible using the [`food_coded_data_clean.py`](food_coded_data_clean.py) script 

## 📂 Repository Structure
