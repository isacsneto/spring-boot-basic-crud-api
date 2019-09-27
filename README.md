# spring-boot-basic-crud-api
A basic crud api system with spring boot.

This app was made with spring boot, its a basic crud for persons, where you can add, update, get and delete persons.
If you want to add just use the POST route with the json body {"name":"Alex Turner"} for example.

Routes: 
1. POST addPerson - http://localhost:8080/api/v1/person
2. GET getPerson - http://localhost:8080/api/v1/person
3. GET getPersonById - http://localhost:8080/api/v1/person/{id}
4. PUT updatePerson - http://localhost:8080/api/v1/person/{id}
5. DELETE deletePerson - http://localhost:8080/api/v1/person/{id}

You can run it locally with "mvn clean install" and then "java -jar demo-0.0.1-SNAPSHOT.jar" 
