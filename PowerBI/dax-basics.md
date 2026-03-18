#  DAX (Data Analysis Expressions)

# 1. Overview

| Topic | Description |
|------|------------|
| DAX | Formula language in Power BI |
| Purpose | Calculations & analysis |

# 2. Measures

| Example | Description |
|--------|------------|
| Total = SUM(Sales[Amount]) | Adds values |
| Avg = AVERAGE(Sales[Amount]) | Average |

👉 Dynamic (changes with filters)

# 3. Calculated Columns

| Example | Description |
|--------|------------|
| Category = IF(Sales[Amount]>100,"High","Low") | Row-level calculation |

👉 Static (stored in table)

# 4. Measure vs Column

| Feature | Measure | Column |
|--------|--------|--------|
| Type | Dynamic | Static |
| Usage | Visuals | Table |
| Calculation | Aggregated | Row-level |

# 5. Common Functions

| Function | Purpose |
|----------|--------|
| SUM() | Total |
| AVERAGE() | Mean |
| COUNT() | Count rows |
| IF() | Conditions |
| CALCULATE() | Modify filters |

# 6. CALCULATE (Important)

| Syntax | Description |
|--------|------------|
| CALCULATE(expression, filter) | Applies filter |

# 7. Common Mistakes

- Using column instead of measure  
- Wrong context understanding  
- Overusing calculated columns  

# Interview Questions

- Difference between Measure and Column?  
- What is CALCULATE?  
- What is DAX used for?  

# Key Takeaways

- DAX is used for calculations in Power BI  
- Measures are dynamic  
- CALCULATE is powerful  
