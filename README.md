# 🛍️ Flipkart E-commerce Database

An end-to-end relational database schema designed to simulate an e-commerce platform like Flipkart.

---

## 🛒 Domain: E-commerce

This project models the backend data structure for an online shopping platform, supporting users, products, cart systems, orders, and reviews.

---

## 🧱 Entities

The following core entities are included in the database schema:

- **Users**: Registered customers with personal and login details.
- **Products**: Items listed for sale.
- **Categories**: Product classification (e.g., electronics, fashion).
- **Orders**: Purchases made by users.
- **Order Items**: Specific products in each order.
- **Payments**: Payment records tied to orders.
- **Cart**: Temporary storage of items before purchase.
- **Reviews**: Feedback provided by users for products.

---

## 🔧 Tools Used

- **MySQL Workbench**: For schema design and implementation.
- **dbdiagram.io**: For creating the ER diagram.

---

## 📄 Deliverables

- `schema.sql` – SQL file containing all DDL queries to create the database schema.
- `ER_Diagram.png` – Entity-Relationship diagram showcasing the design.
- `README.md` – Project overview and documentation (this file).

---

## 📚 Concepts Covered

- **DDL**:
  - `CREATE TABLE`, `PRIMARY KEY`, `FOREIGN KEY`
- **Normalization**:
  - Ensures minimal redundancy and improved data integrity
- **Relationships**:
  - One-to-Many (1:N)
  - Many-to-Many (M:N)
- **Constraints**:
  - `NOT NULL`, `UNIQUE`, `AUTO_INCREMENT`, `CHECK`
