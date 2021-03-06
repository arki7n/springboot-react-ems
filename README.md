# Installation Guide

Demo

<img width="1727" alt="image" src="https://user-images.githubusercontent.com/6889484/178104302-b2c47e55-ac41-46c0-9cb8-25d2f497fa36.png">


## Frontend
```
npm install
npm run start
```

## Backend

Maven CLI Guide: 
- https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html
- https://www.sohamkamani.com/java/cli-app-with-maven/

Setup Database credentials at: 
- springboot-backend/src/main/resources --> application.properties

- Do notice datasource url containing database name. Do create blank DB in mysql first)

```
spring.datasource.url=jdbc:mysql://localhost:3306/employee_management_system?useSSL=false
spring.datasource.username=root
spring.datasource.password=
spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL5InnoDBDialect
spring.jpa.hibernate.ddl-auto = update
```

### Setup Project using CLI
```
mvn clean install
mvn clean compile package
java -jar target/springboot-backend-0.0.1-SNAPSHOT.jar
```

### Setup Project using UI
- Right click on Project Icon-> Run-> Maven Install
- Right click on Project Icon-> Run--> Run as Springboot App

## Postman Tutorial
- https://www.youtube.com/watch?v=FjgYtQK_zLE
- Detailed at https://learning.postman.com/docs/getting-started/introduction/

## Git Cli Tutorial
- https://dev.to/unseenwizzard/learn-git-concepts-not-commands-4gjc
- https://education.github.com/git-cheat-sheet-education.pdf
- https://github.com/mobify/branching-strategy

## Online API Specification Design
- https://stoplight.io/
- https://swagger.io/tools/
- What is OpenAPI Specification https://dev.to/nathan20/a-brief-introduction-to-openapi-specification-4mgd
- REST API Design https://dev.to/blindkai/rest-api-design-27j9

## Chrome Browser DevTools Cheatsheet
- https://umaar.com/dev-tips/

## JavaScript toolings
- https://ageek.dev/js-tooling

## React Guide
- https://beta.reactjs.org/
- React Hooks https://blog.logrocket.com/guide-to-react-useeffect-hook/

## Java Springboot Resources
- https://github.com/gindex/spring-boot-annotation-list
- https://chenweixiang.github.io/docs/Spring_Annotations_cheat_sheet.pdf
- https://lightrun.com/java/the-complete-list-of-spring-boot-annotations-you-must-know/
- https://howtodoinjava.com/spring-core/spring-bean-life-cycle/
- https://medium.com/swlh/the-lifecycle-of-spring-beans-b0edb8936189
- Java Design Pattern https://github.com/fengjundev/Java-Design-Patterns

## Clean Code
- Java https://github.com/leonardolemie/clean-code-java
- Java https://github.com/in28minutes/clean-code/blob/master/presentation.pdf
- General https://gist.github.com/wojteklu/73c6914cc446146b8b533c0988cf8d29
- JavaScript https://github.com/ryanmcdermott/clean-code-javascript

## JavaScript
- Learn to use Promises, Async await, Closure concept, Array methods, Object methods, String methods

## Different Types of Authentication
- https://dev.to/caffiendkitten/authentication-types-3984
- https://betterprogramming.pub/how-do-you-authenticate-mate-f2b70904cc3a
- https://www.freecodecamp.org/news/everything-you-need-to-know-about-cookies-for-web-development/
- https://dev.to/carstenbehrens/the-basics-of-jwt-json-web-tokens-for-dummies-2iin
- Browser CORS polciy https://dev.to/lydiahallie/cs-visualized-cors-5b8h
- Java Auth Tutorial https://www.freecodecamp.org/news/how-to-setup-jwt-authorization-and-authentication-in-spring/

- https://www.bezkoder.com/spring-boot-jwt-authentication/
- https://www.techgeeknext.com/spring/spring-boot-security-token-authentication-jwt
- https://medium.com/javarevisited/springboot-security-with-jwt-fca1446790ba
- https://www.toptal.com/spring/spring-security-tutorial

## Springboot REST API Guide
- https://spring.io/guides/tutorials/rest/
- https://hevodata.com/learn/spring-boot-rest-api/
- https://www.twilio.com/blog/create-rest-apis-java-spring-boot
- https://javatechonline.com/spring-boot-mvc-rest-annotations-with-examples/

## Java Loggingg/Debugging
- https://www.baeldung.com/spring-boot-logging
- https://sematext.com/blog/log4j-tutorial/
- Eclipse Guide https://rollbar.com/blog/how-to-debug-java-code-faster-with-eclipse/

