### This is a library management system project.

#### I developed a web application by using Spring Boot.

### Tech stack:
Requirements:
The application should use the Spring Framework with Spring Boot and be built using Maven or Gradle. 

The application should include two entities: Book and Borrower with a many-to-many relationship. 

The Book entity should have the following fields: id, title, author, publisher, and ISBN. 

The Borrower entity should have the following fields: id, name, email, and phone number. 

The application should allow librarians to perform CRUD operations (Create, Read, Update, Delete) on each entity. 

The application should use Thymeleaf as the view template engine. 

The application should use Spring Data JPA to interact with the database. 

The application should use Hibernate as the ORM tool. 

The application should use MySQL or PostgreSQL as the database. 

The application should include appropriate error handling and validation. 

The application should include a user interface that is easy to use and responsive. 

The application should have a search functionality that allows librarians to search for books by title, author, or ISBN. 

### Requirements

For building and running the application you need:
- [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) or newer
- [Maven 3](https://maven.apache.org)
- [Lombok](https://projectlombok.org)

### Build & Run 

```
  mvn clean install && mvn --projects backend spring-boot:run
```
  
### Port
```
  http://localhost:8081
```

### Features

![Books](https://github.com/mehmetpekdemir/Library-Management-System/blob/master/Photo/Books.png)
![addBook](https://github.com/mehmetpekdemir/Library-Management-System/blob/master/Photo/addBook.png)
![search](https://github.com/mehmetpekdemir/Library-Management-System/blob/master/Photo/search.png)
![Authors](https://github.com/mehmetpekdemir/Library-Management-System/blob/master/Photo/Authors.png)
![Categories](https://github.com/mehmetpekdemir/Library-Management-System/blob/master/Photo/Categories.png)
![Publishers](https://github.com/mehmetpekdemir/Library-Management-System/blob/master/Photo/Publishers.png)
