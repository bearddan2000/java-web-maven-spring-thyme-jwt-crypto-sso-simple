# java-web-maven-spring-thyme-jwt-crypto-sso-simple

## Description
A springboot secure web app with thymeleaf support.
This is a POC for single sign on JSON protected web app.
JWT only validates it doesn't authenticate so any
user or account # will work.

## Tech stack
- java
- maven

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- Available at http://localhost
  - Service Provider Url: http://localhost:81
    - only available with valid token
  - User: John Doe
  - Account number: 123-456-789

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- https://dzone.com/articles/securing-spring-boot-microservices-with-json-web-t