## Java Springboot with AWS SDK integration
- https://spring.io/blog/2021/03/17/spring-cloud-aws-2-3-is-now-available
- https://aws.amazon.com/sdk-for-java/

## Spring JPA ORM guide
- https://dev.to/brunodrugowick/querying-your-spring-data-jpa-repository-introduction-4ani
- https://www.baeldung.com/the-persistence-layer-with-spring-data-jpa
- https://www.javaguides.net/p/spring-data-jpa-tutorial.html

-----------

# ReactJS-Spring-Boot-CRUD-Full-Stack-App - Course on YouTube

#### ReactJS + Spring Boot CRUD Full Stack App - 1 - Project Overview
=> https://youtu.be/n43h1eJ2EUE

#### ReactJS + Spring Boot CRUD Full Stack App - 2 - Project Architecture and Development Process
=> https://youtu.be/iK__liBIXWk
#### ReactJS + Spring Boot CRUD Full Stack App - 3 - Create Spring Boot Project and Configure MySQL
=> https://youtu.be/k5KnAhkRzh4
#### ReactJS + Spring Boot CRUD Full Stack App - 4 - Creating JPA Entity + Repository
=> https://youtu.be/FZwLlaMmers
#### ReactJS + Spring Boot CRUD Full Stack App - 5 - Creating List Employee REST API
=> https://youtu.be/L57OlxU0fEE
#### ReactJS + Spring Boot CRUD Full Stack App - 6 - Creating React App
=> https://youtu.be/tUXiPfNKUWE
#### ReactJS + Spring Boot CRUD Full Stack App - 7 - Add Bootstrap 4 in React App
=> https://youtu.be/ArxBR9C1oNA
#### ReactJS + Spring Boot CRUD Full Stack App - 8 - Creating React List Employee Component
=> https://youtu.be/Tpt9t5IV7Vw
#### ReactJS + Spring Boot CRUD Full Stack App - 9 - Connecting React with List Employee REST API
=> https://youtu.be/zXE7dCidXhc
#### ReactJS + Spring Boot CRUD Full Stack App - 10 - Add Header and Footer to React App
=> https://youtu.be/LOcy9uFzBBU
#### ReactJS + Spring Boot CRUD Full Stack App - 11 - Configure Routing
=> https://youtu.be/z2QAbWy1A40
#### ReactJS + Spring Boot CRUD Full Stack App - 12 - Creating Add Employee REST API
=> https://youtu.be/1y3pOPNrGms
#### ReactJS + Spring Boot CRUD Full Stack App - 13 - Creating React Add Employee Component
=> https://youtu.be/E_7uVf0RCl4
#### ReactJS + Spring Boot CRUD Full Stack App - 14 - React Add Employee Form Handling
=> https://youtu.be/S5AFJIfRxQU
#### ReactJS + Spring Boot CRUD Full Stack App - 15 - Connecting React with Add Employee REST API
=> https://youtu.be/ieMhlyjPjWo
#### ReactJS + Spring Boot CRUD Full Stack App - 16 - Creating Get Employee By Id REST API
=> https://youtu.be/L5SYbfkOTQA
#### ReactJS + Spring Boot CRUD Full Stack App - 17 - Creating Update Employee REST API
=> https://youtu.be/voJAjtioNN8
#### ReactJS + Spring Boot CRUD Full Stack App - 18 - Creating React Update Employee
=> https://youtu.be/GrIG4-lnLkQ
#### ReactJS + Spring Boot CRUD Full Stack App - 19 - Connecting React with Update Employee REST API
=> https://youtu.be/uPCWBOrU6Vs
#### ReactJS + Spring Boot CRUD Full Stack App - 20 - Add & Update Employee with Single React Component 
=> https://youtu.be/ksvDBGF7JRE
#### ReactJS + Spring Boot CRUD Full Stack App - 21 - Creating Delete Employee REST API 
=> https://youtu.be/dzgixz4X1KA
#### ReactJS + Spring Boot CRUD Full Stack App - 22 - Connecting React with Delete Employee REST API
=> https://youtu.be/L6wM7x0fqZs
#### ReactJS + Spring Boot CRUD Full Stack App - 23 - Creating React View Employee Component
=> https://youtu.be/XRWnM51Cd7o
#### ReactJS + Spring Boot CRUD Full Stack App - 24 - Design and Show Data on View Employee Page
=> https://youtu.be/XRWnM51Cd7o
#### ReactJS + Spring Boot CRUD Full Stack App - 25 - It's Demo Time and Source Code on GitHub
=> https://youtu.be/FX5HE_gnOTI
