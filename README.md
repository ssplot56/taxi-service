# 🚕 Taxi service 🚕
![](https://t4.ftcdn.net/jpg/03/14/92/29/360_F_314922983_mdsn0ZPqCSWbuDQBfsV3mjhsGrCyGDas.jpg)

### Project description:
> This web application is an implementation of a simple taxi service.

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

### How to launch project:
> It is required to have JDK, MySQL, Apache Maven & Tomcat (v. 9.0.65)
1. Clone this project.
2. You need to create schema in the database, for this you can use sql-script init_db.sql in resources folder.
3. Configure the connection (enter your data in the ConnectionUtil class).
4. Run Tomcat.