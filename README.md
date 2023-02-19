# Account management application
An account management application that supports 

- The creation of new account
- Deposit
- Transaction log and
- Withdrawal


## Tech stack/framework used

- Springboot 2.7.5
- JDK 1.8
- Maven
- Nodejs
- Concurrent Hashmap for storage - This is an enhanced haspmap with thread safety.
- Docker

##Design
-The application is loosely coupled with the backend running on an embedded Tomcat server
while the front end runs on node. This loose coupling means that the backend can easily be 
integrated into any client 

-The backend is a RESTful service 

## Step-By-Step guide to setup project on local system
--clone the project
--start your docker Engine
--run the following command from the root folder:
docker-compose up --build


Hope this was helpful to get you started

[Abel Agbachi](https://github.com/Abelinho/accountManagementService.git) © 2022 