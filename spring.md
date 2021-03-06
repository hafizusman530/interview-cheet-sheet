
### Spring basic concepts
- Spring framework for dependency injection and autowiring and integration
- Spring Application context
- Spring beans; Objects that are managed by IOC
- EJB container vs Spring container

### Spring DI
- Use Qualifies for Autowiring by Abstract type (Generic type)
- Injecting list of beans by generic type

### Spring Boot
- Classes annotated with @Component @Controller @Service @Repository are candidate for auto detection
- Specialized version of annotation is used for layred the application into modular structure
- All specialized versions of annotations are treated @components while scan auto detection and auto wiring
- Spring Autoconfiguration (Provide configuration if jar found on class path)

### Spring MVC
1. Three Layers of MVC
- ***M***(odel). DAO, Classes annotated with `@Repository`
- ***V***(iew)
- ***C***(ontroller). REST end points, Classes anotated with `@Controller`.
- Service Layer, Classes annotated with `@Service`.

- DispatcherServlet ressolves the @Controller annotation by using handler mapping and route request to that server

### Spring Data
- @transactional

### Links
- https://docs.spring.io/spring/docs/current/spring-framework-reference/core.html#beans
