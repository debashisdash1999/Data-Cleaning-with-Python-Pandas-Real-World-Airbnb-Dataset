# 🧹 Data Cleaning Using Python Pandas

## 📌 Project Overview
This project focuses on **data cleaning using Python and Pandas** with a real-world dataset. The goal is to transform raw, messy data into a clean, reliable, and analysis-ready format. Data cleaning is a critical step in any data science workflow, as poor data quality can lead to incorrect insights and unreliable models.

This project is inspired by a hands-on tutorial that demonstrates practical data cleaning techniques on an **Airbnb dataset sourced from Kaggle**.

---

## 🎯 Objectives
- Understand common data quality issues in real-world datasets
- Learn how to identify and handle missing values
- Perform data type conversions and transformations
- Clean and standardize categorical and text data
- Remove duplicate records
- Improve dataset readability and consistency
- Prepare data for further analysis or machine learning

---

## 📂 Dataset Information
- **Dataset Name:** Airbnb Listings Dataset
- **Source:** Kaggle
- **Type:** Real-world data
- **Content Includes:**
  - Listing prices
  - Location (latitude, longitude, neighbourhood)
  - Room types
  - Host details
  - Reviews and availability

This dataset contains several common data issues such as missing values, inconsistent text formatting, incorrect data types, and duplicate records, making it ideal for data cleaning practice.

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Anaconda Distribution
- Jupyter Notebook (used to perform all Python and Pandas data cleaning operations)

---

## 🔍 Data Cleaning Steps Performed

### 1️⃣ Handling Missing Values
- Identified missing values using `isnull()` and `sum()`
- Dropped rows or columns with excessive missing data where appropriate
- Filled missing numerical values using:
  - Mean
  - Median
- Filled missing categorical values using:
  - Mode
  - Constant values like `"Unknown"`
- Handled Airbnb-specific missing values such as:
  - `reviews_per_month`
  - `last_review`

---

### 2️⃣ Data Type Conversion
- Inspected data types using `df.info()` and `df.dtypes`
- Converted:
  - Price columns from object to numeric
  - Date columns to `datetime`
  - Integer-based columns like `minimum_nights` and `number_of_reviews`
- Used error handling during conversions to avoid crashes

---

### 3️⃣ Data Transformation & Feature Engineering
- Extracted components from date columns (year, month, day)
- Created derived features when needed
- Cleaned text data by:
  - Converting text to lowercase
  - Removing extra spaces
  - Standardizing categorical values

---

### 4️⃣ Renaming Columns
- Renamed columns to improve readability and consistency
- Simplified long column names
- Followed a clear and consistent naming convention

---

### 5️⃣ Removing Duplicate Records
- Identified duplicate rows using `duplicated()`
- Removed duplicates using `drop_duplicates()`
- Retained appropriate records using `keep` parameter

---

### 6️⃣ Handling Outliers
- Identified outliers using statistical methods and visual inspection
- Focused on columns such as:
  - Price
  - Minimum nights
- Decided whether to cap, transform, or remove extreme values based on context

---

### 7️⃣ Data Validation & Consistency Checks
- Ensured logical consistency in numerical columns
- Verified geographical values like latitude and longitude
- Standardized categorical values such as room types

---

## 📈 Final Outcome
- Cleaned and well-structured dataset
- Improved data consistency and reliability
- Dataset ready for:
  - Exploratory Data Analysis (EDA)
  - Visualization
  - Machine Learning models

---

## 📚 Key Learnings
- Data cleaning is an **iterative and essential process**
- Real-world data is often messy and inconsistent
- Pandas provides powerful and flexible tools for cleaning data efficiently
- Clean data leads to better insights and better models

---

⭐ If you find this project useful, feel free to star the repository!

