Fruit Shop Inventory Management

This project is a basic inventory management system for a fruit shop, implemented using a SQLite database. The database tracks various aspects of the shop’s inventory, including fruits, suppliers, stock, customers, and transactions.

Project Structure

	•	notebooks/sql.ipynb: A Jupyter Notebook containing code for creating and managing the SQLite database, including inserting and querying data.
	•	fruit_shop_db.sqlite: The SQLite database file where all data is stored.

Features

	•	Fruits Table: Stores information about different fruits, including name, description, and price per unit.
	•	Suppliers Table: Stores information about suppliers who provide fruits.
	•	Stock Table: Tracks the inventory levels of fruits, including the source (supplier) and quantity.
	•	Customers Table: Stores customer information for tracking transactions.
	•	Transactions Table: Logs sales transactions, including customer details, fruit purchased, quantity, and total price.

Installation and Setup

1. Clone the Repository

First, clone the repository to your local machine:

git clone https://github.com/yourusername/fruit-shop-inventory.git
cd fruit-shop-inventory


2. Set Up the Python Environment

Ensure you have Python installed (preferably version 3.10 or higher). Install the required Python packages using pip:

pip install pandas ipython-sql sqlite3


3. Run the Jupyter Notebook

Launch Jupyter Notebook and open notebooks/sql.ipynb:

jupyter notebook notebooks/sql.ipynb



4. Execute the Notebook Cells

Follow the instructions within the Jupyter Notebook to create the database, insert data, and run queries.

5. Install and Use a SQL Viewer

For better visualization and management of your SQLite database, you can install DB Browser for SQLite.

Windows:

Download and install DB Browser for SQLite.

macOS:

You can install it via Homebrew:

brew install --cask db-browser-for-sqlite


Linux:

Most Linux distributions have DB Browser for SQLite available in their package manager. For example, on Ubuntu:


sudo apt-get install sqlitebrowser



Using the SQL Viewer

	1.	Open DB Browser for SQLite.
	2.	Open the fruit_shop_db.sqlite file located in the project directory.
	3.	You can now browse the database, execute SQL queries, and manage your data visually.

How to Use

Example Queries

You can use the Jupyter Notebook to run example SQL queries and explore the database. Here are a few examples:

	•	View All Fruits:

SELECT * FROM fruits;

SELECT * FROM transactions;


SELECT * FROM stock;





Adding More Data

You can add more dummy data directly in the Jupyter Notebook or using DB Browser for SQLite. Follow the patterns shown in the notebook to insert additional records.
