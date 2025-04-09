# python-data-cleaner

# 🧹 Data Cleaning Master

**Data Cleaning Master** is a Python CLI tool designed to clean raw datasets quickly and efficiently. It removes duplicate entries, handles missing values based on column type, and saves both cleaned data and a record of removed duplicates. Perfect for preprocessing your data before analysis or modeling!

---

## 📌 Features

- ✅ Accepts `.csv` and `.xlsx` files
- ✅ Checks and removes duplicate records
- ✅ Saves a copy of all duplicates separately
- ✅ Identifies missing values
- ✅ Replaces missing **numeric values** with the **mean**
- ✅ Drops rows with missing **non-numeric values**
- ✅ Saves the cleaned dataset as a new CSV
- ✅ User-friendly CLI with helpful prompts and wait messages

---

## 🛠️ Technologies Used

- Python 3
- pandas
- numpy
- openpyxl
- xlrd
- time
- os
- random

---

## 🚀 Getting Started

### Prerequisites

Make sure Python is installed along with these packages:

```bash
pip install pandas numpy openpyxl xlrd

python data_cleaning_master.py
You’ll be prompted to enter:

📁 Dataset file path

📌 Dataset name (used to save output files)

📂 Output Files
After cleaning, the script will generate:

your_dataset_duplicates.csv → contains all removed duplicate rows

your_dataset_Clean_data.csv → the final cleaned dataset

Example
Please enter dataset path : C:/Users/Amrish/Desktop/sales.xlsx
Please enter dataset name : jan_sales
Output files created:

jan_sales_duplicates.csv

jan_sales_Clean_data.csv

**📊 Use Cases**
Data cleaning for machine learning

Preparing sales/marketing reports

Cleaning user-submitted Excel sheets

Academic and project-based data work

📈 Future Improvements
Support .json or .txt file types

Option to choose median/mode for imputation

GUI version using Tkinter or Streamlit

Save logs for data audit trail



🙌 Author
Amrish raja
🎓 B.Tech in Biomedical + MBA in Data Analysis
📊 Passionate about automation, data science & simplifying workflows

