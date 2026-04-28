# 🧹 UrbanStyle Customer Data Cleaning (Pandas Project)

## 📌 Overview

This project focuses on **data cleaning, transformation, and analysis** using Python and Pandas.
The dataset simulates customer data from an e-commerce brand called **UrbanStyle**, intentionally containing inconsistencies such as missing values, duplicates, and formatting issues.

The goal is to transform messy raw data into a **clean, structured, and analysis-ready dataset**, while also extracting meaningful business insights.

---

## ⚙️ Features

### ✅ Data Cleaning

* Handles missing values (median imputation, forward fill, defaults)
* Removes duplicate records
* Fixes inconsistent text formatting
* Standardizes phone numbers

### 🔄 Data Transformation

* Converts date columns to proper `datetime` format
* Cleans currency fields and converts to numeric
* Ensures correct data types for analysis

### 🧼 Data Standardization

* Proper capitalization for names
* Consistent category labels
* Uniform phone number format (`XXX-XXX-XXXX`)

### ➕ Feature Engineering

* `days_since_last_purchase`
* `average_purchase_value`
* `purchase_frequency_category` (High / Medium / Low)

### 📊 Data Analysis

* Average spending by loyalty status
* Revenue by product category
* Correlation between satisfaction and spending

---

## 🗂️ Dataset Details

The dataset includes:

* Customer information (name, email, phone)
* Purchase behavior (total purchases, total spent)
* Preferences (category, loyalty status)
* Demographics (age, city, state)

⚠️ Note: The dataset is **simulated using `StringIO`** and includes intentional errors for learning purposes.

---

## 🚀 How to Run

### 1. Install Dependencies

```bash
pip install pandas numpy
```

### 2. Run the Script

```bash
python module10-assignment.py
```

---

## 📈 Output

The script generates:

### 🧾 Data Cleaning Report

* Total missing values
* Duplicate records
* Data type issues identified

### 🔧 Standardization Summary

* Names formatted properly
* Categories standardized
* Phone numbers cleaned

### 💡 Business Insights

* Total number of customers
* Average spending by loyalty tier
* Top-performing product category

### 📋 Clean Dataset Preview

Displays the first 5 rows of the final cleaned dataset.

---

## 🧠 Key Concepts Demonstrated

* Data cleaning with **Pandas**
* Handling missing and inconsistent data
* Feature engineering
* Exploratory data analysis (EDA)
* Real-world data preprocessing workflow

---

## 📁 Project Structure

```
├── module10-assignment.py   # Main script
└── README.md                # Project documentation
```

---

## 🏁 Final Output

The final dataset (`df_final`) is:

* Cleaned
* Deduplicated
* Properly formatted
* Ready for analysis or visualization




