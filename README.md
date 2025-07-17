# Blinkit-Dataset-Analysis
Prepared detailed analysis and visualization in PowerBI
🛒 Blinkit Sales Dashboard - Power BI Project
This project involves building an interactive Power BI dashboard based on sales data from Blinkit and other online retail channels like Myntra, Amazon, Flipkart, etc. The goal is to analyze customer demographics, sales performance, order channels, and product-level insights.

📊 Dataset Overview
The dataset was provided in an Excel file and contains transaction-level data with the following fields:

Order Details: Order ID, Customer ID, Date, Month, Channel, Status
Customer Info: Gender, Age, Age Group, City, State, Postal Code, Country
Product Info: SKU, Category, Size, Quantity, Amount, Currency
Business Info: Business Type (e.g., B2B)
Sample Columns:

Order ID | Cust ID | Gender | Age | Age Group | Date | Channel | Category | Qty | Amount | City | State
🛠️ Data Preparation in Power BI
Imported Excel data into Power BI

Performed data cleaning:

Converted Date column to proper datetime format
Created Age Group categories (Teenager, Adult, Senior)
Fixed inconsistent city/state names
Removed duplicates and nulls where necessary
Created a Calendar table to enable time-based analysis

🔢 Key DAX Measures Used
Some of the DAX measures used in this project include:

Total Sales 
Total Orders
Average Order Value
Sales by Gender 
Qty Sold 

📈 Power BI Dashboard
The dashboard is divided into multiple visual sections:

Sales Overview: Total sales, total orders, average order value
Customer Demographics: Gender-wise and age group-wise breakdown
Geographical Insights: Sales by city and state using map visuals
Channel Performance: Sales by platform (Amazon, Myntra, Meesho, etc.)
Category Performance: Top-performing product categories like Kurta, Set, etc.
🖼️ Dashboard Preview
Blinkit Dashboard Preview

🔍 Key Insights
Most customers are women adults, contributing the highest number of orders.
Kurta is the best-selling category across multiple platforms.
Myntra and Amazon are the top-performing sales channels.
Major sales come from cities like Gurugram, Bengaluru, and Kolkata.
The majority of transactions fall under B2B business type.
▶️ How to Run This Project
Clone this repository
Open Power BI Desktop
Load the provided Excel dataset
Apply data transformation steps (Power Query)
Create relationships and measures using DAX
Build visuals as shown in the dashboard preview
Customize as needed for further insights
📬 Contact
For queries or collaboration, feel free to reach out:

Aishwarya Burde 📧 Email: aishwaryaburde2000@gmail.com Linkdin: www.linkedin.com/in/aishwarya-burde
