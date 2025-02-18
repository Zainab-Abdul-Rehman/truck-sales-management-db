# Truck-Sales-Management-db
The Truck Sales and Manufacturing System is a MySQL-based database project that manages truck sales, manufacturing processes, and inventory. It ensures efficient tracking of orders, invoices, production batches, and truck parts, providing a structured approach to managing truck manufacturing operations.

# **Features ✨**

✅ Customer Management – Stores customer details and contact information.  

✅ Order Processing – Tracks sales, invoices, and batch orders.  

✅ Manufacturing & Inventory – Manages truck production, parts, and stock.  

✅ Production Planning – Handles manufacturing stages and costs.  

✅ Data Relationships – Uses foreign keys to enforce referential integrity.  


# **Database Schema & Tables 📊**

The system consists of multiple interconnected tables, including:

**CUSTOMER** – Stores customer information.  

**INVOICE** – Manages sales transactions and deliveries.  

**BtORDER** – Tracks customer orders and expected delivery dates.  

**BATCH** – Handles production batches of trucks.  

**TRUCK**– Stores truck details (model, color, specifications).  

**MANUFACTURER** – Manages manufacturers and production capacities.  

**TRUCKPARTS** – Tracks truck components and their costs.  

**PRODPLAN** – Maintains production timelines and costs.

# **Installation & Setup 🚀**

**Step 1: Install MySQL**

Ensure you have MySQL Server installed.  
You can download it from:  

🔗 MySQL Official Website

**Step 2: Import the Database**    

   1.	Open MySQL Workbench or any SQL client.  
   2.	Copy and paste the SQL script (truck_sales_management.sql).
   3.	Run the script to create the database and tables.  

**Step 3: Verify Database Setup**

**Run:**  

USE AVI;  
SHOW TABLES;  
SELECT * FROM CUSTOMER;  
SELECT * FROM TRUCK;  

This will confirm successful installation.

# **SQL Queries & Reports 📝**

Some useful queries included in the project:
• View all customers:

	•	SELECT * FROM CUSTOMER;

Get sales reports by month:

	•	SELECT MONTH(ADDel) AS SaleMonth, SUM(SalePrice) AS TotalRevenue FROM Invoice GROUP BY SaleMonth;

List trucks available in inventory:

	•	SELECT Model, Color, Specs FROM TRUCK;

# **Contributing 🤝**

Contributions are welcome! Feel free to fork this repository, open an issue for suggestions or bugs or submit a pull request.

# **Connect with Me 🔗**
📧 Email: zainababdulrehman329@gmail.com




