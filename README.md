Spring Boot with Integration sample using Java DSL
=========================================


To Use 
=========================================

To use this project , do these 3 steps

1. Make sure the POJO structure aligns with your REST API . Example shown is using REST API with following structure

{
  "firstName": "Jason",
  "lastName": "Bourne",
  "phone": "000-000-000",
  "email": "secret@gmail.com"
}

2. Update URL in the integration.xml to the right REST API

You can download the rest api producer used in the example @ 
https://github.com/arun2dot0/simple-rest-service

3. Build the Project using the following command


    $ mvn clean install
    
    

Execute
=========================================    
run App or as String boot project

    $ mvn spring-boot:run

Test
=========================================   

http://localhost:9000/person 

will call the api from http://localhost:8080/person 


