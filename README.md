🎓 University Advising Management System (JavaFX)

A desktop application developed using JavaFX and Java that allows users to manage academic relationships within a university environment.
The system supports managing Advisers, Studies, and Supervision relationships, with full CRUD operations connected to a SQL database.

This project demonstrates how to build a JavaFX GUI application integrated with a database using Maven and MVC architecture principles.

📖 Project Description

The University Advising Management System is designed to help manage academic information related to advisers and students.
Through a graphical interface, users can perform operations such as adding, updating, deleting, and viewing records stored in the database.

The application uses JavaFX with FXML for UI design, and separates the logic using a controller-based architecture, making the code easier to maintain and extend.

🚀 Features

Manage Advisers

Manage Student Studies

Manage Supervision relationships

Perform CRUD operations (Create, Read, Update, Delete)

Interactive JavaFX user interface

Organized project structure

Database integration using SQL

Maven-based dependency management

🛠 Technologies Used

Java

JavaFX

FXML

Maven

SQL Database

MVC Architecture

📂 Project Structure
src
 └── main
     ├── java
     │   └── org/example/demo2
     │       ├── Controller
     │       │   ├── MainController.java
     │       │   ├── AdvisersController.java
     │       │   ├── StudiesController.java
     │       │   └── SupervisesController.java
     │       │
     │       ├── db
     │       │   ├── AdviserCrudOperations.java
     │       │   ├── StudiesCrudOperations.java
     │       │   └── SupervisesCrudOperations.java
     │       │
     │       ├── dto
     │       │   ├── Adviser.java
     │       │   ├── Studies.java
     │       │   └── Supervises.java
     │       │
     │       ├── Pro1Application.java
     │       └── Launcher.java
     │
     └── resources
         └── org/example/demo2
             ├── Main.fxml
             ├── Advisers.fxml
             ├── Studies.fxml
             └── Supervises.fxml
🗄 Database Setup

The repository includes a SQL file:

DB.sql

This file contains the database schema required for the project.

Steps to set up the database:

Open your database system (MySQL, PostgreSQL, etc.).

Create a new database.

Execute the SQL script located in DB.sql.

Update the database connection settings in the project if needed.

▶️ How to Run the Project
1. Clone the repository
git clone https://github.com/yourusername/repository-name.git
2. Open the project

Open the project using an IDE such as:

IntelliJ IDEA

Eclipse

VS Code with Java extensions

3. Install dependencies

The project uses Maven to manage dependencies.

Run:

mvn clean install

or let your IDE automatically download the dependencies.

4. Run the application

Run one of the following classes:

Launcher.java

or

Pro1Application.java

The JavaFX application window will open.

📸 Application Screens

The application contains several graphical interfaces including:

Main Dashboard

Advisers Management

Studies Management

Supervision Management

All interfaces are designed using JavaFX FXML.

🎯 Learning Objectives

This project was built to practice and demonstrate:

JavaFX GUI development

MVC architecture in Java applications

Database CRUD operations

Java and SQL integration

Maven project structure

Desktop application development


Computer Science Student

🔗 LinkedIn
https://www.linkedin.com/in/ziyad-alboghdady-a50ab8247

💻 GitHub
https://github.com/ziyad-alboghdady

📄 License

This project is for educational purposes and can be freely used for learning and academic practice.
