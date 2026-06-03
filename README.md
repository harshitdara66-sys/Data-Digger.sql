# Data Digger SQL Project

## 📌 Overview
Data Digger is a SQL practice project that demonstrates core database operations using a Customer and Orders management system. The project covers CRUD operations, filtering, joins, and query execution examples with sample outputs.

## 🚀 Features
- Create and manage database tables
- Insert sample records
- Retrieve data using SELECT queries
- Update existing records
- Delete records
- Filter data using WHERE clauses
- Customer and Orders relationship examples
- SQL query output demonstrations

## 🗄️ Database Schema

### Customer Table
| Column | Type |
|---------|------|
| CustomerID | INT |
| Name | VARCHAR(255) |
| Email | VARCHAR(255) |
| Address | VARCHAR(255) |

### Orders Table
| Column | Type |
|---------|------|
| OrderID | INT |
| CustomerID | INT |
| OrderDate | DATE |
| Total_Amount | INT |

## 📂 Project Structure

```text
.
├── Data Digger.sql
└── README.md
```

## 🛠 SQL Operations Covered

### CREATE TABLE
Creates Customer and Orders tables.

### INSERT
Adds sample customer and order records.

### SELECT
Retrieves records from tables.

### UPDATE
Modifies existing customer and order information.

### DELETE
Removes records from tables.

### FILTERING
Uses WHERE clauses to retrieve specific data.

## 💻 Example Query

```sql
SELECT * FROM Customer
WHERE Name = 'Alice';
```

## 🎯 Learning Outcomes
- Database design fundamentals
- SQL syntax and commands
- CRUD operations
- Data retrieval techniques
- Table relationships
- Query optimization basics

## ⚙️ Requirements

- MySQL 8.0+
- MariaDB (optional)
- Any SQL-compatible database client

## ▶️ How to Run

1. Create a database.
2. Import `Data Digger.sql`.
3. Execute the script.
4. Review query results and outputs.

## 🤝 Contributing

Feel free to fork the repository and submit improvements.

## 👨‍💻 Author

Harshit Dara

## 📄 License

This project is intended for educational and learning purposes.

