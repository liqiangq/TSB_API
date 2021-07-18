# TSB_API
Implement Java Spring Boot microservice to provide an API interface to a vehicle listing resource.


Details
•	Implement a REST resource for a vehicle listing (create, update, delete, get and find/search).
•	The vehicle listing resource should contain the following properties: 
o	Registration (mandatory)
o	Year
o	Make
o	Model
o	Colour 
o	Price
•	Find/search endpoint should filter on all properties; make price a searchable range.
•	Add appropriate security over the endpoints.
•	Create an in-memory database to store the vehicle listing resources, alternatively you can integrate into the TradeMe API at https://developer.trademe.co.nz/.
•	Include Open API/Swagger.
•	Demonstrate how you would implement testing for this API, including integration testing.
•	Demonstrate how you would manage CI/CD and running in different environments and other operational support aspects such as logging.


----------------------------------------------------------
Tools and Technologies Used:
Spring Boot
JDK- 11
Spring Framework
Spring-search
JPA
Maven
IDE-Eclipse 
H2 Embedded Database

URL:
1. GET     /Vehicles
2. Post    /Vehicle
3. POST   /vehicles
4. GET     /vehicles/{id}
5. PUT     /vehicles/{id}
6. Delete /vehicles/{id}
7. GET   /vehicles/search?search=param:value 




  
  
 

