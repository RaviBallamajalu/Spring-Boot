## Spring Boot Annotations

 
 ### @SpringBootApplication
 * Used to identify the main class of a Spring Boot application.
 * It Consits of 3 Other Annotation @Configuration, @EnableAutoConfiguration, and @ComponentScan
 * @ Configuration : The class annotated with @Configuration used by Spring Containers as a source of bean definitions.
 * @EnableAutoConfiguration : This makes the application to look for auto-configuration beans on its classpath and automatically applies them.
 * @ComponentScan : Used scan a package for beans.

 ### @Controller
 * The @Controller is a class-level annotation. It is a specialization of @Component. It marks a class as a web request handler.
 * Used to handle the view requests in reponse.

 ### @RestController
 * Class level annotation. It is a specialization of @Component. It marks a class as a web request handler.

 ### @Service
 * Class level annotation. It tells the Spring that class contains the business logic.

 ### @Repository
 * Class level annotation. The repository is a DAOs (Data Access Object) that access the database directly contains all the operations related to the database.

 ### @RequestMapping
 * It is used to map the web requests.



 
