# 🧹 Data Cleaning Task – Sales Dataset

## 📌 Internship Task Overview

This task was assigned as part of a **Data Analyst Internship** to demonstrate real-world data preprocessing skills. The dataset used was a sales data file containing order details, customer information, and transaction metrics.

---

## 🎯 Objective

Clean and preprocess the raw dataset to make it ready for analysis or modeling. The dataset had potential issues like inconsistent formatting, unstandardized text, and irregular column naming.

---

## 🛠 Tools Used

- Python
- Pandas

---

## 📂 Files Included

- `cleaned_sales.csv` – Final cleaned version of the dataset  
- `sales.csv.xlsx` – Original uncleaned dataset (optional)  
- `README.md` – This documentation

---

## 🧼 Cleaning Steps Performed

### ✅ 1. **Checked for Missing Values**
- No missing values were found across any of the columns.

### ✅ 2. **Checked for Duplicate Rows**
- No duplicate entries were present in the dataset.

### ✅ 3. **Standardized String Columns**
- Converted all text columns (e.g., `Country`, `Segment`, `Ship Mode`, etc.) to **title case**.
- Removed leading/trailing whitespaces.

### ✅ 4. **Formatted Dates**
- Converted the `order_date` column to **datetime** format using `pd.to_datetime()`.

### ✅ 5. **Renamed Columns**
- All column names were converted to **snake_case** for consistency and ease of use in analysis (e.g., `Order Date` → `order_date`).

---

## 🧠 Key Learnings

- Importance of consistent formatting for analysis-ready data
- Best practices for data type handling and text normalization
- Practical exposure to using Pandas for data cleaning

---

## 🚀 Outcome

This task prepared a real-world dataset for further data analysis or visualization, ensuring it met the necessary quality standards. The cleaned dataset is now ready for tasks like:
- Exploratory Data Analysis (EDA)
- Dashboarding
- Machine Learning
- Reporting

---

## 👨‍💻 Author

**Koushik Yarra**  
Data Science Undergraduate | Aspiring Data Analyst  
