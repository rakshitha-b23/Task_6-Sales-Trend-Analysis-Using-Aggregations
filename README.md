## 📄 Online Sales Data: SQL Project

### 📁 Project: Data Exploration & Analysis – Online Sales Data  
### 🧰 Tools Used: MySQL, Excel  

---

## 📝 Overview

This project involved cleaning, querying, and analyzing an `online_sales_data` dataset using MySQL. The objective was to extract insights such as revenue trends, transaction volume, category performance, and time-based sales breakdowns.

---

### ✅ Tasks and Steps Performed

- Converted Excel to CSV format to resolve encoding errors during import.  
- Increased column size for `Product_Name` to fix data truncation error.  
- Used correct date format (`YYYY-MM-DD`) to resolve date value errors.  
- Created SQL table and loaded sales data successfully.  
- Used `EXTRACT(MONTH FROM Date)` and `EXTRACT(YEAR FROM Date)` for month/year extraction.  
- Used `GROUP BY` year/month to analyze time-based trends.  
- Used `SUM(Total_Revenue)` to calculate monthly and category-wise revenue.  
- Used `COUNT(DISTINCT Transaction_ID)` to calculate sales volume.  
- Filtered records using `BETWEEN` for specific date ranges.  
- Used `ORDER BY` to sort revenue in descending order.  
- Applied `DISTINCT` to extract unique month values.  
- Grouped by `Product_Category` to analyze category performance.  
- Ensured clean output by fixing syntax errors and refining queries.

---

## 🔚 Conclusion

This project demonstrates data handling, transformation, and business insight generation using SQL. These tasks helped in understanding sales behavior across months and categories and laid a foundation for deeper business intelligence reporting.

---
