# Hibernate Student Management System

A Java-based Student Management Web Application developed using Hibernate ORM, Java Servlets, Maven, MySQL, HTML/CSS, and Apache Tomcat.

The application allows users to manage student records and demonstrates CRUD (Create, Read, Update, Delete) operations using Hibernate for database interaction.

## Technologies Used

- Java 17
- Hibernate ORM
- Jakarta Servlets
- MySQL
- Maven
- Apache Tomcat 10.1
- HTML5
- CSS3
- Eclipse IDE

## Features

- Student registration
- Add student records
- View student records
- Update student information
- Delete student records
- MySQL database integration
- Hibernate ORM-based database operations
- Servlet-based web application

## Student Details

- Student ID
- Name
- Department
- Age

## Project Architecture

HTML/CSS → Java Servlet → Hibernate ORM → MySQL Database

## Project Structure

maven-archetype-webapp
├── src/main/java
│   ├── com.database.operation
│   ├── com.student.model
│   ├── com.test.util
│   └── com.student.controller
├── src/main/resources
│   └── hibernate.cfg.xml
├── src/main/webapp
│   ├── index.html
│   └── WEB-INF
│       └── web.xml
└── pom.xml

## Database

The project uses MySQL as the database and Hibernate ORM for object-relational mapping.

Database: studentdb
Table: student

## Purpose

This project was developed to understand Java web application development using Hibernate, Servlets, Maven, MySQL, and Apache Tomcat, while implementing database CRUD operations.

## Future Enhancements

- Student search
- Student filtering
- Improved UI
- Form validation
- Login and authentication
- Pagination
- Student dashboard

## Author

Shriya Sharma
