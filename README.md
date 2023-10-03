# Spring Security Login System Tutorial Code

Java application code for a Spring Boot 3+, Spring Data JPA, Spring Security, Spring Web, and OAuth2Resource server application which allows users to login or register using HTTP POST requests, then view endpoints based on their roles.

Users are authenticated against a database using a custom `UserDetailsService` and `AuthenticationManager` along with Spring Data JPA repositories.

When a successful login occurs, a JWT is generated and sent back to the user, the user can use this JWT in the header as a bearer token to access authenticated routes according to their roles

[Follow the youtube tutorial here]()

****************************************************************
Register
![imagen](https://github.com/csgutierm/spring-security-login-system/assets/90303345/e60a9bf5-9e80-4d8a-9a44-d1870c39b4e5)

Login give a jwt to allow access in other endpoints
![imagen](https://github.com/csgutierm/spring-security-login-system/assets/90303345/4ac0cca9-692c-423f-8329-71b60529ff37)

Enter your pass, user and your jwt

![imagen](https://github.com/csgutierm/spring-security-login-system/assets/90303345/add6189c-491c-408f-a011-ba0efef93eaf)

Key: Authorization
Value: Bearer <jwt>  --you need only one space between Bearer and your jwt
![imagen](https://github.com/csgutierm/spring-security-login-system/assets/90303345/c928fcee-5ed2-4f81-9c09-91f9f4397019)


