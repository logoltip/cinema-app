# 🎞️ Cinema-app 🎞️

### 📝 Description:

Simple web app that supports authentication, authorization and have CRUD operations (with Spring and Hibernate).

### 📹️ Technologies used:

Java 17, Spring MVC, Spring Security, Hibernate, MySql, Tomcat 9.0.71, Maven.

### 🖨️ Project structure:

- Controllers layer - http controllers.
- Service layer - all business logic (and connecting dao with controllers).
- Model and DTO layer - models and DTOs (for http requests and responses).
- DAO layer - work with database.
- Config layer - config classes required by Spring & Hibernate.

### 📋 Functional app schema:

![pic](Hibernate_Cinema_Uml.png)

### 🎫 How to use app:

1. You need to install Intellij, JDK 17, MySQL and TomCat 9.* on your computer (if you don't have some already);
2. Clone this project on GitHub;
3. Copy SSH key, and create new Project from Version Control... in your Intellij;
4. Change properties in db.properties to your DB settings: URL, username, password, Driver;
5. Edit configuration of your TomCat;
6. Run ```mvn package``` command in terminal;
7. Start Tomcat;
8. Let the magic begin 🪄

P.s. For the best experience, use Postman for POST endpoints.
