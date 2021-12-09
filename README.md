## This is a working example accompanying the blog post "Testing Optimistic Locking Handling with Spring Boot and JPA"

### Intro
This SpringBoot maven project is part of a [blog post](https://blog.mimacom.com/testing-optimistic-locking-handling-spring-boot-jpa/) where you could find not only explanation for it, but also theoretical background for:
- What does optimistic locking handling mean
- How you could implement it within a Spring Boot Application and JPA
- How you could write integration tests for handling optimistic locking.

### Prerequisites
- JDK8+.

### Docker

```bash
docker run --name postgres-demo -e POSTGRES_PASSWORD=root -p 5432:5432 -d postgres:11
```

### Run optimistic locking integration test
- Just execute "./mvnw clean verify".

Have fun and do not hesitate to contact me if you have any questions or suggestions!
