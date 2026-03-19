# Grocery Store Sales — SQL Data Cleaning & Analysis

This project analyzes product data for **FoodYum**, a U.S.-based grocery chain.  
The goal is to clean the product dataset, fix missing values, and generate insights about pricing and product performance.

This project was completed as part of a **DataCamp Practical Exam**.

---

## 🔍 Business Problem

FoodYum wants to ensure that all product categories have a full range of prices to serve customers with different budgets.  
However, the product database contained:

- Missing values  
- Incorrect formatting  
- Inconsistent categories  
- Missing `year_added` values due to a system bug  

Your task was to clean the data and answer key business questions using SQL.

---

## 🛠️ Skills Used

- SQL Data Cleaning  
- COALESCE, NULLIF, CASE  
- Regular Expressions (REGEXP_REPLACE)  
- Aggregations (MIN, MAX)  
- GROUP BY  
- Data validation  
- Handling missing values  
- Median imputation  

---

## 📂 Project Tasks

### **Task 1 — Count Missing `year_added` Values**
Identify how many products were missing the year they were added.

### **Task 2 — Clean the Product Dataset**
Applied cleaning rules:

- Missing product_type → `"Unknown"`  
- Missing brand → `"Unknown"`  
- Missing weight → median weight  
- Missing price → median price  
- Missing average_units_sold → `0`  
- Missing year_added → `2022`  
- Missing stock_location → `"Unknown"`  

### **Task 3 — Price Range by Product Type**
Returned the minimum and maximum price for each product category.

### **Task 4 — Filter Meat & Dairy Products**
Returned products where:

- product_type IN ('Meat', 'Dairy')  
- average_units_sold > 10  

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `grocery_store_sales.pdf` | Original DataCamp practical exam submission |
| `sql/task1_missing_year.sql` | SQL for Task 1 |
| `sql/task2_clean_data.sql` | SQL for Task 2 |
| `sql/task3_min_max_price.sql` | SQL for Task 3 |
| `sql/task4_meat_dairy_units.sql` | SQL for Task 4 |

---

## 🧠 Key Insights

- The dataset required extensive cleaning before analysis.  
- Several product categories showed wide price ranges, useful for pricing strategy.  
- Meat and dairy products with high unit sales can be targeted for promotions.  

---

## 👤 Author

**Bala Akhil Rajdeep Battula**  
Data & Technology Professional → Automotive Technology (WDTC Fall 2026)
