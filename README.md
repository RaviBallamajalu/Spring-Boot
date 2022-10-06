# Spring-Boot


### What is Spring Boot ? Why ?
* Spring Boot project is built on the Spring Framework.
* It provides an easier and faster way to set up, configure, and run both simple and web-based applications.
* Used to create a stand-alone application.
* It Consists of embedded server which is tomcat by default. If required the changes can be done using the dependency added in pom.
* It Uses convention over configuration. 


* Sample Program 
```java
package com.example.demo;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

@SpringBootApplication
public class DemoApplication {

	public static void main(String[] args) {
		SpringApplication.run(DemoApplication.class, args);
	}

}

```
