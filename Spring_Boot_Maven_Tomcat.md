

# SPRING BOOT DEVELOPMENT ENVIRONMENT 
###################################
Google: Web Server Software 



### What is Tomcat? 
a web server, allows us to deploy and run Java web apps.

### Where can we use Tomcat? 
within IntelliJ IDE

### Install and Configure Tomcat
- Download and install Tomcat from the Apache website.
- In IntelliJ, go to the "Run" menu and select "Edit Configurations".
- Click the "+" icon in the top left corner and select "Tomcat Server" -> "Local".
- In the "Server" tab, specify the Tomcat installation directory and the server port number.
- In the "Deployment" tab, select the web application you want to deploy to Tomcat.
- Click "OK" to save the configuration.

# Maven

### What is Maven? 
a Build automation tool, helps manage java project dependencies and build process


### Configure Maven in IntelliJ 
- In IntelliJ, go to "File" -> "New" -> "Project".
- Select "Maven" as the project type and click "Next".
- Specify the project details, such as group ID, artifact ID, and version.
- In the "Project SDK" dropdown, select the Java SDK you want to use for the project.
- Click "Next" and specify the project template you want to use.
- Click "Finish" to create the Maven project.

- THEN, add dependencies to your project's pom.xml file and use Maven to manage your project's build process.


## What is Postman?
API Testing and development tool
allows us to test API Endpoints.

### Configure: 
- In IntelliJ, go to "File" -> "Settings" -> "Plugins".
- Search for the Postman plugin and install it.
- Restart IntelliJ to activate the plugin.
- Open Postman and generate an API key to use in the plugin.
- In IntelliJ, go to "File" -> "Settings" -> "Tools" -> "Postman".
- Enter the API key and configure the Postman settings as desired.


### What is NPM? 
Package Manager 


## COMMON QUESTIONS

### What is Tomcat and how does it work? 
Explain the basic architecture of Tomcat.
Open source web server and servlet container that allows you to deploy and run java web applications

#### How does it work? 
it accepts http request from clients and forwards them to the appropriate web app.

#### How would you break down the architecture? 
- The basic architecture consist of  three main components: the Connector, the Container, and teh Catalina.
- The Connector, accepts and processes incoming client request
- THe Container manages the lifecycle of the web app and HANDLES the requests.
- The Catalina provides additional functionality, such as security and session management.

### How do you add dependencies in maven to a project?
use the pom.xml file to add the dependency info with a <dependency> tag.

### How do you deploy a java web app to Tomcat?
- Build app as WAR file using Maven.
- Maven is a build tool
- Copy WAR file to "webapps" directory in Tomcat installation directory
- Restart Tomcat Server.

### What config files do you need to modify to configure tomcat for your app?
- Modify server.xml and web.xml config files.
- Server.xml contains settings for the server such as port number and security settings.
- web.xml contains settings for web app, such as servlet mappings and security constraints.

### How do You troubleshoot erroes in Tomcat web app?
- check the Tomcat Logs for errors and stack traces
- Try to Reproduce Locally
- Use Debugging Tools like breakpoints to isolate the issue
- Review the Code

### What's a common error in Tomcat or other servers?
HTTP status 404 error
This indicates that the requested resources was not found

### How would you resolve this error?
- Verify app is deployed to Tomcat Server and WAR file is located in correct directory
- Check web.xml to ensure servlet mappings and URL patterns are configed correctly.
- check server.sml to ensure that the context path and URL mappings are configed correctly.
- Verify that the requested resources exists and is accessible.



## SPRING
- Spring is owned by VMWare.

### What is Spring? 
Makes programming Java Easier, building enterprise applications

### What are the benefits of using Spring? 
Spring is secure and Supported by a Strong Community.

### What is a Web framework?
 A combination of Coding Tools and Software to make the web app development process streamlined and more efficient.

### What is a web framework? In detail?
A web framework is a software tool that provides developers with a set of libraries, tools, and conventions to build web applications more efficiently. 

### What do web frameworks consist of?
Web frameworks typically include features such as request routing, templating, session management, database integration, and security, among others. 

### How does it help?  
By providing a set of standardized components and structures, web frameworks enable developers to focus on building the unique business logic of their web application, without worrying about the underlying infrastructure and mechanics of the web.

## What is another benefit of this? 
The use of a web framework can significantly reduce development time, improve code quality, and increase the maintainability and scalability of a web application.

Provide some example frameworks:  Some examples of popular web frameworks include Django for Python, Ruby on Rails for Ruby, and Spring for Java

### Sprint init settings:
2.7.11
Maven
Java
.jar file is standard
Java 17


Built my First SpringBoot Project Today
https://start.spring.io/

What is the default server that Springboot comes with?
Apache Tomcat

Three Server Env: Dev Database, Staging Database, Production Database
User Profiles: application.properties is the default profile 
application-dev.properties
application-dev1.properties(staging)
application-prod.properties


PostGres runs on 5432.
Spring boot runs on 8080.



## RESOURCES 
## MVC Framework Intro 
https://www.geeksforgeeks.org/mvc-framework-introduction/#

### Init Spring Projects 
https://start.spring.io/
https://spring.io/

### Spring Overview
https://git.generalassemb.ly/java-interapt-3-13-2023/Spring-Overview

### Sprint Boot Dev Env 
https://git.generalassemb.ly/java-interapt-3-13-2023/Setting-up-your-Dev-Environment/blob/master/README.md

### MVC Design Pattern 
https://git.generalassemb.ly/java-interapt-3-13-2023/spring-ecosystem/blob/master/spring-design-patterns/mvc-design-pattern.md

### Restful JSON API with Java Spring Boot 
https://git.generalassemb.ly/sureshmelvinsigera/Java-Spring-Boot-lecture/tree/spring-2-7-8


