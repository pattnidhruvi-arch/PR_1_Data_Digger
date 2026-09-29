# 🛒 PR_1_Data_Digger - E-Commerce Database Management Project

**Student Name:** Pattani Dhruvi  
**Semester:** 5th  
**Subject:** Database Management System (DBMS) - Lab Work 1  
**Date:** 29th September 2026  
**GitHub Repo:** PR_1_Data_Digger

---

### 🎯 1. PROJECT AIM
The aim of this project is to create an E-Commerce database system to manage Customers and Products data efficiently using SQL. We learn how to create tables, insert records, view data and sort data as per business needs.

### 🛠️ 2. TOOLS & TECHNOLOGY USED
- **Database:** MySQL Workbench / SQL
- **Documentation:** Microsoft Word
- **Version Control:** GitHub
- **Laptop:** HP Laptop (as per project file)

### 🗄️ 3. DATABASE DESIGN & IMPLEMENTATION

#### A) Customers Table Creation
This table stores customer information.
```sql
CREATE TABLE Customers (
    CustomerID INT PRIMARY KEY,
    CustomerName VARCHAR(100),
    City VARCHAR(50)
);
B) Data Insertion
Inserted first customer record.sqlINSERT INTO Customers VALUES (1, 'Dhruvi', 'Ahmedabad');
-- Result: 1 row affectedC) View DatasqlSELECT * FROM Customers;
-- Shows: CustomerID | CustomerName | City
--        1          | Dhruvi       | AhmedabadD) Products Table & ORDER BY
To find low-stock products first, we use ORDER BY.sqlSELECT * FROM products ORDER BY Stock ASC;
-- Result shows: PR-6 Headphone (Stock: 5) on top
-- This helps in E-Commerce to restock items quickly.
📸 4. SCREENSHOTS ATTACHED IN DOCX
Successful insertion proofCustomers table full viewProducts table sorted by Stock ASCAll screenshots are available in PROJECT 1-LAPTOP-4VG9OL4G.docx
📂 5. FILES IN THIS REPOSITORY
PROJECT 1-LAPTOP-4VG9OL4G.docx - Complete Project Report with queries and output screenshotsREADME.md - This detailed project summary✅ 
6. CONCLUSION
In this project, we successfully executed all SQL queries. We learned practical implementation of CREATE TABLE, INSERT, SELECT and ORDER BY. This project is very useful for real-world E-Commerce websites like Amazon and Flipkart to manage inventory.
🙏 7. ACKNOWLEDGEMENT
Thank you to our DBMS faculty for guiding us.
