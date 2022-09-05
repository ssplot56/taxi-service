# 🚕 Taxi service 🚕
![](https://t4.ftcdn.net/jpg/03/14/92/29/360_F_314922983_mdsn0ZPqCSWbuDQBfsV3mjhsGrCyGDas.jpg)

### Project description:
> This web application is an implementation of a simple taxi service. 
> The app allows you to work with the database directly through your browser. 
> Create and manage your own set of cars, add drivers and manufacturers!  
> 
> Add, change and delete data in just one click!

### Features: 
> Various CRUD operations such as:
* create/update/delete a car;
* create/update/delete a manufacturer;
* create/update/delete a driver;
* display list of manufacturers/drivers/cars;
* add driver to car / remove driver from car;
> The possibility to register as a driver and then be authenticated in service
> Provided logout

### Structure:
> The project consists of three layers:
* Controller - provides for the processing of user requests;
* DAO - provides a database operation;
* Service - includes all the application logic;

### Application was built with:
* Java 11;
* JDBC;
* Apache Maven 3.8.6 
* Apache Tomcat 9.0.65;
* MySQL;

### How to launch project:
> It is required to have JDK, MySQL, Apache Maven & Tomcat (v. 9.0.65)
1. Clone this project.
2. You need to create schema in the database, for this you can use sql-script init_db.sql in resources folder.
3. Configure the connection (enter your data in the ConnectionUtil class).
4. Run Tomcat.