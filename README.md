## Run Spring Boot application
```
mvn spring-boot:run
```

Let’s check H2 database with url: http://localhost:8080/h2-ui



## Run following SQL insert statements
```
INSERT INTO roles(name) VALUES('USER');
```


Register some users with /signup API:
 USER



Login an account: POST /api/auth/signin


Access USER  resource:
– GET /api/test/user


Logout the Account: POST /api/auth/signout
