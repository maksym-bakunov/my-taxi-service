# :taxi: Taxi Service :taxi:

<p align="center">
  <a href="#description">Description</a> •
  <a href="#structure">Structure</a> •
  <a href="#used-technologies">Used technologies</a> •
  <a href="#how-to-use">How To Use</a>
</p>

## Description

This simple web application allows users to log in and log out. After authentication, the user can:
- add/update/delete information about cars, drivers and manufacturers.
- displaying a list of cars, drivers and manufacturers.

## Structure
#### This web application structure is N-tier architecture model that including the following layers:
- Controllers
- Service
- DAO (CRUD operations)

## Used technologies

- JDK 11
- Java Servlet API 4.0.1
- JSP
- JSTL 1.2
- MySQL 8.0
- JDBC
- Apache Tomcat 9.0.50
- Apache Maven 3.8.11

## How To Use

- Clone this project.
- Install MySQL and create a schema by using the script from resources/init_db.sql.
- Set up and run Apache TomCat.
- Change url, driver, username and password in  /util/ConnectionUtil.java file. 
- Configure Local Apache TomCat Service in your IDE
- Start application
- Enjoy
