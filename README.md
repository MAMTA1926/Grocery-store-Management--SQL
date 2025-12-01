 Grocery-store-Management--SQL


 **1. Project Title / Headline**

A structured SQL-based Grocery Management System designed to manage products, orders, suppliers, employees, and sales efficiently using a relational database.


 **2. Short Description / Purpose**

The system stores and manages grocery store data in a clean, relational database. Using SQL queries, the project analyzes sales trends, supplier performance, employee activity, product demand, and inventory movement. It helps understand store operations through data-driven insights.


 **3. Tech Stack**

🗄 **MySQL / MySQL Workbench** – Database creation, management, and SQL queries
📌 **SQL (DDL + DML)** – Tables, relationships, joins, aggregation, filtering
📊 **Analytical Queries** – Revenue, top products, employee performance
📁 **Dataset** – Grocery store data (Products, Orders, OrderDetails, Suppliers, Employees)

---

 **4. Database Structure / Schema Overview**

The **GroceryDB** database contains multiple interconnected tables:

* **Products** – Product details, category, price, supplier ID
* **Suppliers** – Supplier information and relationships to products
* **Orders** – Customer orders processed by employees
* **OrderDetails** – Quantity, unit price, and total order value
* **Employees** – Staff members handling orders
* **Customers** – Customer information (if included)

All tables reference each other through primary and foreign keys, ensuring accurate relationships between products, suppliers, orders, and employees.



 **5. Features / Highlights**

 📌 **Business Problem**

Grocery stores handle large amounts of product and sales data. Without SQL analysis, questions like:

* Which products sell the most?
* Which supplier provides the most items?
* What are the busiest order dates?
* Which employees process the highest sales?

are difficult to answer.



 📌 **Goal of the Project**

To use SQL to:

* Analyze order patterns and sales performance
* Identify top-selling and slow-moving products
* Evaluate supplier contribution & reliability
* Track employee performance
* Understand customer ordering behavior
* Support inventory and sales decision-making



📌 **Key SQL Analyses Performed**

1️⃣ **Order Trends**

* Most ordered dates
* Monthly sales volume
* Weekday vs weekend patterns

2️⃣ **Supplier Analysis**

* Total suppliers
* Supplier providing most products
* Supplier-wise revenue contribution

3️⃣ **Product Performance**

* Best-selling products
* Average quantity ordered
* Price variation across orders

4️⃣ **Employee Performance**

* Employees who processed the most orders
* Total sales handled by each employee
* Average order value per employee

5️⃣ **Overall Sales Insights**

* Total revenue
* High-demand categories
* Customer order size patterns



📌 **Business Impact & Insights**

* **Improved Inventory Management:** Identifies fast-moving and low-demand products.
* **Supplier Optimization:** Helps choose high-contributing suppliers.
* **Employee Performance Tracking:** Shows productivity through sales and orders.
* **Better Sales Planning:** Highlights peak order days and busy months.
* **Data-Driven Decisions:** Clear insights for purchasing, stocking, and staffing.
