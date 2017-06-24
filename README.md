# BasicSpringRESTAPI
A basic Hello World REST API made with Spring Boot and Maven.

## To Run:
In a terminal, run ```mvn compile``` to build the project, and ```java -jar target/gs-rest-service-0.1.0.jar``` to run the server.
Then, open a browser and go to ```localhost:8080/greeting``` to recieve a "Hello World!" JSON object.
Optionally, including a query string with a "name" value will personalize the message. E.g.: ```localhost:8080/greeting?name=Joe``` returns a JSON with "Hello Joe!".
