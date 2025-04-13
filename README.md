# bookstore-db
This project defines the schema for a relational database designed for managing a bookstore. It includes entities for books, authors, customers, orders, and shipping.

## 📁 Database Overview

The `bookstore` database is structured to handle:
- Book inventory and details
- Author information and book-author relationships
- Customers and their addresses
- Orders, order history, and order statuses
- Shipping methods
- Publishers and languages

## 🗂️ Database Tables

The following main tables are included in the schema:

| Table | Description |
| `book` | Stores book details like title, price, publisher, and language. |
| `author` | Stores author names. |
| `book_author` | Many-to-many link between books and authors. |
| `publisher` | Book publisher information. |
| `book_language` | Languages that books can be written in. |
| `customer` | Customer information including name and email. |
| `address` | Stores address data, linked to countries and status. |
| `customer_address` | Many-to-many link between customers and addresses. |
| `country` | Stores list of countries. |
| `address_status` | Tracks status of an address (e.g., active, inactive). |
| `cust_order` | Stores customer order details. |
| `order_line` | Items in each order (books and quantities). |
| `order_status` | Status of an order (e.g., pending, shipped). |
| `order_history` | Tracks status history of an order. |
| `shipping_method` | How orders are shipped (e.g., courier, pickup). |

## 🏗️ How to Use
1. Run the script to create and initialize all tables:
2. Add Sample Data (Optional): You can insert test data for development or testing.
3. Query the Database
4. Generate ERD Diagram: Use tools like MySQL Workbench to visually represent relationships.

✅ Requirements
A editor i.e(vscode)
A SQL client (e.g., MySQL Workbench,)

🧑‍💻 Contributors
Team Members: Joy Wucha, Victor, Cristopher
