
# Customer Shopping Behavior Analysis

## Overview
This project analyzes customer shopping behavior using Python, MySQL, SQL, and Power BI. The workflow starts from raw CSV data, followed by data preprocessing and analysis in Jupyter Notebook, storing processed data in MySQL, performing SQL-based business queries, and finally building an interactive Power BI dashboard for visualization and insights.

---

# Project Workflow

```text
CSV Dataset
   ↓
Jupyter Notebook (EDA & Data Cleaning)
   ↓
Processed Data Stored in MySQL
   ↓
SQL Queries & Business Insights
   ↓
Power BI Dashboard & Visualization
```

---

# Project Structure

```text
Customer_Shopping_Behavior_Analysis/
│
├── README.md
├── customer_behavior_dashboard.pbix
├── customer_insights_queries.sql
├── customer_shopping_behavior.csv
├── shopping_behavior_analysis_eda.ipynb
```

---

# Dataset

Dataset used in this project:

```text
customer_shopping_behavior.csv
```

---

# Technologies Used

- Python
- Pandas
- MySQL
- SQLAlchemy
- SQL
- Power BI
- Jupyter Notebook

---

# Project Steps

## 1. Data Loading & Exploration

The CSV dataset was loaded into Jupyter Notebook for:
- data exploration
- checking null values
- understanding data types
- statistical analysis

Notebook used:

```text
shopping_behavior_analysis_eda.ipynb
```

---

## 2. Data Cleaning & Preprocessing

Performed preprocessing operations such as:
- handling missing values
- transforming columns
- formatting data
- adding/modifying rows and columns
- preparing dataset for analysis

---

## 3. Connecting Python to MySQL

The processed data from the notebook was connected and exported to MySQL using:
- SQLAlchemy

This enabled SQL-based querying and analysis.

---

## 4. SQL Analysis

SQL queries were written to generate business insights such as:

SQL file used:

```text
customer_insights_queries.sql
```

---

## 5. Power BI Dashboard

The cleaned data was loaded into Power BI to create an interactive dashboard for visualization and business insights.

Dashboard file:

```text
customer_behavior_dashboard.pbix
```

---

# Dashboard Preview


<img width="1378" height="745" alt="Dashboard" src="https://github.com/user-attachments/assets/8322b51e-6018-4185-bfaa-8d66b99b2c74" />


---

# Key Insights

- Identified popular shopping categories
- Analyzed customer spending behavior
- Compared review ratings across categories
- Studied shopping trends and customer preferences
- Generated business insights using SQL queries







