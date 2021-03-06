# **🚖Taxi service🚖**

### Project's description:

This is a simple web-application which was created as educational project, built using SOLID principles,
and it has to show the work with Database, Servlets and basic code architecture.

The following features are implemented here:
* Create new Driver
* Create new Car
* Create new Manufacturer
* Display All Drivers
* Display All Cars
* Display All Manufacturers
* Add Driver to Car
* Delete Driver from Car
* Delete Driver
* Delete Car
* Delete Manufacturer
* Display User's Current Cars

### This project consists of 3 Architecture layers:
1. Presentation tier(Controller)
2. Application tier(Service)
3. Data tier(Dao)

### Project's structure:
* **_Controller_** - contains HttpServlets and is responsible for handling requests and responses;
* **_WebFilter_** - contains filter, which is responsible for authorisation;
* **_Service_** - contains all business logic of the application;
* **_Lib_** - contains Injector and annotations to achieve dependency injection;
* **_Exception_** - contains custom exceptions;
* **_Model_** - contains entities which we operate during application usage;
* **_Util_** - contains ConnectionUtil which is responsible for connection with Database;
* **_Dao_** - contains dao classes and interfaces which are responsible to interact with Database;

### Test-drive 
If you want to try this application click [here](https://mk-taxi-service.herokuapp.com/index)

### Database structure
![](join-db-diagram.png)


### Technologies used in project
* Java 11
* Apache tomcat v.9.0.64
* MySQL
* JDBC
* Servlet
* JSTL
* JSP
* HTML, CSS

### If you want to run project on your computer
* Install MySQL and Apache Tomcat v 9.0.64
* Configure Apache Tomcat and MySQL
* For creating schema use /resources/init_db.sql
* Set URL, USERNAME, PASSWORD, JDBC_DRIVER in /util/ConnectionUtil.java
* Configure Tomcat library path in Edit configurations

