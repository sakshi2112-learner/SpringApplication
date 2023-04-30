# SpringApplication
# Basic Concepts

**Spring MVC ⇒** 

- Spring MVC (Model-View-Controller) is a widely used framework for building web applications in Java.
- three distinct components: Model, View, and Controller
- The Model represents the data and business logic, the View represents the presentation layer, and the Controller acts as an intermediary between the Model and View.
- Spring MVC provides various features like handling user requests, processing form data, handling exceptions, and providing various types of views like JSP, Thymeleaf, and more

anything written after "@" is an annotation.

Annotations are used to define beans, endpoints, request mappings, security configurations, and many other aspects of Spring Boot applications.

**Spring Boot ⇒** annotations available in Spring Boot 

1. @SpringBootApplication: This annotation is used to indicate that a class is the main entry point of the application.
2. @Controller: This annotation is used to indicate that a class is a web controller.
3. @RestController: This annotation is used to indicate that a class is a RESTful web controller.
4.  @RequestMapping: This annotation is used to map a URL request to a specific method in a controller.
5. @GetMapping: This annotation is used to map a GET request to a specific method in a controller.
6. @PostMapping: This annotation is used to map a POST request to a specific method in a controller.
7. @PutMapping: This annotation is used to map a PUT request to a specific method in a controller.

**Spring Data ⇒** 

Spring Data provides support for both relational databases and NoSQL databases, including MongoDB, Cassandra, and Redis, among others. CRUD operations can also be performed using Spring Data.

Some of the subprojects of Spring Data are:

- Spring Data JPA: Provides support for the Java Persistence API (JPA) standard, and simplifies the development of JPA-based data access layers.
- Spring Data MongoDB: Provides support for MongoDB, and allows developers to use MongoDB as a persistent store in Spring applications.
- Spring Data JDBC: Provides a simple JDBC-based approach to access relational databases, and eliminates the need for boilerplate JDBC code.
- Spring Data Redis: Provides support for Redis, and offers features such as object-to-hash mapping, distributed locks, and Redis scripts.
- Spring Data REST: Provides a framework for building hypermedia-driven RESTful web services using Spring Data repositories as the data access layer.

*By using Spring Data, developers can focus on writing business logic rather than worrying about the intricacies of different data access technologies.*
