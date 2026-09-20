📚 Online Bookstore SQL Analysis
📌 Project Overview

This project analyzes an Online Bookstore database using SQL to explore books, customers, orders, sales revenue, inventory, and customer purchasing behavior.

The project demonstrates practical SQL skills by answering a series of business-oriented questions, progressing from basic data retrieval to more advanced analysis using joins, aggregation, filtering, grouping, subqueries, and conditional analysis.

🎯 Project Objectives

The main objective of this project is to use SQL to analyze an online bookstore's operational and sales data and extract useful business insights.

The analysis focuses on:

📚 Book inventory and pricing
👥 Customer information and purchasing behavior
🛒 Order activity
💰 Revenue analysis
📊 Genre and author performance
📦 Inventory remaining after orders
🏆 Top-performing books and customers
🛠️ Tools & Technologies
SQL
PostgreSQL / SQL
Relational Database Concepts
JOINs
Aggregate Functions
GROUP BY & HAVING
ORDER BY
Subqueries
Filtering & Sorting
COALESCE
LIMIT

🗂️ Database Structure

The project contains three main tables:

📚 Books

Contains information about books available in the bookstore.

Column	Description
Book_ID	Unique book identifier
Title	Book title
Author	Book author
Genre	Book genre
Published_Year	Publication year
Price	Book price
Stock	Available inventory

👥 Customers

Contains customer information.

Column	Description
Customer_ID	Unique customer identifier
Name	Customer name
Email	Customer email
Phone	Customer phone
City	Customer city
Country	Customer country
🛒 Orders

Contains customer order information.

Column	Description
Order_ID	Unique order identifier
Customer_ID	Customer reference
Book_ID	Book reference
Order_Date	Date of order
Quantity	Number of books ordered
Total_Amount	Total order amount

🔄 Analysis Process
1. Database Creation

Created the OnlineBookstore database and designed tables for:

Books
Customers
Orders

Relationships were established between customers, books, and orders using primary and foreign keys.

2. Data Exploration

Performed initial exploration of the database using queries such as:

Retrieving all books
Retrieving all customers
Retrieving all orders
Identifying available genres

3. Basic SQL Analysis

The project answers several business questions, including:

Finding books in the Fiction genre
Finding books published after 1950
Identifying customers from Canada
Retrieving orders placed during November 2023
Finding expensive books
Identifying books with the lowest stock
Finding orders above a specific amount
Calculating total revenue
4. Advanced SQL Analysis

Advanced analysis was performed using:

JOIN
GROUP BY
HAVING
SUM()
AVG()
COUNT()
COALESCE()
ORDER BY
LIMIT

The analysis includes:

Books sold by genre
Average Fantasy book price
Customers with at least two orders
Most frequently ordered book
Top three most expensive Fantasy books
Books sold by author
Cities of customers with higher-value orders
Highest-spending customer
Remaining book inventory after fulfilling orders

📊 Key Business Questions

The project answers questions such as:

Sales & Revenue
What is the total revenue generated from orders?
Which customers spend the most?
Which orders have a value greater than $20?
Which cities have customers with orders above $30?
Product Analysis
Which genre sells the most books?
Which book is ordered most frequently?
Which are the most expensive Fantasy books?
Which book has the lowest stock?
Customer Analysis
Which customers have placed at least two orders?
Which customer has spent the most?
Where are high-value customers located?
Inventory Analysis
How much stock is available?
How many books have been ordered?
What quantity remains after fulfilling orders?

💡 SQL Skills Demonstrated

This project demonstrates practical knowledge of:

SELECT
WHERE
DISTINCT
ORDER BY
LIMIT
BETWEEN
COUNT()
SUM()
AVG()
GROUP BY
HAVING
INNER JOIN
LEFT JOIN
COALESCE()
PRIMARY KEY
FOREIGN KEY
Aggregate Functions
Relational Database Design

📈 Business Value

The analysis demonstrates how SQL can be used to convert transactional bookstore data into business insights.

The queries can help a bookstore understand:

Customer purchasing behavior
Revenue performance
Product demand
Genre performance
Author-level sales
Inventory requirements
High-value customers
Frequently ordered books

These insights can support decisions related to inventory management, customer analysis, product planning, and sales performance monitoring.

📁 Project Files
Online-Bookstore-SQL-Analysis/
│
├── Onlinebookstore_Project.sql
│
└── README.md
👨‍💻 Author

Ravi Singh

Aspiring Data Analyst | SQL | Power BI | Excel | Python

Skills Demonstrated

SQL PostgreSQL Data Analysis Joins Aggregation GROUP BY HAVING Database Design Business Analysis

⭐ Project Highlights

End-to-End SQL Data Analysis Project

Database Creation → Data Exploration → SQL Analysis → Business Insights

This project demonstrates the practical application of SQL to analyze an online bookstore's books, customers, orders, revenue, and inventory data.
