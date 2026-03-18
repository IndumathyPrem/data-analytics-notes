Excel for Data Analysis ( Notes)

Overview

| Topic        | Description |
|-------------|------------|
| Tool        | Microsoft Excel |
| Purpose     | Data cleaning, analysis, visualization |
| Use Cases   | Reporting, dashboards, preprocessing |

2. Core Formulas

| Function | Syntax | Purpose |
|----------|--------|--------|
| SUM | =SUM(A1:A10) | Adds values |
| AVERAGE | =AVERAGE(A1:A10) | Calculates mean |
| COUNT | =COUNT(A1:A10) | Counts numeric values |
| COUNTA | =COUNTA(A1:A10) | Counts non-empty cells |
| IF | =IF(A1>50,"Pass","Fail") | Conditional logic |


3. Text Functions

| Function | Syntax | Use Case |
|----------|--------|----------|
| TRIM | =TRIM(A1) | Removes extra spaces |
| CLEAN | =CLEAN(A1) | Removes non-printable characters |
| CONCAT | =CONCAT(A1," ",B1) | Combines text |
| LEFT | =LEFT(A1,4) | Extracts from left |
| RIGHT | =RIGHT(A1,4) | Extracts from right |
| MID | =MID(A1,1,4) | Extracts from middle |

 4. Lookup Functions

| Function | Syntax | Notes |
|----------|--------|------|
| HLOOKUP | =HLOOKUP(lookup_value, table_array, row_index, FALSE) |Horizontal Lookup, Rarely used|
| VLOOKUP | =VLOOKUP(A2,A1:C10,2,FALSE) | Vertical lookup , Rarely used|
| XLOOKUP | =XLOOKUP(A2,A1:A10,B1:B10) | More flexible, modern , Prefered|
| INDEX + MATCH | =INDEX(return_range, MATCH(value, lookup_range, 0))| Complex / large data , Prefered|

 5. Data Cleaning Tasks

| Task | Method |
|------|--------|
| Remove duplicates | Data → Remove Duplicates |
| Handle missing values | Replace / Filter |
| Standardize text | TRIM, LOWER, UPPER |
| Fix data types | Format cells |
| Detect errors | Filters |

 6. Sorting & Filtering

| Feature | Description |
|--------|------------|
| Sorting | Arrange data (A–Z / Z–A) |
| Filtering | Display specific rows |

 7. Pivot Tables

| Step | Action |
|------|-------|
| 1 | Select dataset |
| 2 | Insert → Pivot Table |
| 3 | Drag fields (Rows, Columns, Values) |

Used for summarizing large datasets quickly

 8. Conditional Formatting

| Use Case | Example |
|----------|--------|
| Highlight high values | Top 10 |
| Detect duplicates | Duplicate values rule |
| Visual patterns | Color scales |

 9. Data Validation

| Feature | Purpose |
|--------|--------|
| Drop-down list | Restrict inputs |
| Number limits | Prevent invalid values |
| Date restriction | Control date input |

10. Charts

| Chart Type | Use Case |
|-----------|----------|
| Bar Chart | Comparison |
| Line Chart | Trends over time |
| Pie Chart | Proportions |

11. Common Mistakes

- Hidden spaces in text  
- Incorrect formula ranges  
- Wrong data types  
- Overwriting formulas  

12. Best Practices

- Keep data in tabular format  
- Use clear column headers  
- Avoid merged cells  
- Maintain consistent formatting  
- Validate data before analysis  

Interview Questions

- What is the difference between VLOOKUP and XLOOKUP?  
- How do you remove duplicates in Excel?  
- What is a Pivot Table?  
- What is data validation?  

 Key Takeaways

- Excel is essential for data cleaning and analysis  
- Functions and Pivot Tables simplify complex tasks  
- Clean and structured data improves accuracy  
