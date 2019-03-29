Todo App

This snapshot is contains the actual java code for RESTFUL APIs.
This is written in Java/Springboot and using gradle build
The backend connected is MongoDb with the following properties:
spring.data.mongodb.host=localhost
spring.data.mongodb.port=27017
spring.data.mongodb.database=tododb

To execute this app please run as Spring boot or Java application.

http://localhost:8080/notes
http://localhost:8080/todo/{_id}