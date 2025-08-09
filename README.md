Inventory Management System – Python & MySQL (GUI)
📌 Overview
A GUI-based Inventory Management System built using Python (Tkinter) and MySQL.
This system allows businesses to efficiently manage products, customers, suppliers, sales, and purchases while tracking stock levels and generating reports.
The project is designed with error handling, data validation, and a user-friendly interface to ensure smooth operation.

✨ Features
Product Management – Add, edit, and delete products with details like name, ID, description, unit price, and quantity.

Customer & Supplier Management – Maintain customer and supplier records for transactions.

Inventory Tracking – Monitor stock levels and identify low-stock items.

Sales & Purchase Transactions – Record and manage both sales and purchase details.

Reporting – Generate reports for inventory status, sales trends, and reorder points.

Data Validation & Error Handling – Prevents invalid data entries and ensures system reliability.

User-Friendly GUI – Built with Tkinter for easy navigation (non-CLI based).

🛠️ Tech Stack
Programming Language: Python 3

GUI Library: Tkinter

Database: MySQL

Connector: mysql-connector-python

📂 Database Structure
Tables:

items – Product details (name, description, price, quantity)

customers – Customer details

suppliers – Supplier details

sales – Sales transaction records

sale_details – Details of each sale

purchases – Purchase transaction records

purchase_details – Details of each purchase

🚀 Installation & Setup
Clone the Repository

bash
Copy
Edit
git clone https://github.com/your-username/Inventory-Management-System-Python-MySQL-GUI.git
cd Inventory-Management-System-Python-MySQL-GUI
Install Dependencies

bash
Copy
Edit
pip install mysql-connector-python
Set Up MySQL Database

Open MySQL and create the database:

sql
Copy
Edit
CREATE DATABASE inventory;
Import the provided .sql file (if available) to create tables.

Update Database Connection in Code
Inside the Python script, update:

python
Copy
Edit
host="localhost"
user="root"
password="your_password"
database="inventory"
Run the Application

bash
Copy
Edit
python main.py
📊 Future Improvements
Add authentication and user roles.

Export reports to Excel/PDF.

Implement barcode scanning.

Enable cloud database integration.

📜 License
This project is licensed under the MIT License – feel free to use and modify it.
