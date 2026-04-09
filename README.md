# 📊 Retail Sales Analysis using MySQL

- Performing EDA to answer important ‘Business Questions’ using SQL Queries
- Domain: Retail (Sales)
- Tools used: MySQL Workbench

### ✅ Project Details:

This project demonstrates SQL skills (from beginner to intermediate) and data analytics techniques for exploring, cleaning, and analyzing a large dataset. The project involves setting up a retail sales database (Retail_db), performing EDA, and answering specific business questions through SQL queries.

### 🎯Objectives:

1. **Set up ‘Database’**: Create and populate a ‘Sales Database’ from the CSV dataset.
2. **Data Cleaning**: Identify and remove any records with missing or null values.
3. **Exploratory Data Analysis**: Perform basic exploratory data analysis to understand the dataset.
4. **Business Analysis**: Use SQL to answer specific business questions and derive insights.

### ✒️Project Architecture:

1. Database Setup:

- Database Creation: CREATE DATABASE retail_db;
- Table Creation: CREATE TABLE retail_sales
    
2. Data Exploration & Cleaning:
   
- Record Count: Determine the total number of records in the dataset.
- Customer Count: The number of unique customers in the dataset.
- Category Count: Identify all unique product categories in the dataset.
- Null Value Check: Check for null values and delete records with missing data.

3.	Data Analysis & Findings:
   
- Deleted empty records using SQL Queries
- Total unique customers recorded: '155'
- Total categories recorded: '3'

### 📈Analysing Key Business Questions (Using SQL queries): 

**(All SQL queries (with codes) are available in the ‘SQL Analysis Report PDF’ file listed above)**

Q1 Retrieve all columns for sales made on '2024-11-05': Record of 11 columns retrieved

Q2 Retrieve all transactions where category is 'Clothing' & qty sold is more than 3 in November 2024 and more than 2 & less than 4 in Aug 2025?

Q3 Product category that generated the highest total revenue: 'Electronics' recorded the highest revenue of 3,14,370/-

Q4 The average 'Age' of customers who purchased items from the 'Beauty' category: 'Average AGE' is 40

Q5 The monthly sales total for the years 2024 & 2025?

Q6 All transactions where the ‘Total sale’ is greater than 1000?

Q7 The top 6 customers by lifetime spend: To find high-value customers for loyalty programs

Q8 Total number of transactions made by each gender under each category:

-	Beauty: Female -- 331 | Male – 282
-	Clothing: Female – 347 | Male – 354
-	Electronics: Female – 341 | Male - 346
  
Q9 Average order value (AOV) and 'Average Qty' per transaction by category: It helps compare basket size and value across categories.

Q10 'Gross Margin' (GM) by category (revenue minus COGS): It revealed which categories are most profitable

Q11 The 'Average Sale' for each month & find out the best-selling month in each year: July 2024 and Feb 2025 have the highest average sales

Q12 'Days of week' which have the highest number of transactions: 'Tuesday' has the highest, with Friday being the lowest

Q13 The number of unique customers who purchased items from each category?

Q14 Create each shift & number of sales (Morning <=12, Afternoon Between 12 & 17, Evening >17): Using CTE Functions

Q15 The hour of day that drives most revenue & transactions: This insight helps schedule promotions and staffing for peak hours.

Q16 How does average spend differ by gender & age group? 

-	It supports targeted marketing and segmentation – using ‘CASE’ function
  
       ''' CASE
         WHEN age < 25 THEN 'Below 25'
         WHEN age BETWEEN 25 AND 34 THEN '25-34'
         WHEN age BETWEEN 35 AND 44 THEN '35-44'
         WHEN age BETWEEN 45 AND 54 THEN '45-54'
         WHEN age >= 55 THEN '55+'
       END AS age_group '''
 	
Q17 Which transactions show unusually low or negative margins?

### 💡Key Learnings:

1.	Understanding Business Problems & Exploratory Analysis
2.	Data Understanding and Collection
3.	Create, DROP, Select, CTE, Group By, CASE Functions
   
### ✒️Conclusion
This project serves as a comprehensive introduction to SQL for data analysts, covering database setup, data cleaning, exploratory data analysis, and business-driven SQL queries.

## Author & Contact:

👩‍💻 Author: Pragyan Saikia

📧 Email: [pragyan.saikia04@gmail.com]
