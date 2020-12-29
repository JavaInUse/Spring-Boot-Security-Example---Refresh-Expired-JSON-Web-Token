# Spring-Boot-Security-Example---Refresh-Expired-JSON-Web-Token

In previous tutorial we had implemented [Spring Boot + JWT Example](https://www.javainuse.com/webseries/spring-security-jwt/chap4). We had also covered the topic of JWT Expiration. We had implemented the solution such that if the JWT has expired then the user gets JWTExpiredException.
Suppose our requirement is such that if the token has expired, still the user should be allowed to access the system if the token is valid. That is the token should be refreshed or a new valid token should be provided.
We will be working on a solution where if the user he receives JWT expired exception, then he can call another API with the expired token. A new token will then provided to the user which he can use for future interactions. Previously [we had implemented an example for programmatically consuming the JWT secure API using Spring RestTemplate](https://www.javainuse.com/webseries/spring-security-jwt/chap6).

 We will be testing this refresh Token generation API both using Postman as well as the Spring RestTemplate.


This tutorial is explained in the below Youtube Video.<br>


[![Watch the video](https://www.javainuse.com/spring.token-min.jpg)](https://youtu.be/O9jhPB-zTc8)
