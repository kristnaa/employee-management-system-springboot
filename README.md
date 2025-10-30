# employee-management-system-springboot
A Spring Boot web application for managing employee records with CRUD operations using MVC, Thymeleaf, Spring Data JPA, and MySQL.


# Project Title:

Employee Management (CRUD) System

## 1. Project Description:

A Spring Boot and Thymeleaf web application for managing employee information with full CRUD operations:

- View all employees
- Add a new employee
- Update employee details
- Delete an employee

This project demonstrates the use of Spring MVC, Spring Data JPA, and MySQL for building a simple yet complete employee management system.

---

## 2. Tech Stack:

- Java 17
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate
- Thymeleaf
- HTML
- Bootstrap
- Maven
- MySQL Database

---

## 3. Installation & Setup:

### i. Clone the GitHub Repository

git clone https://github.com/kristnaa/employee-management-system-springboot.git

### ii. Open the Project Folder

Open the folder in your preferred IDE (IntelliJ IDEA, Eclipse, or Spring Tool Suite).

### iii. Database Setup

1. Create a new MySQL database named demo (or update the name in application.properties).  
2. Update your MySQL username and password in:
   src/main/resources/application.properties

Example:
spring.datasource.url=jdbc:mysql://localhost:3306/demo
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update

### iv. Run the Project

Run the application as a Spring Boot App.  
Hibernate will automatically create the employee table in your database.

---

## 4. How To Use:

1. Launch the web app at:
   http://localhost:8080/

2. Use the interface to:
   - Add new employees
   - Update existing employee information
   - Delete employees
   - View all employee records

 
    ALL THE BEST

✨ Modified and maintained by A M V K Я (https://github.com/kristnaa)

