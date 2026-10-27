# Reading Data from Various Sources Using Pandas

## 📌 Project Overview
This project demonstrates how to read, process, display, and export data from different sources using Python and the Pandas library. It covers working with JSON, CSV, HTML tables, Excel files, and Pickle files.

## 🎯 Objectives
- Learn how to import data from different file formats and online sources.
- Understand how to convert JSON data into a Pandas DataFrame.
- Read CSV files from online datasets.
- Extract tables from HTML webpages.
- Read and write Excel files.
- Save and load data using Pickle files.
- Export DataFrames into different formats.

## 🛠️ Technologies Used
- Python
- Pandas
- OpenPyXL
- Jupyter Notebook

## 📚 Topics Covered

### 1. Reading JSON Data
- Imported JSON data using `pd.read_json()`.
- Used `StringIO` to read JSON strings.
- Converted DataFrames into JSON using `df.to_json()`.
- Explored different JSON orientations, including `index` and `records`.
- Accessed individual DataFrame columns and nested JSON values.

### 2. Reading CSV Files
- Imported CSV data using `pd.read_csv()`.
- Loaded the Wine dataset from an online source.
- Displayed the first few rows using `data.head()`.
- Exported data to a CSV file using `data.to_csv()`.

### 3. Reading HTML Tables
- Used `pd.read_html()` to extract tables from webpages.
- Retrieved bank-related information from an online HTML table.
- Selected a specific table from the returned list.
- Displayed the first and last rows using `head()` and `tail()`.

### 4. Extracting Tables Using Conditions
- Used the `match` parameter in `pd.read_html()`.
- Extracted tables containing country-related information.
- Worked with mobile country codes and related details.

### 5. Reading Excel Files
- Imported Excel data using `pd.read_excel()`.
- Loaded sample data containing names and ages.
- Used the OpenPyXL library to support Excel file operations.

### 6. Working with Pickle Files
- Saved a DataFrame in Pickle format using `to_pickle()`.
- Loaded saved data using `pd.read_pickle()`.
- Learned how to store and retrieve Python objects.

## 💻 Libraries Used

```python
import pandas as pd
from io import StringIO
import openpyxl
```

## 📂 Project Files
- `README.md` — Project documentation.
- Jupyter Notebook (`.ipynb`) — Python code and practical examples.
- `sample_data.xlsx` — Sample Excel dataset used in the notebook.
- `wine1.csv` — CSV file generated from the Wine dataset.
- Pickle file — Saved DataFrame in Pickle format.

## ✅ Key Learnings
- Reading data from JSON, CSV, Excel, and HTML sources.
- Extracting tables from webpages.
- Selecting DataFrame columns and accessing nested values.
- Exporting data into CSV and JSON formats.
- Saving and retrieving data using Pickle.
- Understanding practical applications of Pandas for data handling.

## 🚀 Conclusion
This project provides practical experience in handling data from multiple sources using Python and Pandas. It helps build a foundation in data ingestion, data manipulation, and data export, which are important skills in Data Analytics.

## 👩‍💻 Author
**Pooja Janu Jore**# Read-data-from-various-sources
Read data from various sources using Python Pandas.
