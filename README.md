# Зміст

### 1. Мова Java та основи програмування

- [ООП (класи, об'єкти, наслідування, поліморфізм, інкапсуляція)](01-java-basics/oop.md/#зміст)
- [Java Core (типи даних, оператори, цикли, винятки)](01-java-basics/java-core-types-operators-loops-exceptions.md/#зміст)
- [Java 8–21 (лямбди, Stream API, Optional, записи, switch expressions тощо)](01-java-basics/java8-21-lambdas-streams-optional-records-switch.md/#зміст)
- [Java Collections Framework](01-java-basics/java-collections-framework.md/#зміст)
- [Generics](01-java-basics/generics.md/#зміст)
- [Enum'и, аннотації](01-java-basics/enums-annotations.md/#зміст)
- [Модифікатори доступу](01-java-basics/access-modifiers.md/#зміст)
- [String API, регулярні вирази](01-java-basics/string-api-regular-expressions.md/#зміст)

### 2. Платформа Java та виконання

- [JVM (структура, стек, heap, garbage collection)](02-jvm-runtime/jvm-structure-stack-heap-garbage-collection.md/#зміст)
- [ClassLoader'и](02-jvm-runtime/classloaders.md/#зміст)
- [JIT компіляція](02-jvm-runtime/jit-compilation.md/#зміст)
- [Сборка сміття (GC tuning)](02-jvm-runtime/gc-tuning.md/#зміст)
- [Сериалізація](02-jvm-runtime/serialization.md/#зміст)
- [Java Memory Model](02-jvm-runtime/java-memory-model.md/#зміст)

### 3. Concurrency & Multithreading

- [Thread, Runnable, Callable, Future](03-concurrency-multithreading/thread-runnable-callable-future.md/#зміст)
- [synchronized, volatile, wait/notify](03-concurrency-multithreading/synchronized-volatile-wait-notify.md/#зміст)
- [ExecutorService, ForkJoinPool](03-concurrency-multithreading/executorservice-forkjoinpool.md/#зміст)
- [java.util.concurrent API](03-concurrency-multithreading/java-util-concurrent-api.md/#зміст)
- [Проблеми: race condition, deadlock, starvation](03-concurrency-multithreading/concurrency-issues-race-deadlock-starvation.md/#зміст)
- [Механізми синхронізації](03-concurrency-multithreading/synchronization-mechanisms.md/#зміст)

### 4. Ввід/вивід та робота з файлами

- [Streams (FileInputStream, BufferedReader тощо)](04-io-and-files/streams-fileinputstream-bufferedreader.md/#зміст)
- [NIO, NIO.2 (Path, Files, Channels)](04-io-and-files/nio-nio2-path-files-channels.md/#зміст)

### 5. Реактивне програмування

- [Основи (observer pattern, push vs pull)](05-reactive-programming/reactive-programming-observer-push-pull.md/#зміст)
- [RxJava, Project Reactor](05-reactive-programming/rxjava-project-reactor.md/#зміст)
- [Підходи до обробки подій](05-reactive-programming/event-processing-approaches.md/#зміст)

### 6. Бази даних

*(Теми без файлів — додати при потребі)*

### 7. Тестування

- [Unit testing: JUnit, TestNG](06-testing/unit-testing-junit-testng.md/#зміст)
- [Mocking: Mockito](06-testing/mocking-mockito.md/#зміст)
- [Інтеграційне тестування](06-testing/integration-testing.md/#зміст)
- [TDD, BDD](06-testing/tdd-bdd.md/#зміст)

### 8. Логування та відлагодження

- [Log4j / SLF4J / java.util.logging](07-logging-debugging/logging-log4j-slf4j-java-util-logging.md/#зміст)
- [Аналіз логів, логування рівнів](07-logging-debugging/log-analysis-levels.md/#зміст)
- [Відлагодження в IDE](07-logging-debugging/debugging-in-ide.md/#зміст)

### 9. Веб-програмування

- [HTTP, Cookies, Sessions](08-web-development/http-cookies-sessions.md/#зміст)
- [Servlets, JSP, JSTL](08-web-development/servlets-jsp-jstl.md/#зміст)
- [HTML/CSS базові знання](08-web-development/html-css-basics.md/#зміст)
- [REST API: створення, versioning, статус-коди](08-web-development/rest-api-creation-versioning-status-codes.md/#зміст)

### 10. Spring Framework

- [Spring Core (DI, IoC)](09-spring-framework/spring-core-di-ioc.md/#зміст)
- [Spring Boot (auto-configuration, starter'и)](09-spring-framework/spring-boot-auto-configuration-starters.md/#зміст)
- [Spring MVC (REST API)](09-spring-framework/spring-mvc-rest-api.md/#зміст)
- [Spring Data JPA](09-spring-framework/spring-data-jpa.md/#зміст)
- [Spring Security](09-spring-framework/spring-security.md/#зміст)
- [Spring AOP](09-spring-framework/spring-aop.md/#зміст)

### 11. Мікросервіси та інтеграція

- [Основи мікросервісної архітектури](10-microservices-integration/microservices-architecture.md/#зміст)
- [REST/gRPC](10-microservices-integration/rest-grpc.md/#зміст)
- [Apache Kafka / RabbitMQ](10-microservices-integration/apache-kafka-rabbitmq.md/#зміст)
- [API Gateway, Service Registry (Eureka, Consul)](10-microservices-integration/api-gateway-service-registry.md/#зміст)

### 12. Cloud, CI/CD, DevOps

- [Docker, Kubernetes](11-cloud-ci-cd-devops/docker-kubernetes.md/#зміст)
- [Maven / Gradle](11-cloud-ci-cd-devops/maven-gradle.md/#зміст)
- [Jenkins / GitHub Actions](11-cloud-ci-cd-devops/jenkins-github-actions.md/#зміст)
- [Deployment pipelines](11-cloud-ci-cd-devops/deployment-pipelines.md/#зміст)
- [Cloud basics (AWS, GCP, Azure)](11-cloud-ci-cd-devops/cloud-basics-aws-gcp-azure.md/#зміст)

### 13. Архітектура та патерни

- [Design Patterns (GoF)](12-architecture-patterns/design-patterns-gof.md/#зміст)
- [SOLID, GRASP](12-architecture-patterns/solid-grasp.md/#зміст)
- [Clean Architecture / Hexagonal](12-architecture-patterns/clean-architecture-hexagonal.md/#зміст)
- [DTO, DAO, Service layers](12-architecture-patterns/dto-dao-service-layers.md/#зміст)
- [UML (класів, послідовності, компонентів)](12-architecture-patterns/uml-classes-sequence-components.md/#зміст)

### 14. Інструменти та екосистема

- [IDE (IntelliJ IDEA, Eclipse)](13-tools-ecosystem/ide-intellij-eclipse.md/#зміст)
- [Git / GitHub](13-tools-ecosystem/git-github.md/#зміст)
- [Maven / Gradle](13-tools-ecosystem/maven-gradle-tools.md/#зміст)
- [SonarQube, Checkstyle](13-tools-ecosystem/sonarqube-checkstyle.md/#зміст)

### 15. Додаткові теми

- [XML / JSON](14-advanced-topics/xml-json.md/#зміст)
- [Reflection API](14-advanced-topics/reflection-api.md/#зміст)
- [Annotation processing](14-advanced-topics/annotation-processing.md/#зміст)
- [Java Native Interface (JNI)](14-advanced-topics/java-native-interface-jni.md/#зміст)
- [Performance tuning](14-advanced-topics/performance-tuning.md/#зміст)
- [Soft skills: code review, співпраця, менторство](14-advanced-topics/soft-skills-code-review-collaboration-mentoring.md/#зміст)
