## Spring Boot Annotations

 
 ### @SpringBootApplication
 * Used to identify the main class of a Spring Boot application.
 * It Consits of 3 Other Annotation @Configuration, @EnableAutoConfiguration, and @ComponentScan
 * @Configuration : The class annotated with @Configuration used by Spring Containers as a source of bean definitions.
 * @EnableAutoConfiguration : This makes the application to look for auto-configuration beans on its classpath and automatically applies them.
 * @ComponentScan : Used scan a package for beans.

 ### @Controller
 * The @Controller is a class-level annotation. It is a specialization of @Component. It marks a class as a web request handler.
 * Used to handle the view requests in reponse.

 ### @RestController
 * Class level annotation. It is a specialization of @Component. It is the combination of @Controller and @ResponseBody.

 ### @Service
 * Class level annotation. It tells the Spring that class contains the business logic.

 ### @Repository
 * Class level annotation. The repository is a DAOs (Data Access Object) that access the database directly contains all the operations related to the database.

 ### @RequestMapping
 * It is used to map the web requests.

 ### @GetMapping
 *  It maps the HTTP GET requests on the specific handler method used to create a web service endpoint that fetches.

 ### @PostMapping
 *  It maps the HTTP POST requests on the specific handler method used to create a web service endpoint that creates a new entry.

 ### @PutMapping
 * It maps the HTTP PUT requests on the specific handler method used to create a web service endpoint that updates.

 ### @DeleteMapping
 * It maps the HTTP DELETE requests on the specific handler method used to create a web service endpoint that deletes a resource.

 ### @RequestBody
 * It is used to bind HTTP request with an object in a method parameter.

 ### @ResponseBody
 * It binds the method return value to the response body. Tells the application to return an object in JSON or XML format.
