# ***Cinema-app*** 🎥
### This is simple simulator of cinema service for reservation tickets, that support registration, authentication and CRUD operations.📽️
___
### **`Features:`**
```
- Register or login as user.
- Find users by email.
- Add and find movies.
- Create, update and find available movie sessions.
- Create shopping carts and get shopping carts by user.
- Add tickets to shopping cart.
- Add new cinema halls and find cinema-halls.
- Add new orders and see order history.
```
___
### **`Project structure:`**
```
├───.idea
│   └───codeStyles
└───src
    ├───main
    │   ├───java
    │   │   └───cinema
    │   │       ├───config
    │   │       ├───controller
    │   │       ├───dao
    │   │       │   └───impl
    │   │       ├───dto
    │   │       │   ├───request
    │   │       │   └───response
    │   │       ├───exception
    │   │       ├───lib
    │   │       ├───model
    │   │       ├───service
    │   │       │   ├───impl
    │   │       │   └───mapper
    │   │       └───util
    │   └───resources
```
___
### **`Used tecnologies:`**

+ Java 18;
+ Spring;
+ Hibernate;
+ Junit;
+ Javax servlet;
+ MySQL;
+ Apache Tomcat;
+ Apache Maven;
___
### **`How to start project locally:`**
+ In the **`resources/db.properties`** change properties to your own.
- ![img_1.png](img_1.png)
+ Install and configure **Tomcat 9.0.50**(use war exploded deployment). If you decide to install version 10 and above, you should use a different dependency for servlets and JSTL as well.
+ ![img_2.png](img_2.png)
+ Use **`mvn clean package`** to build the project, and to check if everything correct.
+ ![img_3.png](img_3.png)
+ Run the project, application will automatically open in browser.
