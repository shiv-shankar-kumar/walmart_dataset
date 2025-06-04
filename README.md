# 🛠️ Walmart Sales Data - ETL & Business Intelligence Project

This project demonstrates a complete **ETL (Extract, Transform, Load)** pipeline and **Business Intelligence** solution built using **Python**, **MySQL**, and **SQL**, based on real-world sales data from **Walmart**, one of the largest retail chains worldwide.

---

## 📌 Project Overview

- **Goal:** Extract raw sales data → Clean & transform → Load into database → Analyze to uncover business insights
- **Data Source:** Kaggle (via Kaggle API)
- **Tools & Tech:** Python, Pandas, SQLAlchemy, MySQL, Jupyter Notebook

---

## 🔄 ETL Pipeline

### ✅ Extract
- Pulled the sales dataset directly from **Kaggle’s cloud repository** using the **Kaggle API** into a **Jupyter Notebook** environment.


### ✅ Transform
- Cleaned and transformed data using **Pandas**:
  - Removed duplicate records
  - Handled and imputed missing/null values
  - Reformatted columns (e.g., date/time, category fields) for consistency and usability

https://github.com/shiv-shankar-kumar/walmart_dataset/blob/main/project.ipynb

### ✅ Load
- Loaded the cleaned dataset into a **local MySQL database** using **SQLAlchemy’s `create_engine()`** method.

https://github.com/shiv-shankar-kumar/walmart_dataset/blob/main/sql_query.ipynb

---

## 📊 Business Analysis & SQL Insights

Wrote and executed SQL queries to extract critical insights for stakeholders:

- 🔹 Identified **payment methods**, number of transactions, and quantity sold by each
- 🔹 Determined the **highest-rated product categories** for each branch
- 🔹 Found the **busiest day** of the week per branch based on transaction volume
- 🔹 Calculated **total quantity sold per payment method**
- 🔹 Derived **average, minimum, and maximum ratings** by product category and city
- 🔹 Identified **top 5 branches** with the **highest revenue decline** from 2022 to 2023
- 🔹 Categorized sales into **time-based shifts**: Morning, Afternoon, Evening

---

## 🧰 Tech Stack

| Component       | Tool/Library           |
|----------------|------------------------|
| Language        | Python, SQL            |
| Data Handling   | Pandas                 |
| Database        | MySQL (Local)          |
| ORM             | SQLAlchemy             |
| Notebook Env.   | Jupyter Notebook       |
| Data Source     | Kaggle (API-based)     |

---
