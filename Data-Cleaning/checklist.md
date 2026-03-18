# 🧹 Data Cleaning Checklist

A comprehensive checklist to ensure data quality, consistency, and reliability before analysis.
## 1. Understand the Data
- Identify:
  - Column meanings
  - Data types (text, numeric, date)
  - Expected value ranges
- Clarify business context before cleaning

## 2. Remove Duplicate Records
- Check for repeated rows or entries
- Ensure unique identifiers (primary keys)
- Tools:
  - Excel → Remove Duplicates
  - SQL → DISTINCT

---

## 3. Handle Missing Values
- Detect null, blank, or undefined values
- Choose an approach:
  - Remove records
  - Impute values (mean, median, mode)
  - Replace with placeholders ("Unknown")

👉 Decision depends on data importance and context

## 4. Standardize Text Data
- Remove leading/trailing spaces (TRIM)
- Convert consistent case (UPPER / LOWER)
- Fix inconsistent labels
- Example: "yes", "Yes", "Y" → standardized value
  
## 5. Fix Data Types
- Ensure correct formats:
  - Dates → Date format
  - Numbers → Numeric
  - Categories → Text
- Avoid storing numbers as text

---

## 6. Remove Invalid & Inconsistent Values
- Identify logically incorrect values
- Examples:
  - Negative values where not applicable
  - Impossible dates
- Validate against expected rules

## 7. Handle Outliers
- Detect extreme or unusual values
- Methods:
  - Statistical (IQR, Z-score)
  - Visual (box plots)
- Actions:
  - Remove
  - Cap values
  - Investigate source

## 8. Normalize & Structure Data
- Break complex fields into atomic values
- Avoid multi-value columns
- Ensure proper tabular structure

---

## 9. Rename Columns Clearly
- Use consistent naming conventions:
  - lowercase_with_underscores
- Avoid spaces and special characters

## 10. Check Data Consistency
- Ensure relationships between fields are valid
- Cross-verify related columns
- Maintain uniform formats across dataset

## 11. Remove Unnecessary Data
- Drop irrelevant or redundant columns
- Focus only on data required for analysis

## 12. Validate Data Integrity
- Check:
  - No duplicate IDs
  - No missing key fields
- Ensure referential integrity (if multiple tables)

---

## 13. Create Derived Fields (if required)
- Generate useful metrics:
  - Totals
  - Averages
  - Ratios
- Helps in better analysis

## 14. Document Cleaning Steps
- Record all transformations performed
- Maintain transparency and reproducibility

## 15. Final Data Quality Check
- Verify:
  - Accuracy
  - Completeness
  - Consistency
- Ensure data is ready for analysis or modeling


## 🎯 Interview Questions
Q: What are the main steps in data cleaning?  
Q: How do you handle missing values?  
Q: What are outliers and how do you treat them?  
Q: Why is data standardization important?  
Q: What is data integrity?


## ✅ Key Takeaways
- Data cleaning is a critical step before analysis  
- Clean data improves accuracy and decision-making  
- Consistency and validation are essential  
