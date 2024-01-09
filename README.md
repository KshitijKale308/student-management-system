# Spring Boot CRUD Project with Spring MVC, Spring Data JPA, Thymeleaf, Hibernate, MySQL


## Tools and Technologies Used
- Java 17
- Spring Boot 3
- Spring MVC
- Spring Data JPA (Hibernate)
- MySQL
- Thymeleaf
- Eclipse STS

## Tutorial Sections
1. [Create Spring Boot Project](#create-spring-boot-project)
2. [Create Spring Boot Project Structure](#create-spring-boot-project-structure)
3. [Maven Dependencies](#maven-dependencies)
4. [Create Student JPA Entity](#create-student-jpa-entity)
5. [Create JPA StudentRepository](#create-jpa-studentrepository)
6. [Configure MySQL Database](#configure-mysql-database)
7. [Creating Service Layer](#creating-service-layer)
8. [Controller Layer](#controller-layer)
9. [View Layer](#view-layer)

## Detailed Steps

### 1. Create Spring Boot Project
[Link to guide for creating a Spring Boot project in Eclipse STS IDE](#)
Specify dependencies like:
- Spring Web
- Thymeleaf
- Spring Data JPA
- MySQL Driver
- Spring Boot Devtools

### 2. Create Spring Boot Project Structure
Create packages:
- `controller`
- `service`
- `repository`
- `entity`

### 3. Maven Dependencies
Note: Spring Boot 3 requires Java version 17 or later.

Add Maven dependencies in your `pom.xml` file.

### 4. Create Student JPA Entity
Create a `Student` JPA entity under the `entity` package.

### 5. Create JPA StudentRepository
Create a `StudentRepository` interface under the `repository` package.

### 6. Configure MySQL Database
Set up MySQL database configuration in the `application.properties` file.

### 7. Creating Service Layer
- Create a `StudentService` interface.
- Implement `StudentServiceImpl` class.

### 8. Controller Layer
Create a `StudentController` class for handling HTTP requests.

### 9. View Layer
Create `students.html` under `resources/templates` for the front-end view.
