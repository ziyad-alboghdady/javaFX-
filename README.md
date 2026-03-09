🎓 University Advising Management System

A JavaFX desktop application that manages university academic relationships such as Advisers, Studies, and Supervision.
The system allows users to perform CRUD operations through a graphical interface connected to a SQL database.

This project demonstrates building a Java desktop application using JavaFX, Maven, and MVC architecture.

📖 Project Overview

The University Advising Management System is designed to help manage academic information related to advisers and students.

The application provides an intuitive interface that allows users to:

Add and manage advisers

Manage student study records

Manage supervision relationships

Store and retrieve information from a database

The project follows a structured approach separating controllers, database logic, and data models.

🚀 Features

Manage Advisers

Manage Student Studies

Manage Supervision relationships

Perform CRUD operations

Interactive JavaFX GUI

Database integration with SQL

Organized project structure using MVC

🛠 Technologies Used
Technology	Purpose
Java	Core programming language
JavaFX	Graphical User Interface
FXML	UI layout design
Maven	Dependency management
SQL	Database storage
📂 Project Structure
src/main/java/org/example/demo2

Controller
 ├── MainController.java
 ├── AdvisersController.java
 ├── StudiesController.java
 └── SupervisesController.java

db
 ├── AdviserCrudOperations.java
 ├── StudiesCrudOperations.java
 └── SupervisesCrudOperations.java

dto
 ├── Adviser.java
 ├── Studies.java
 └── Supervises.java

Launcher.java
Pro1Application.java

FXML files are located in:

src/main/resources/org/example/demo2
🗄 Database Setup

The repository contains a database script:

DB.sql
Setup steps

Open your SQL database system.

Create a new database.

Run the DB.sql script.

Update the database connection settings if necessary.

▶️ Running the Project
1️⃣ Clone the repository
git clone https://github.com/yourusername/repository-name.git
2️⃣ Open the project

Open the project using:

IntelliJ IDEA

Eclipse

VS Code

3️⃣ Install dependencies

Run:

mvn clean install
4️⃣ Run the application

Run:

Launcher.java

or

Pro1Application.java
🎯 Learning Goals

This project demonstrates:

JavaFX desktop application development

MVC architecture

Database CRUD operations

Java and SQL integration

Maven project structure

👨‍💻 Author

Ziyad Alboghdady
Computer Science Student

🔗 LinkedIn
https://www.linkedin.com/in/ziyad-alboghdady-a50ab8247

💻 GitHub
https://github.com/ziyad-alboghdady

📄 License

This project is created for educational and learning purposes.
