# SQL_Data_Analyst_Associate_Practical_Exam
FoodYum is a prominent grocery store chain in the United States, offering a wide range of products including produce, meat, dairy, baked goods, snacks, and other household food staples. This README provides information and SQL queries to perform data analysis on the FoodYum product data

# Table of Contents

# Identifying Missing year_added Values
To determine how many products have missing year_added values, I used the following query:
```
SELECT COUNT(*) AS missing_year
FROM products
WHERE year_added IS NULL;
```
This query outputs a single column, missing_year, indicating the number of products with missing year_added values.

# Ensuring Data Accuracy
