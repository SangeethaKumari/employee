This is a RESTful API built with Java Spring Boot that provides CRUD operations for managing tasks.
It follows REST principles of  stateless, client-server communication model using standard HTTP methods and uses Spring Boot architecture.

Spring Boot follows a layered architecture that simplifies building scalable applications. It consists of:

1️⃣ Presentation Layer – Handles HTTP requests via Controllers (@RestController) and returns responses (JSON, HTML).
2️⃣ Service Layer – Contains business logic (@Service), interacting between the controller and repository.
3️⃣ Repository Layer – Uses Spring Data JPA (@Repository) to interact with the database.
4️⃣ Database Layer – Stores data using H2, MySQL, PostgreSQL, or other databases, managed by Hibernate (JPA).

Spring Boot uses auto-configuration, embedded servers (Tomcat), and dependency injection to streamline application development. 🚀

Note ** In this project , yet to include the Databases functionality. Added java classes to insert, and remove rows of datas.
