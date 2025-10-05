# 📚 Flexisaf Task 4 – Hibernate Entity Design (Library Management System)

This task demonstrates the use of key Hibernate annotations to design a database table for a Library Management System.  
The entity created here is Book, which represents book records in the library.

## ⚙ Entity Fields
- id  
- title  
- author  
- isbn  
- firstname
- last name 
- publishedDate
- Email
- phonenumber
- membership date


## 📘 Hibernate Annotations Used
- @Entity  
- @Table  
- @Id  
- @GeneratedValue  
- @Column  
 

## 🏁 How to Run
1. Add this entity to your existing Spring Boot project.  
2. Configure your PostgreSQL credentials in application.properties.  
3. Run the project:
   ```bash
   mvn spring-boot:run
