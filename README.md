# Zepto_Python_Project
Zepto Sales Data Analysis & Dashboard
Zepto Sales Data Analysis Project
📌 Project Overview

This project focuses on analyzing real-world sales data from Zepto, a leading quick-commerce platform. 
The dataset contains over 200,000+ sales records along with product catalog information.

The objective of this project is to:

Clean and preprocess raw sales data

Perform exploratory data analysis (EDA)

Extract meaningful business insights

Visualize trends using professional charts

This project simulates an industry-level data analysis workflow using Python.

📂 Dataset Information

This project uses two CSV files:

1️⃣ zepto_sales.csv

Contains transaction-level data.

Columns:

order_id – Unique order identifier

order_date – Date & time of order

product_id – Product identifier

quantity – Units sold

city – Order location

delivery_status – Delivered / Cancelled / Returned

customer_id – Unique customer ID

delivery_time_mins – Delivery duration

total_amount – Total transaction amount

2️⃣ zepto_products.csv

Contains product-level details.

Columns:

product_id – Unique product ID

product_name – Product name

category – Product category

base_price – Base product price

Technical Stack

Language: Python 
Data Manipulation: Pandas 
Visualization: Matplotlib, Seaborn

📊 Data Visualizations

Created multiple professional visualizations:
<img width="1847" height="986" alt="image" src="https://github.com/user-attachments/assets/f2051faa-6ffd-4e66-9e82-818759e79ce0" />
Project Workflow
Step 1: Data Loading & Exploration
Load the CSV files into DataFrames and perform an initial inspection using .info(), .describe(), and .head() to understand the data structure and identifying initial patterns.

Step 2: Data Cleaning
To ensure data quality, the following cleaning steps are implemented:

Handling Missing Values:

Remove records with NaN values in city and delivery_status.

Fill missing values in delivery_time_mins with the column mean.


Removing Duplicates: Identify and remove any duplicate sales records.


Data Formatting: Convert order_date into proper datetime objects for time-series analysis.

Step 3: Data Analysis & Aggregation
Extract key performance indicators (KPIs) through grouping and aggregation:

Calculate minimum, maximum, and average transaction amounts.
Identify the Top 5 Products by total sales revenue.
Calculate total sales and average delivery times by City.
Analyze Monthly Sales Trends and sales distribution by Category.

Step 4: Data Visualization
Generate professional charts to communicate findings effectively:
Bar Charts: Top products and sales by city.
Line Graphs: Monthly sales trends.
Pie Charts: Sales distribution by product category.
Histograms: Distribution of delivery times to analyze logistics efficiency.
Conclusion
Completion of this project demonstrates a foundational capability in interpreting raw data to answer critical business questions. These insights can help Zepto optimize inventory, improve delivery times, and target high-performing regions
👨‍💻 Author
Avnish
Zepto Sales Data Analysis Project
Python | Pandas | Data Visualization
