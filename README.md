# Flight_Booking_System
A Java based web application built using Spring boot. Users can book a flight, search, view their bookings,modify, delete, update their profile. Admins can add a flight , view all bookings made by users , delete a flight. URL's are secured based on roles (admin or users) using Spring Security. Passwords are Encrypted using BCRYPT Encryption.

## Tech Stack

* Java
* Spring Framework
* Spring Boot
* Spring Data JPA
* Spring Security
* Hibernate
* Thymeleaf
* Maven
* MySQL Database
* Lombok
* Html , css
* Bootstrap

## Modules

* Login Module
* User Module
* Admin Module
* Reservation Module

## Features

* User and Admin authentication & validation with Spring Security.
* Restricted URL's based on roles (user or admin).
* Passwords are encrypted and stored in MySQL database using BCrypt Encryption.
* Hibernate ORM is used to interact with database.
* Admin Features:
    * Administrator Role of the entire application
    * Only registered admins with valid session can add/view/update/delete Flights from main database
    * Admin can view all the bookings made by users.
* User Features:
    * A user can register on the platform.
    * Users can search for flights based on date.
    * Users can book flight if available.
    * Users can modify a reservation or delete the reservation made by him.    


## Installation & Run
### Prerequisites:
* Java 17 or higher.
* IDE.
* Lombok installed in IDE.
* MySQL database.

### How to Run:

* Before running the Application, you should update the database config inside the [application.properties](https://github.com/Pramod082002/Flight_Booking_System/blob/main/src/main/resources/application.properties) file. 
* Update the port number, username and password as per your local database config.
* Create a Database using MySQL workbench.

```
    server.port=8080

    spring.datasource.url=jdbc:mysql://localhost:3306/{Your_database_name};
    spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
    spring.datasource.username={Your_username}
    spring.datasource.password={Your_Password}

```
* Open the main class and run as Java application from your IDE.




