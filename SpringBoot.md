# Spring Boot


## What's an MVC?
A design pattern in SE

## What's MVC Used for?
to separate an application into three interconnected components: Model, View Controller
What does each component do?
Model - data and business logic 
view - displays data to user  (UI)
controller - handles user input, manages model -> view relationship and interactions (Middle-Man)

## What's an API? 
a set of protocols, tools and standards
What are API's used for?
building software applications that allows different software components to interact with each other. (Software Interaction/Interoparability) 
### How are API's used?
API'S can be used to expose the functionality of the model component of an MVC application to other applications or systems. This allows us to build new aplications that can interact with existing app data nd business logic without having to recreate those components. (DRY)

### Example:
An E-commerce website might use an MVC architecture to separate it's products catalog and shopping cart functionality into separate components.
The Website's mobile app could utilize an API to access the product catalog and shopping cart functionality and bring it down into the app without having to create those components.
So in essence, the mobile app and website have the same functionality while keeping code (DRY).


## API'S IN -DEPTHH 

### What is an API?
application programming interface
It is a set of protocols and standards for building and integrating application software

### How do API's work?
they let your product or service communicate with other products or services using abstraction.

### What are the benefits of API usage?
simplify app development, save time and money, flexibility, 
Simplify design, administration and use.
Collaboration between business and IT Teams

### What Are API's sometoimes thought of?
Contracts, with documentation that represents an agreement between parties.

### What are the benefits of Public API's
They represent a unique business value because they simplify and expand how you connect with your partners, as well as offer a way to monetize your data.
Create new revenue channels
Expand reach
Facilitate open innovation

### What are the three API release policies?
Private, Partner and Public

### What do they mean?
- Private - API is only for internal use.
- Partner - API is shared with specific business partners / revenue streams
- Public - API is available to everyone, allows third party collaboration using API to innovate.


### History of APIs?
API used to be libraries for operating systems


### What are Remote API's
designed to interact through a communications network
What does remote mean? resources are being manipulated by the API are somewhere outside the computer.
Are all remote API's, web APIs?
No, not all but it's fair to assume that web APIs are remote.

### Which protocol is typically used by API's?
HTTP for request messages, and provide a definition of the structure of response messages.
What file format is the response in? XML or JSON
Why is this the preferred format? they present data in a way that's easy for other apps to manipulate

 
## SOAP vs REST

### What is SOAP? 
Simple Object Access Protcol
API's designed with SOAP use XML for message format and receive request through HTTP or SMTP.
What's the benefit of SOAP? makes it easier for apps running in different envs or written in diff langauges to share information.

### What is REST?
 Representational State Transfer

### What are these API's called that adhere to REST architecturural constraints? 
RESTful APIs

### How does REST differ from SOAP? 
SOAP is a protocol, REST is an architectural Style.

### Is there an official standard for RESTful web APIs? 
NO.

### What makes an API RESTful?
- complyihng with 6 guiding constraints/rules:
- Client-Server Architecture
- Statelessness 
- Cacheability
- Layered System
- Code on Demand (Optional) 
- Uniform Interface
    Resource Identification in requests
    Resource manipulation through representations
    Self-Descriptive messages
    Hypermedia as the engine of application state



jPa lets us read and write data regardless of database 


Lab / HW 
https://git.generalassemb.ly/java-interapt-3-13-2023/spring-boot-todo-lab#3a

Sprint RestAPI Crud Spread 
https://docs.google.com/spreadsheets/d/1rhc1kTmxgIwPBJIoh8aiPJ69CgF-TpOXLsGFDCp7tiU/edit#gid=0

RESTFUL JSON API with Java Spring Boot 
https://git.generalassemb.ly/sureshmelvinsigera/Java-Spring-Boot-lecture/tree/spring-2-7-8#day02

What are APIs 
https://www.redhat.com/en/topics/api/what-are-application-programming-interfaces



