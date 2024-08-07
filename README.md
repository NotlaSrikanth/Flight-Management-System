# Flight-Management-System

       Developed a robust for Flight Management System. Utilized java for backend development, hibernate ORM for object-relation mapping Spring Boot and, MySQL for database 
  management, and RESTful API for seamless front-end to back-end integration. Project follows a modular structure with well-defined packages for different responsibility.

  Key-Packages:
      1.	DTO (Data Transfer Objects): 
           •	Contains lightweight objects used for data exchange between layers (e.g.: between controller and service)
           •	DTOs map to database entities and simplify data transformation.
      2.	Repository Layer:
           •	Contains JPA repositories(interfaces) that extends JpaRepository.
           •	Provides high-level abstraction for database operations.
      3.	DAO (Data Transfer Objects):
           •	Responible for database interactions (CURD operation).
           •	The annotation of @Repository that class responsible for integrate with data base
      4.	Service Layer:
           •	Implements business logic and orchestrates between DAOs and controllers.
           •	@Service Annotation to indicate that a class belongs to business logic
      5.	Controller Layer:
           •	Handles incoming HTTP requests.
           •	Maps URLs to appropriate service methods.
           •	@RestController Annotation to handle the all-RESTful APIs coming from the POSTMAN
      6.	RESTful APIs:
          •	Follow REST convections (e.g., proper HTTP methods, resource naming).
