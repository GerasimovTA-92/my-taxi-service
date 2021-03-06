# **Taxi Service**

![img.png](src/main/resources/taxi.png)

## **Contents**

1. [Description](#Description)
2. [Features](#Features)
3. [Project structure](#Project-structure)
4. [Technologies](#Technologies)
5. [How to run project](#How-to-run-project)
____

## **Description**

This is simple implementation of taxi app

[:arrow_up:Contents](#Contents)
____

## **Features**

* registration like a driver;
* authentication like a driver;
* create/update/remove a manufacturer;
* create/update/remove a car;
* create/update/remove a driver;
* display list of all manufacturers;
* display list of all drivers;
* display list of all cars
* display list of all cars for authentication driver;
* remove/add driver to car;

[:arrow_up:Contents](#Contents)
____

## **Project structure**

### Project built on 3-tier architecture:
1. Data access layer (DAO).
2. Application layer (service).
3. Presentation layer (controllers).

Tables relation:
![img_1.png](src/main/resources/tables_relation.png)

[:arrow_up:Contents](#Contents)
____

## **Technologies**

* Apache Tomcat (v9.0.50);
* MySQL;
* JDBC;
* Servlet;
* JSP, JSTL;
* HTML, CSS;
* Maven;
* Maven Checkstyle Plugin;

[:arrow_up:Contents](#Contents)
____

## **How to run project**

### Tools to run project:
* IntelliJ Idea Ultimate
* Apache Tomcat (v9.0.50)
* MySQL

`Warning!!!` If you want to create own database, please, use this [script](src/main/resources/init_db.sql) and add your url to DB, login, password and JDBC driver [here](src/main/java/taxi/util/ConnectionUtil.java)!

1. Clone this project on your IDE
2. Add Tomcat to Configurations
3. Configure log4j2.xml from resources directory. Add correct absolute path to the app.log file

[:arrow_up:Contents](#Contents)
____
