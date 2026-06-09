# 🎵 Chinook Database – SQL Analysis Project

This project contains SQL queries and analysis performed on the **Chinook Database (`chinook.db`)**, a sample digital media store database.
The analysis focuses on practicing **SQL joins, aggregations, grouping, filtering, ranking, and customer segmentation**.

---

## 📂 Project Files
Chinook-Database-SQL-Analysis-Project/
├─ README.md
├─ Chinook_Sqlite_Analysis/
│ ├─ chinook_schema.png
│ ├─ Chinook_Sqlite.sqlite
│ └─ chinook-database-sql-analysis-project.ipynb


---
![Schema](https://github.com/mubashirshayan/Chinook-Database-SQL-Analysis-Project/blob/main/Chinook_Sqlite_Analysis/schema.png)


## 🛠 Tools & Technologies Used

* **SQLite**
* **SQL**
* **Python (pandas)**
* **Jupyter Notebook**

---

## 🗂 Database Overview

The Chinook database represents a digital music store and includes tables such as:

* `customer`
* `invoice`
* `invoice_line`
* `track`
* `album`
* `artist`
* `genre`
* `media_type`
* `employee`

These tables are connected through primary and foreign keys, allowing relational analysis.

---

## 📊 Key SQL Concepts Covered

* ✅ INNER JOIN & LEFT JOIN
* ✅ Self Join (Employee–Manager relationship)
* ✅ GROUP BY & HAVING
* ✅ Aggregate Functions (COUNT, SUM)
* ✅ CASE Statements (Customer Segmentation)
* ✅ Ranking (Top customers by country)
* ✅ Filtering & Sorting

---

## 🔎 Analysis Performed

### 1️⃣ Customer Analysis

* Customer-wise invoice count and total spending
* Customer segmentation (Small, Regular, Big Spender)
* Top-spending customer in each country

### 2️⃣ Sales Analysis

* Invoice-wise track details
* Number of tracks sold per album
* Album sales performance

### 3️⃣ Music Catalog Analysis

* Number of tracks in each genre
* Albums with more than 10 tracks
* Track details with album and artist information

### 4️⃣ Employee Reporting Structure

* Employee details with reporting manager
* Self join to replace `reports_to` ID with supervisor name

---

## ▶️ How to Run This Project

1. Install SQLite and Jupyter Notebook.
2. Place `chinook.db` in the same directory as the notebook.
3. Open the notebook:

```bash
jupyter notebook SQL_Tablejoin.ipynb
```

4. Run all cells sequentially.

---

## 🎯 Learning Outcomes

Through this project, I strengthened my ability to:

* Write structured and optimized SQL queries
* Perform relational joins correctly
* Apply aggregation and grouping logic
* Derive business insights from raw data
* Implement customer segmentation using CASE statements

---

## 🚀 Future Improvements

* Add data visualization (Matplotlib / Plotly)
* Create a dashboard version of analysis
* Optimize queries for performance
* Convert analysis into a business case study

---

## 👤 Author

**Mubashir Shayan Raees**
Aspiring Data Analyst | SQL | Data Analytics

---

⭐ If you found this project useful, feel free to star the repository!

