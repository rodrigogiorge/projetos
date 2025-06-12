# HelloWorld API

Simple Spring Boot API running on Java 21. Provides `/hello` endpoint returning
`helloworld` string. It includes Swagger UI via `springdoc-openapi` and adds the
JDBI dependency for future database integration.

## Build

```bash
mvn package
```

## Run

```bash
mvn spring-boot:run
```

Swagger UI will be available at `http://localhost:8080/swagger-ui.html` once the
application is running.
