📚 Library Management System – Java (NetBeans + JDBC + SQL)

🧾 Project Overview
        This Library Management System is a desktop-based application developed in Java using the NetBeans IDE. It utilizes JDBC for database connectivity and SQL for data operations. The system allows librarians to manage books, students, and transactions such as issuing and returning books.

🛠️ Technologies Used
- Java (JDK 8+)
- NetBeans IDE
- JDBC (Java Database Connectivity)
- MySQL Database

📦 Features & Modules

| Login |  
| AddStudent |  
| AddBook |   
| Statistics |  
| IssueBook |   
| ReturnBook |   
| Logout |  


🗃️ Database Schema
Tables:
- students(student_id, name, course, branch)
- books(book_id, title, author, publisher)
- issue(issue_id, student_id, book_id, issue_date)
- return(return_id, issue_id, return_date)
Ensure MySQL is running and the database is created before launching the application.

🔌 Setup Instructions
- Clone or download the project.
- Open NetBeans and load the project.
- Configure JDBC:
  - Add the MySQL JDBC driver to your project libraries.
  - Update the database connection string in your Connection.java class.
- Create the database:
  - Use the provided SQL script or manually create tables as per the schema.
- Run the project:
  - Start with the Main.java or Login.java class.
    
🔐 Login Credentials
Default credentials (can be changed in the database):
- Username: Admin
- Password: admin
- 

📌 Notes
- Exception handling is implemented for database operations.
- GUI is built using Java Swing components.
- Modular design with separate classes for each functionality.
- 
📄 License
  This project is for educational purposes. Feel free to modify and enhance it.
