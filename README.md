# 📌 SQL Developer Internship – Task 4  
## Aggregation, Grouping, and HAVING

This task focuses on using *aggregate functions* and *GROUP BY* to summarize and analyze data in SQL.

---

## 🚀 Objective
- Use aggregate functions such as *SUM, COUNT, AVG, MIN, MAX*
- Apply *GROUP BY* to group records
- Filter groups using *HAVING*
- Understand COUNT(*) vs COUNT(column)
- Use ROUND() and DISTINCT

---

## 🛠 Tools Used
- DB Browser for SQLite  
- MySQL Workbench  
- Any SQL-compatible database  

---

## 📁 Deliverables
This repository contains:

- task4_aggregation.sql → SQL queries using  
  *SUM, COUNT, AVG, GROUP BY, HAVING, DISTINCT, ROUND*
- README.md → Explanation of the task and concepts

---

## 📝 SQL Topics Covered

### *1️⃣ Aggregate Functions*
- SUM()
- AVG()
- COUNT()
- MIN()
- MAX()

### *2️⃣ GROUP BY*
Used to group rows and perform computations on each group.

### *3️⃣ HAVING*
Filters groups after aggregation (WHERE cannot be used).

### *4️⃣ COUNT() vs COUNT(column)**
- COUNT(*) counts all rows  
- COUNT(column) ignores NULL values  

### *5️⃣ ROUND()*
Rounds numeric values (commonly used with AVG).

### *6️⃣ DISTINCT*
Used to count unique values.

---

## 📌 How to Run
1. Open your SQL editor (SQLite, MySQL Workbench, or DB Browser)
2. Create a sample employees table (or use your own dataset)
3. Copy the SQL code from task4_aggregation.sql
4. Run each query step-by-step

---

## 📚 Sample Table Structure (Optional)
```sql
CREATE TABLE employees (
    id INTEGER PRIMARY KEY,
    name TEXT,
    department TEXT,
    job_role TEXT,
    salary INTEGER
);
