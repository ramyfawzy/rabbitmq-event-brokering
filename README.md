# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.1.8.RELEASE/maven-plugin/)


mvn -X spring-boot:run -Dspring-boot.run.arguments=--spring.profiles.active=subscriber,--subscriber.queue=service1Queue,--subscriber.routingKey=customer.*


mvn -X spring-boot:run -Dspring-boot.run.arguments=--spring.profiles.active=subscriber,--subscriber.queue=service2Queue,--subscriber.routingKey=*.created


mvn -X spring-boot:run -Dspring-boot.run.arguments=--spring.profiles.active=publisher
