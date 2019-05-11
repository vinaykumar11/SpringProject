# Spring Boot Application
The following features are implemented in this mini todo management project:
### New Features!
- Create Todo
- Update Todo
- Delete Todo
- List Todo
- Get Todo by id.
- Simple Spring security
- Webjars to manage client-side dependencies(CSS and JS).
- JSP as view and common header, footer, and navigation bar.
- Custom error page mapping
### Implemented the following features to this Todo Management project:
- **Finish Todo feature:** Add finish button and save status against each record in a database.
- **logging:** 
Refer below article to implement logging effectively in this Todo management project Spring Boot 2 Logging SLF4j Logback and LOG4j2 Example
- **Role-based spring security:**
Refer below article to implement role-based Spring security effectively in this Todo management project Spring Boot + Spring MVC + Role Based Spring Security + JPA + Thymeleaf + MySQL Tutorial
- **Exception handling:**
Refer below article to implement exception handling effectively in this Todo management project Spring Boot 2 Exception Handling for REST APIs
- **Validation:**
Refer below article to implement validation effectively in this Todo management project Spring Boot CRUD REST APIs Validation Example
- **Auditing:**
Refer below article to implement auditing effectively in this Todo management project Spring Data JPA Auditing with Spring Boot 2 and MySQL Example
### What we’ll build
We will develop step by step Spring MVC Todo management web application using Spring Boot, Spring MVC, Spring Security, JSP, JPA and MySQL as a database.
### Tools and Technologies Used
- Spring Boot - 2.0.4.RELEASE
- JDK - 1.8 or later
- Spring Framework - 5.0.8 RELEASE
- Hibernate - 5.2.17.Final
- Maven - 3.2+
- Spring Data JPA - 2.0.10 RELEASE
- IDE - Eclipse or Spring Tool Suite (STS)
- MYSQL - 5.1.47
- Spring Security - 5.0.7 RELEASE
- JSP

### Running the Application
We have successfully developed the Mini Todo Management web application. Now it's time to deploy our application in a servlet container(embedded tomcat). Two ways we can start the standalone Spring boot application.
1) From the root directory of the application and type the following command to run it -
```sh
$ mvn spring-boot:run
```
2) From your IDE, run the TodoManagementSpringBootApplication.main() method as a standalone Java class that will start the embedded Tomcat server on port 8080 and point the browser to http://localhost:8080/

### DEMO URL's
1. Login Page
URL : http://localhost:8080/login
```sh
Username: admin
Password: admin
```
2. Home Page
After successfully user logged in navigate to a home page.

3. List Todos
URL: http://localhost:8080/list-todos

4. Create Todo
URL: http://localhost:8080/add-todo

5. Update Todo
URL: http://localhost:8080/update-todo?id=28

6. Logout Page
URL: http://localhost:8080/login?logout
