
# Walmart Sales Data Analysis

## About

This project aims to explore Walmart sales data to understand top-performing branches and products, sales trends, and customer behaviour. The objective is to study how sales strategies can be improved and optimized. The dataset was obtained from the Kaggle Walmart Sales Forecasting Competition.

> "In this recruiting competition, job-seekers are provided with historical sales data for 45 Walmart stores located in different regions. Each store contains many departments, and participants must project the sales for each department in each store. To add to the challenge, selected holiday markdown events are included in the dataset. These markdowns are known to affect sales, but it is challenging to predict which departments are affected and the extent of the impact."

## Purpose of the Project

The major aim of this project is to gain insights into Walmart’s sales data to understand the various factors affecting the sales of different branches.

## About the Data

The dataset was obtained from the Kaggle Walmart Sales Forecasting Competition and includes sales transactions from three branches of Walmart located in Mandalay, Yangon, and Naypyitaw. The dataset contains 17 columns and 1,000 rows.

### Column Descriptions

- **invoice_id:** Invoice of the sales made (VARCHAR(30))
- **branch:** Branch where sales were made (VARCHAR(5))
- **city:** Location of the branch (VARCHAR(30))
- **customer_type:** Type of customer (VARCHAR(30))
- **gender:** Gender of the customer (VARCHAR(10))
- **product_line:** Product line of the product sold (VARCHAR(100))
- **unit_price:** Price of each product (DECIMAL(10, 2))
- **quantity:** Amount of the product sold (INT)
- **VAT:** Amount of tax on the purchase (FLOAT(6, 4))
- **total:** Total cost of the purchase (DECIMAL(10, 2))
- **date:** Date of the purchase (DATE)
- **time:** Time of the purchase (TIMESTAMP)
- **payment_method:** Payment method used (VARCHAR(30))
- **cogs:** Cost Of Goods Sold (DECIMAL(10, 2))
- **gross_margin_percentage:** Gross margin percentage (FLOAT(11, 9))
- **gross_income:** Gross Income (DECIMAL(10, 2))
- **rating:** Rating (FLOAT(2, 1))

## Analysis List

### Product Analysis

- Conduct analysis to understand the performance of different product lines.
- Identify the best-performing product lines and those needing improvement.

### Sales Analysis

- Analyze sales trends across different products.
- Measure the effectiveness of sales strategies and suggest modifications for increased sales.

### Customer Analysis

- Uncover different customer segments and their purchase trends.
- Assess the profitability of each customer segment.

## Approach Used

### Data Wrangling

- Inspect data for NULL or missing values.
- Apply data replacement methods to handle missing or NULL values.

### Build a Database

- Create tables and insert data.
- Ensure no NULL values in the database by setting NOT NULL constraints for each field.

### Feature Engineering

- Add new columns to enhance the dataset:
  - **time_of_day:** Categorize sales into Morning, Afternoon, and Evening.
  - **day_name:** Extract day of the week (Mon, Tue, Wed, Thu, Fri).
  - **month_name:** Extract month of the year (Jan, Feb, Mar).

### Exploratory Data Analysis (EDA)

- Perform EDA to answer project questions and achieve project aims.
