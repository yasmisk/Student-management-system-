# Student Management System

A beginner-friendly Java full-stack CRUD application.

## Technologies
- HTML, CSS, JavaScript
- Java Servlet
- JDBC
- MySQL
- Maven
- Apache Tomcat 10+
- JDK 17+

## Features
- Add student
- View students
- Search students
- Update student
- Delete student

## Setup

1. Install JDK 17+, MySQL, Maven and Tomcat 10+.
2. Open MySQL and run `database.sql`.
3. Open:
   `src/main/java/com/yasmi/studentapp/DBConnection.java`
4. Change the MySQL username and password.
5. In the project folder run:
   `mvn clean package`
6. Copy:
   `target/student-management-system.war`
   into Tomcat's `webapps` folder.
7. Start Tomcat.
8. Open:
   `http://localhost:8080/student-management-system/`

## JDBC flow

Browser
  -> HTML/CSS/JavaScript
  -> Java Servlet
  -> JDBC
  -> MySQL
