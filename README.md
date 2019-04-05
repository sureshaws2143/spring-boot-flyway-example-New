# spring-boot-flyway-example-New
spring-boot-flyway-example-New imported from 
Spring Boot Flyway Example
Learn how to integrate Flyway in your Spring Boot application -

https://www.callicoder.com/spring-boot-flyway-database-migration-example/

Requirements
Java - 1.8.x

Maven - 3.x.x

MySQL - 5.x.x

Steps to setup
1. Clone the application

git clone https://github.com/callicoder/spring-boot-flyway-example.git
2. Create Mysql database

create database flyway_demo
3. Change mysql username and password as per your installation

open src/main/resources/application.properties

change spring.datasource.username and spring.datasource.password as per your mysql installation

4. Build and run the app using maven

cd spring-boot-flyway-example
mvn package
java -jar target/flyway-demo-0.0.1-SNAPSHOT.jar
You can also run the app without packaging it using -

mvn spring-boot:run
