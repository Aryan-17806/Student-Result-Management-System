# Student Result Management System

## 📌 Objective

This project integrates Java concepts into a working console-based application capable of performing **CRUD operations using JDBC**. It demonstrates how OOP, collections, and MySQL connectivity can be applied in a real-world project.

---

## 🧰 Tech Stack

* **Language:** Java
* **Database:** MySQL
* **Connectivity:** JDBC
* **Data Structures:** ArrayList
* **Interface:** Console-based application

---

## 📜 Project Description

The **Student Result Management System** allows users to:

* Add new student records
* Update existing student details
* Delete student records
* View student information and results
* Store and retrieve information using MySQL via JDBC
* Maintain an in-memory copy using ArrayList

Key classes in the project:

| Class Name        | Responsibility                               |
| ----------------- | -------------------------------------------- |
| `Student`         | Represents student entity                    |
| `Result`          | Stores subject-wise marks and result details |
| `DatabaseManager` | Handles database operations using JDBC       |

---

## 🧠 Concepts Practiced

* Object-Oriented Programming (Classes, Objects, Encapsulation)
* Collections (`ArrayList`)
* Exception handling
* JDBC-based CRUD operations
* Menu-driven interactive system

---

## 🗄 Database Setup

Run the following commands in MySQL:

```sql
CREATE DATABASE users;
USE users;

CREATE TABLE students (
  id INT PRIMARY KEY AUTO_INCREMENT,
  name VARCHAR(50),
  course VARCHAR(50)
);
```

```

---

## ⚙ Configuration

Before running the application:

1. Add the **MySQL JDBC Driver** (e.g., `mysql-connector-j.jar`) to the project.
2. Update database connection details in `DatabaseManager.java`:

```java
private static final String DB_URL = "jdbc:mysql://localhost:3306/studentdb";
private static final String DB_USER = "root";
private static final String DB_PASS = "password";
```

---

## 🚀 How to Run

1. Clone the repository:
   `https://github.com/Aryan-17806/Student-Result-Management-System`
2. Import the project into your IDE (Eclipse, IntelliJ, NetBeans, etc.).
3. Ensure MySQL is running and the database is created.
4. Compile and run `StudentManagementApp.java`.

---

## 📖 Learning Outcomes

By completing this project, learners will:

* Apply OOP principles in a real-world application
* Write reusable and maintainable code
* Perform CRUD operations using JDBC
* Understand how in-memory and persistent storage can work together

---

## 🤝 Contribution

Contributions, improvements, and suggestions are welcome! Submit a pull request anytime.

---

## 📄 License

This project is intended for academic and learning purposes.
