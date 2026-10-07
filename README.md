# Student Management System – Java & JDBC

A console-based **Student Management System** developed using **Java and JDBC** with **MySQL** as the database. The application allows users to manage student records through basic CRUD (Create, Read, Update, Delete) operations.

## 📌 Project Description

The Student Management System is a Java console application designed to demonstrate database connectivity using **JDBC**.

Users can add, view, update, and delete student information stored in a MySQL database through an interactive command-line interface.

## ✨ Key Features

- ➕ Add new student records
- 📋 View all student records
- ✏️ Update existing student details
- 🗑️ Delete student records
- 👨‍🎓 Store student ID, first name, last name, major, and GPA
- ⌨️ Interactive console-based input
- 🗄️ MySQL database integration using JDBC
- 🔄 Complete CRUD functionality

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Java SE 8+** | Application development |
| **JDBC** | Database connectivity |
| **MySQL** | Data storage |
| **Eclipse IDE** | Development environment |

## 📂 Project Structure

```text
StudentManagementSystemJava_JDBC/
│
├── src/
│   └── ...
│
├── studentdb_setup.sql
│
├── README.md
│
└── ...
```

> The exact source-file structure may vary depending on the Eclipse project configuration.

## ⚙️ Prerequisites

Before running the project, make sure you have:

- Java Development Kit (**JDK 8 or higher**)
- **MySQL Server**
- **MySQL Workbench** (recommended)
- **Eclipse IDE**
- **MySQL JDBC Driver**

## 🚀 Setup and Installation

### 1. Clone the Repository

```bash
git clone <your-repository-url>
```

Navigate into the project directory:

```bash
cd StudentManagementSystemJava_JDBC
```

### 2. Import the Project into Eclipse

1. Open **Eclipse IDE**
2. Select **File → Import**
3. Choose the appropriate Java project import option
4. Select the cloned project
5. Make sure the project builds successfully

### 3. Set Up the MySQL Database

Open **MySQL Workbench** and run the provided:

```text
studentdb_setup.sql
```

This script creates the required database and student table.

### 4. Configure Database Credentials

Open:

```text
DBConnection.java
```

Update the database connection details with your own MySQL credentials.

Example:

```java
String url = "jdbc:mysql://localhost:3306/studentdb";
String username = "root";
String password = "your_password";
```

> Do not upload your actual database password to GitHub.

### 5. Run the Application

Run:

```text
MainApp.java
```

The application will start in the Eclipse console.

## 💻 Usage

After starting the application, follow the instructions displayed in the console.

The application allows you to:

1. Enter student details
2. Add students to the database
3. View stored student records
4. Update existing student information
5. Delete student records

Example student information:

```text
Student ID : 101
First Name : Ravi
Last Name  : Kumar
Major      : Computer Science
GPA        : 8.5
```

## 🗃️ Database Operations

The application demonstrates the four fundamental CRUD operations:

```text
CREATE  → Add a student
READ    → View students
UPDATE  → Modify student details
DELETE  → Remove a student
```

## 🎯 Learning Outcomes

Through this project, you can understand:

- Java database connectivity using JDBC
- MySQL database integration
- SQL CRUD operations
- Prepared Statements
- Exception handling
- Console-based Java applications
- Connecting Java applications with relational databases

## 🤝 Contributing

Contributions are welcome!

If you would like to improve the project:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit your changes
5. Push the branch
6. Create a Pull Request

## 📄 License

This project is licensed under the **MIT License**.

## 👨‍💻 Author

**Tharun L**

Computer Science & Engineering

---

⭐ If you found this project useful, consider giving the repository a star!
