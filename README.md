Zepto Data Analysis Project :-

This project focuses on analyzing Zepto product data using MySQL. The dataset contains product-related information such as category, pricing, discounts, and inventory. The main objective is to clean the data, explore patterns, and generate meaningful business insights.

Initially, the dataset existed as a single table, which was later conceptually structured into entities like Category, Product, and Inventory to improve organization and reduce redundancy.

Relationships
* One category → Many products
* One product → One inventory

Data Cleaning
* Removed products with invalid price (MRP = 0)
* Converted price from paise to rupees
* Checked and handled null values

 Data Exploration
* Counted total products
* Identified unique categories
* Detected duplicate product names

Key Insights
* Certain categories generate higher revenue
* Some high-value products are out of stock
* Bulk products provide better value per gram
* Discount patterns vary across categories

 Learning Outcomes
* Strong SQL fundamentals
* Data cleaning techniques
* Use of aggregate functions
* Writing subqueries
* Basic database design (ER concepts)

Conclusion
This project demonstrates how raw data can be transformed into meaningful insights using SQL. It highlights skills in data cleaning, analysis, and understanding business patterns like pricing, discounts, and inventory.

----------------------------------------------------------------------------------------------------------------------------------------------------
Bookstore Database Management System:-

The Bookstore Database Management System is a relational database project built using MySQL to efficiently manage bookstore operations such as books, customers, and orders. It demonstrates core database concepts including normalization, relationships, and structured query design.

 A relational database project built using MySQL
* Designed to manage bookstore operations such as books, customers, and orders
* Demonstrates core concepts like normalization and relationships

 Database Structure
* Authors
* Genres
* Books
* Customers
* Orders
* Order_Details

Relationships
* One Author to Many Books (1:M)
* One Genre to Many Books (1:M)
* One Customer to Many Orders (1:M)
* One Order to Many Order_Details (1:M)
* One Book to Many Order_Details (1:M)
* Many-to-Many relationship between Orders and Books implemented using Order_Details

Features
* Structured and normalized database design
* Use of primary keys and foreign keys
* Supports real-world operations such as inventory and order management
* Enables revenue calculation and customer tracking

Learning Outcome
* Understand how real-world systems are modeled using databases
* Practice writing SQL queries
* Learn normalization and schema design

 Conclusion
* A beginner-friendly project that builds a strong foundation in database management
* Useful for academic work, interviews, and practical understanding of SQL
