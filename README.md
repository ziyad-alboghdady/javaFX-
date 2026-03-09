# 🎓 University Advising Management System

A **JavaFX desktop application** for managing academic relationships in a university environment.  
The system allows users to manage **Advisers, Studies, and Supervision relationships** through a graphical interface connected to a **SQL database**.

This project demonstrates the use of **Java, JavaFX, Maven, and MVC architecture** to build a structured desktop application.

---

## 📖 Project Overview

The **University Advising Management System** helps manage university academic data in an organized way.

Users can:

- Add and manage advisers  
- Manage study records  
- Manage supervision relationships  
- Store and retrieve data from a database  

The application uses **JavaFX with FXML** for building the graphical interface and organizes the code using **controllers, data models, and database operations**.

---

## 🚀 Features

- Manage **Advisers**
- Manage **Studies**
- Manage **Supervision relationships**
- Perform **CRUD operations**
- Interactive **JavaFX user interface**
- Database integration
- Organized project structure

---

## 🛠 Technologies Used

- **Java**
- **JavaFX**
- **FXML**
- **Maven**
- **SQL Database**

---

## 📂 Project Structure

### Source Code

src/main/java/org/example/demo2

Controller
- MainController.java
- AdvisersController.java
- StudiesController.java
- SupervisesController.java

db
- AdviserCrudOperations.java
- StudiesCrudOperations.java
- SupervisesCrudOperations.java

dto
- Adviser.java
- Studies.java
- Supervises.java

Launcher.java  
Pro1Application.java

### Resources

FXML files are located in:

src/main/resources/org/example/demo2

---

## 🗄 Database Setup

The project includes a database script:

DB.sql

### Steps to set up the database

1. Open your database system (MySQL / PostgreSQL / etc.)
2. Create a new database
3. Run the SQL script inside **DB.sql**
4. Update the database connection settings if needed

---

## ▶️ Running the Project

### 1. Clone the repository

git clone https://github.com/ziyad-alboghdady/javaFX-.git

### 2. Open the project

Open the project using an IDE such as:

- IntelliJ IDEA
- Eclipse
- VS Code

### 3. Install dependencies

mvn clean install

### 4. Run the application

Run one of these classes:

Launcher.java

or

Pro1Application.java

---

## 🎯 Learning Objectives

This project demonstrates:

- JavaFX desktop application development  
- MVC architecture in Java  
- Database CRUD operations  
- Java and SQL integration  
- Maven project management  


---

## 📄 License

This project is created for **educational and learning purposes**.

