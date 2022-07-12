## Proyecto Microservicios Con Spring Boot.

### Arquitectura Microservicios con  Spring Boot 2, Eureka, Spring Cloud Gateway, LoadBalancer, Resilience4J, Rest, OAuth, Docker.
### Clemente Quintana Pozo.

* Registro y escalamiento dinámico con Eureka (servidor de nombres).
* Spring Cloud Gateway (puerta de enlace). [https://cloud.spring.io/spring-cloud-gateway/reference/html/]
* Balanceo de carga con Spring Cloud LoadBalancer y Ribbon.
* Resiliencia y Tolerancia a fallos con Hystrix -> Resilience4J. (Programacion funcional, Circuit Breaker) 
* Automatiza, escala y despliega en producción los microservicios en contenedores Docker.
* Spring Cloud Security (OAuth2 y JWT).
* Seguridad a Spring Cloud Gateway mediante el api JJWT.
* centralizar toda la configuración de los microservicios utilizando Spring Cloud Config Server-
* Trazabilidad distribuida con Spring Cloud Sleuth y Zipkin.
* Ecosistema Spring: IoC, Spring MVC, RestController, Servicios Web RESTful, cliente HTTP con RestTemplate y Feing, Spring Data JPA e Hibernate 	
	para la persistencia y CRUD, usaremos bases de datos MySQL 8 y PostgreSQL, 



- Arrancar Eureka Server : http://localhost:8761/
- Arrancar microservicios Productos y Items
- Arrancar Zuul o gateway: http://localhost:8090/api/items/