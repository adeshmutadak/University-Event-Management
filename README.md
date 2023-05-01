# University-Event-Management

 👤University-Event-Management</h1>

>### Framework Used 
 * ![SpringBoot](https://img.shields.io/badge/SpringBoot-White?style=flat&logoColor=Blue)

>### Language Used
* ![Java](https://img.shields.io/badge/Java-White?style=flat&logoColor=Blue)
>## Data flow
In this project, we have four layers-
* **Controller** - The controller layer handles the HTTP requests, translates the JSON parameter to object, and authenticates the request and transfer it to the business (service) layer.
* **Service** -The business layer handles all the business logic. It consists of service classes and uses services provided by data access layers.
* **Repository** - This layer mainatains the h2-database thing on which CRUD operations are performed
* **Model** - This layer consists basically the class level things- the various classes required for the project and these classes consists the attributes to be stored.

>## Data Structure used in my project
This document outlines the steps to create a  University-Event-Management
 model will have-
* IStudentId
* first name
* last name
* age
* department

Also we use H2 database

>## Project Summary
This project contains variou crud operations using inbuilt @CrudRepo methods ,custom get methods using our own custom finders (No implementations, correct queries should be fired based on method names) and write operations (update and delete) using Custom queries (using @Query) 
