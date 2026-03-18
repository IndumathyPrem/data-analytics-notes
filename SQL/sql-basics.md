# 🗄️ SQL Basics ( Notes)

 1. What is SQL?

| Topic | Description |
|------|------------|
| SQL | Structured Query Language |
| Purpose | To store, retrieve, and manipulate data |
| Used In | Databases (MySQL, PostgreSQL, etc.) |

2. SELECT Statement

| Syntax | Description |
|--------|------------|
| SELECT * FROM table_name; | Fetch all columns |
| SELECT col1, col2 FROM table_name; | Fetch specific columns |

 3. WHERE Clause

| Syntax | Purpose |
|--------|--------|
| WHERE condition | Filters rows |

### Example
SELECT * FROM students  
WHERE marks > 80;

 4. Operators

| Type | Examples |
|------|---------|
| Comparison | =, >, <, >=, <= |
| Logical | AND, OR, NOT |
| Special | IN, BETWEEN, LIKE |

 5. ORDER BY

| Syntax | Description |
|--------|------------|
| ORDER BY column ASC | Ascending |
| ORDER BY column DESC | Descending |

---
6. Aggregate Functions

| Function | Purpose |
|----------|--------|
| COUNT() | Counts rows |
| SUM() | Adds values |
| AVG() | Average |
| MIN() | Minimum |
| MAX() | Maximum |

 7. GROUP BY

| Syntax | Purpose |
|--------|--------|
| GROUP BY column | Groups data |

### Example
SELECT grade, COUNT(*)  
FROM students  
GROUP BY grade;

 8. HAVING

| Syntax | Purpose |
|--------|--------|
| HAVING condition | Filters grouped data |

### Example
SELECT grade, COUNT(*)  
FROM students  
GROUP BY grade  
HAVING COUNT(*) > 5;

9. Difference: WHERE vs HAVING

| Feature | WHERE | HAVING |
|--------|------|--------|
| Filters | Before grouping | After grouping |
| Works on | Rows | Groups |

 10. Common Mistakes

- Using WHERE with aggregate functions  
- Forgetting GROUP BY  
- Wrong conditions  

 11. Best Practices

- Use clear column names  
- Filter early using WHERE  
- Use GROUP BY properly  

Interview Questions

- Difference between WHERE and HAVING?  
- What are aggregate functions?  
- What does GROUP BY do?  

 Key Takeaways

- SQL is used to query data  
- WHERE filters rows  
- GROUP BY + aggregates summarize data  
