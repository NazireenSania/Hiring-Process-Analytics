# 🧑‍💼 Hiring Process Analytics – Excel-Based HR Insights

This project analyzes hiring data from a company to uncover patterns in gender distribution, department-wise hiring, salary outliers, and role tiering. The analysis is performed using **Microsoft Excel**, and provides key insights for HR decision-making and workforce planning.

---

## 🧾 Project Overview

- 🛠 **Tool Used:** Microsoft Excel  
- 📊 **Dataset Size:** 7,168 rows × 7 columns  
- 📁 **Key Columns:** `application_id`, `Interview Taken on`, `Status`, `event_name`, `Department`, `Post Name`, `Offered Salary`

---

## 🧹 Data Cleaning

### 🔍 Missing Values
- Removed 393 rows with "Don't want to say" and 15 with hyphens in `event_name`.
- Deleted rows with missing values in `Post Name`.

### ❌ Why Not Use Imputation?
- Gender (categorical) could not be imputed without bias.
- Creating a new category would mislead the gender analysis.
- Most frequent value imputation was avoided to preserve balance.

---

## 📈 Data Analytics Tasks

A. 📊 Gender-wise Hiring Analysis
B. 💰 Salary Analysis
C.  Salary Distribution 
D. Departmental Analysis 
E. Position Tier Analysis 
