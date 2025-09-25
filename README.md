# 📘 Task 3 – SQL SELECT Queries (Library Management System)  

## 📌 Overview  
This task demonstrates how to use **SQL SELECT queries** on the **Library Management System** database created in Task 1 & 2.  
The queries showcase retrieving data, filtering rows, and sorting results.  

---

## 🗂️ Queries Demonstrated  

### 🔹 1. SELECT * and specific columns  
- Fetch all data from `Members`.  
- Fetch only selected columns (`title, author, published_year`) from `Books`.  
- Fetch loan details from `Loans`.  

### 🔹 2. Filtering with WHERE, AND, OR, LIKE, BETWEEN  
- Find members with phone numbers (`IS NOT NULL`).  
- Find books published after 2020 with more than 3 copies (`AND`).  
- Find staff with role Librarian or Manager (`OR`).  
- Search books with titles containing `"SQL"` (`LIKE`).  
- Find books published between 2019 and 2022 (`BETWEEN`).  

### 🔹 3. Sorting with ORDER BY  
- Sort books by published year (ascending).  
- Sort books by available copies (descending).  
- Sort members alphabetically by name.  

---

## 📂 Files Included  
SQL DDL file: [`library_schema_task3.sql`](library_schema_task3.sql)

---

## ✅ Outcome  
By completing this task, you will learn how to:  
- Retrieve all or specific columns from a database table.  
- Apply conditional filters to fetch meaningful results.  
- Sort query results in ascending or descending order.  

This builds the foundation for **data extraction and analysis** using SQL.  
