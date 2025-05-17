# online_retail# 🛒 Online Retail Application – SQL Database

This project contains a PostgreSQL SQL script for creating a fully structured **Online Retail Application** database. It supports core business functions including customer registration, employee management, order tracking, payment processing, and product listings.

---

## 🛠️ Key Features

- Structured under a dedicated schema: `online_retail_app`
- Separate user and customer login systems
- Employee classification by internal/vendor roles
- Product and order tracking system with payment integration
- Delivery tracking and order fulfillment logic

---

## 📂 Schema Overview

This script builds the following tables:

| Table Name | Description |
|------------|-------------|
| `user_login` | General user login system for app users |
| `customers` | Customer registration and login data |
| `employment_type` | Types of employment (internal/vendor) |
| `employees` | Employee details with type and contact |
| `payment` | Payment processing and tracking |
| `orders` | Customer orders and delivery status |
| `product_items` | Product listings with price, discount, stock |
| `order_items` | Mapping of ordered products per order |
| `order_delivery` | Order delivery stages and tracking |

---

## 🧾 How to Use

1. Open a PostgreSQL client (e.g., pgAdmin or DBeaver).
2. Create a new database (e.g., `retail_app_db`).
3. Run the `online_retail_app.sql` script.
4. All tables and relationships will be created under the `online_retail_app` schema.

---

## 💡 Example Use Cases

- Power backend for an e-commerce dashboard
- Analyze sales, delivery, or product performance
- Track customer activity and order behavior
- Manage employees, vendors, and product inventory

---

## ⚙️ Technical Notes

- Uses `FOREIGN KEY` constraints for referential integrity
- JSON datatype is used for product images
- Handles both internal and third-party (vendor) employee types
- Includes timestamps for tracking activity and delivery stages

---

## 📁 File Structure

- `online_retail_app.sql` – SQL script to create all tables and relationships

---

## 👤 Author

Your Name  
_MBA Student | Aspiring Data Analyst | SQL Enthusiast_

---

