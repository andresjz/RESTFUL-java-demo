RESTFUL EXAMPLE SPRING HIBERNATE MVC!
===================

This project cover the integration of several Frameworks to create a simple restful service that shows a data about statistics of PISAMATHEMATICS over 20 countries during the last 20 years. The full demo is available on https://iwa-demo.herokuapp.com/

----------
Dependencies
-------------

> **Frameworks and dependencies:**

> - **Spring** It is useful for mapping the views, it allows to create applications in MVC model.
> - **Hibernate** This framework allows connect the Database write in `MySQL`, `Postgress`, `SQL` and implement all methods necessary for establish and easy connections with the DataBase and the Application.
> - **REST-assured** For testting purposes 
> -  **AngularJS** A Javascript Framework for develoment in the client-side very useful and customizable.
> - **AWS** (*Optional)* Amazon Web Services, Create a virtual machine, configure and start a instance with mySQL using remote connection.
> - **Heroku** (*Optional)* Is a platform where I uploaded the project, it accepts to deploy a `.WAR` or `.JAR` package.
> - **Bootstrap** A styling Framework written in `js`. and  `css`
> - **D3** A javascript library for charting

Structure project
-------------
The current project has been developed with Maven in Netbeans, so it creates a basic project with all necessary elements to working in web. I customized some of that project including addtional folder an files that allows to work with Spring and Hibernate.

The final estructure looks like:
```
project
?   README.md
?   pom.xml
|   nb-configuration.xml    
?
????src
?   ?
?   ????main
?   ?   ?
?   ?   ????java
?   ?   ?   ?
?   ?   ?   ????Controller
?   ?   ?   ?	 	MathematicsController.java
?   ?   ?   ? 		MathematicsControllerRest.java
?   ?   ?   ?
?   ?   ?   ????Dao
?   ?   ?   ?		MathematicsDAO.java
?   ?   ?   ?		MathematicsDAOImpl.java
?   ?   ?   ?
?   ?   ?   ????Model
?   ?   ?   ?		Mathematics.java
?   ?   ?   ?
?   ?   ?   ????Service
?   ?   ?   		MathematicsService.java
?   ?   ?   		MathematicsServiceImpl.java
?   ?   ?   
?   ?   ????resources
?   ?   ?
?   ?   ?
?   ?   ????webapp
?   ?          spring-servlet.xml 
?   ?          web.xml
?   ?          ?
?   ? 	       ????WEB-INF
?   ?				home.jsp
?   ?				form.jsp
?   ?				pages/
?   ?				pages/assets		
?   ?				... plugins etc.
?   ?
?   ????test
?       ?
?       ????java
?	      controllerTest.java     
?      
????target
         spring2.war
        ... *other files generated by netbeans
```

