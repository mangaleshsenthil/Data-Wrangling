# 📊 CSV & Excel Data Processing Lab

## 📁 Overview

This repository contains practical notebooks for working with CSV, JSON, XML, and Excel (XLS/XLSX) data formats using Python, developed as part of coursework for the Data Wrangling subject.

It demonstrates multiple libraries and approaches for reading, processing, and analyzing structured data.

---

## 📂 Contents

### 🔹 CSV, JSON & XML

* Data loading and parsing
* Format conversion
* Basic preprocessing

Notebook:

* `lab_csv_json_xml.ipynb`

---

### 🔹 Excel Processing (Multiple Libraries)

This repository explores different tools to work with Excel files:

* `pandas` → Data analysis and manipulation
* `calamine` → Fast Excel reading
* `pyexcel` → Unified API for spreadsheet formats
* `xlwings` → Excel automation and integration

Notebooks:

* `xlsx xls.ipynb`
* `xlsx xls using pandas.ipynb`
* `xlsx xls using calamine.ipynb`
* `xlsx xls using pyexcel.ipynb`
* `xlsx xls using xlwings.ipynb`

---

## 🎯 Objectives

* Understand different data formats (CSV, JSON, XML, Excel)
* Compare Python libraries for Excel handling
* Perform basic data preprocessing tasks
* Build a foundation for data engineering workflows

---

## ⚙️ Requirements

Install dependencies:

```bash
pip install pandas pyexcel xlwings
```

---

## 🚀 Usage

Run notebooks using:

* Jupyter Notebook
* JupyterLab

Example:

```python
import pandas as pd
df = pd.read_excel("file.xlsx")
print(df.head())
```

---

## 📌 Notes

* This repository is intended for **learning and experimentation**
* Datasets included are for **practice purposes**
* Focus is on **data handling techniques**, not large-scale datasets

---

## 👤 Author

Maintained by *Mangalesh Senthil*
