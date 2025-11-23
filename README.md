# Student Result Management System

## 📌 Objective

This project integrates Java concepts into a working console-based application capable of performing **CRUD operations using JDBC**. It demonstrates how Object-Oriented Programming, collections, and MySQL database connectivity work together in a real-world software scenario.

---

## 🧰 Tech Stack

* **Language:** Java
* **Database:** MySQL
* **Connectivity:** JDBC
* **Data Structure:** ArrayList
* **Interface:** Console-based application

---

## 📜 Project Description

The **Student Result Management System** allows users to:

* Add new student records
* Update existing student details
* Delete student entries
* View stored student information
* Store and retrieve data from MySQL using JDBC
* Maintain an in-memory list using `ArrayList`

### Project Class Structure

| Class Name        | Description                                       |
| ----------------- | ------------------------------------------------- |
| `Student`         | Represents the student entity                     |
| `Result`          | Stores subject marks and total calculation        |
| `DatabaseManager` | Handles JDBC database connectivity and operations |

---

## 🧠 Concepts Practiced

* Object-Oriented Programming (Encapsulation, Classes, Objects)
* CRUD operations using JDBC
* Using `ArrayList` for managing records in memory
* Exception handling for stable execution
* Menu-driven program flow through console interaction

---

## 🗄 Database Setup

Run the following SQL commands in MySQL to create the database and table:

```sql
CREATE DATABASE users;
USE users;

CREATE TABLE students (
  id INT PRIMARY KEY AUTO_INCREMENT,
  name VARCHAR(50),
  course VARCHAR(50)
);
```

---

## ⚙ Configuration

Before running the project:

1. Install MySQL and ensure the database is created.
2. Add the **MySQL JDBC Driver** (`mysql-connector.jar`) to the project classpath.
3. Update database credentials inside `DatabaseManager.java`, for example:

```java
private static final String DB_URL = "jdbc:mysql://localhost:3306/users";
private static final String DB_USER = "root";
private static final String DB_PASS = "password";
```

---

## 🚀 How to Run

1. Clone the repository:
   `https://github.com/Aryan-17806/Student-Result-Management-System`
2. Open the project in your preferred Java IDE (IntelliJ, Eclipse, NetBeans, etc.).
3. Ensure MySQL is running and the database setup script has been executed.
4. Compile and run the main application file (`StudentManagementApp.java`).

---

## 📖 Learning Outcomes

By completing this project, students will:

* Implement clean and maintainable Java code
* Apply OOP principles in real application development
* Perform database CRUD operations using JDBC
* Work with both in-memory and persistent storage

---

## 🤝 Contribution

Contributions are welcome!
Feel free to fork the project and submit pull requests for improvements.

---

## 📄 License

This project is intended for educational and academic use.
