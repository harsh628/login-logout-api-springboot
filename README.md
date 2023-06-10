## Run Spring Boot application
```
mvn spring-boot:run
```

Let’s check H2 database with url: http://localhost:8080/h2-ui



## Run following SQL insert statements
```
INSERT INTO roles(name) VALUES('ROLE_USER');
INSERT INTO roles(name) VALUES('ROLE_MODERATOR');
INSERT INTO roles(name) VALUES('ROLE_ADMIN');
```


Register some users with /signup API:

admin with ROLE_ADMIN
mod with ROLE_MODERATOR and ROLE_USER
zkoder with ROLE_USER


Login an account: POST /api/auth/signin


Access ROLE_USER and ROLE_MODERATOR resource:
– GET /api/test/user
– GET /api/test/mod

Logout the Account: POST /api/auth/signout
