# User management by using Spring Boot and PostgreSQL
Here's a step-by-step guide to building REST APIs using the Java Spring framework with PostgreSQL for the specified endpoints:

## 1. Set Up Your Spring Boot Project

### Create a New Spring Boot Project:

Use Spring Initializr (https://start.spring.io/) to create a new project.
Choose the following dependencies:
- Spring Web
- Spring Data JPA
- PostgreSQL Driver

### Configure the application.properties:

## 2. Create the User Entity

## 3. Create the User Repository

## 4. Create the User Service

## 5. Create the User Controller

## 6. Run Your Application
- Ensure PostgreSQL is running and the database is created.
- Run your Spring Boot application.
- Use tools like Postman or curl to test the endpoints.

## 7. Test Your API
- GET /users: Retrieve all users.
- GET /user/{id}: Retrieve a user by ID.
- POST /user: Create a new user.
- PUT /user: Update an existing user.
- DELETE /user/{id}: Delete a user by ID.


### Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/3.3.3/gradle-plugin)
* [Create an OCI image](https://docs.spring.io/spring-boot/3.3.3/gradle-plugin/packaging-oci-image.html)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.3.3/reference/htmlsingle/index.html#web)
* [Spring Data JPA](https://docs.spring.io/spring-boot/docs/3.3.3/reference/htmlsingle/index.html#data.sql.jpa-and-spring-data)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)
* [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)

### Additional Links
These additional references should also help you:

* [Gradle Build Scans – insights for your project's build](https://scans.gradle.com#gradle)
