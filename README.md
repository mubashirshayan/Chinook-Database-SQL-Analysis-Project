# # SQLite Table Joins – Practice Project

This repository contains a **SQLite SQL practice notebook** focused on **table joins, aggregations, filtering, and analytical queries** using a music store–style database (customers, invoices, tracks, albums, artists, employees, genres).

The project is implemented in a **Jupyter Notebook (`.ipynb`)** and is designed to strengthen practical SQL skills for **data analysis and reporting**.

---

## 📌 Objectives

* Practice **INNER JOIN, LEFT JOIN** concepts
* Apply **GROUP BY, HAVING, ORDER BY**
* Perform **real-world analytical queries**
* Build confidence for **data analyst / research roles**

---

## 🛠 Tools & Technologies

* **SQLite**
* **SQL**
* **Jupyter Notebook**
* **DB Browser for SQLite / SQLite3** (optional)

---

## 📂 File Structure

```
SQL_Tablejoin.ipynb   # Main notebook with all SQL queries and explanations
chinook.db            # Database File
README.md             # Project documentation
```

---

## 🔍 Key SQL Concepts Covered

* Table Joins (INNER JOIN, LEFT JOIN)
* Aggregate Functions (SUM, COUNT)
* Grouping & Filtering (GROUP BY, HAVING)
* Pattern Matching (LIKE, wildcards)
* Subqueries & CTE-style logic
* Ranking & Top-N analysis

---

## 📊 Queries Implemented

### 1️⃣ Invoice & Track Analysis

* Fetch invoice details with track name, media type, quantity, and unit price
* Filter results using specific invoice IDs

### 2️⃣ Album & Artist Analysis

* List tracks with album titles and artist names
* Identify albums with **more than 10 tracks**
* Count number of tracks per genre

### 3️⃣ Sales Insights

* **Top 5 selling tracks**
* Number of tracks sold per album
* Customer-wise total spending

### 4️⃣ Customer Analytics

* Best customer from each country by total spending
* Top 5 customers by invoice count and amount spent
* Categorize customers based on spending

### 5️⃣ Employee Hierarchy

* Fetch employee details with reporting managers

### 6️⃣ Pattern Matching & Filtering

* Customers whose names contain specific characters (e.g., 'JEN')

---

## ▶️ How to Run the Project

1. Install **SQLite** and **Jupyter Notebook**
2. Open the notebook:

```bash
jupyter notebook SQL_Tablejoin.ipynb
```

3. Run cells sequentially to view queries and outputs

---

## 🎯 Learning Outcomes

* Improved understanding of **relational databases**
* Hands-on experience with **analytical SQL queries**
* Ready-to-showcase SQL project for **GitHub & LinkedIn**

---

## 🚀 Future Improvements

* Convert queries into **views**
* Add **query optimization examples**
* Visualize results using **Python (Matplotlib / Plotly)**

---

## 👤 Author

**Mubashir Shayan Raees**
Aspiring Data Analyst | SQL | Data Analytics

---

⭐ If you find this project helpful, feel free to star the repository!
