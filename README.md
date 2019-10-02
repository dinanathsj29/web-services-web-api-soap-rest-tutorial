Web Services-Web API Beginner Tutorial
=====================


Topics included/covered
=====================

1. [Introduction to Web Service](#1-introduction-to-web-service)
    - 1.1. [What is Web Service?](#11-what-is-web-service)
    - 1.2. [Advantages of Web Service](#12-advantages-of-web-service)
    - 1.3. [Web service Architecture](#13-web-service-architecture)
    - 1.4. [Web Service Features](#14-web-service-features)
    - 1.5. [How Web Service works?](#15-how-web-service-works)
    - 1.6. [Types of Web Services](#16-types-of-web-services)
    - 1.7. [Components of Web Services](#17-components-of-web-services)

2. [Introduction to SOAP Web Services](#2-introduction-to-soap-web-services)
    - 2.1. [What are SOAP Web Services?](#21-what-are-soap-web-services)
    - 2.2. [SOAP Web Services Specifications/standards](#22-soap-web-services-specifications/standards)
    - 2.3. [Disadvantages of SOAP Web Services](#23-disadvantages-of-soap-web-services)

3. [Introduction to REST Web Services](#3-introduction-to-rest-web-services)
    - 3.1. [What is REST API?](#31-what-is-rest-api)
    - 3.2. [What are RESTful Web Services?](#32-what-are-restful-web-services)
    - 3.3. [Principles of REST API](#33-principles-of-rest-api)
    - 3.4. [Features of REST API](#34-features-of-rest-api)
    - 3.5. [Method  s of REST API](#35-methods-of-rest-api)
    - 3.6. [Advantages of REST API](#36-advantages-of-rest-api)

4. [SOAP Vs REST](#4-soap-vs-rest)
    - 4.1. [SOAP vs REST Web Services](#41-soap-vs-rest-web-services)


1 Introduction to Web Service
=====================

1.1. What is Web Service?
---------------------

`Web Service is a standardized way or medium for communication` between client and server applications to exchange data on the World Wide Web

`Web Services provides a standard protocol/format` and helps to communicate between two different application and make sure all things happening smooth-proper and successful

`Web Services provide a common platform` that allows multiple applications built on various programming languages to communicate and have the ability to communicate with each other

- Scenario: Java programming language can interact with PHP/ASP and .Net, JavaScript by using Web Services

Example: 
> **`Hotel/Restaurant`**
  - The waiter is a mediator (Act as a Web Service/Bridge) between two application ie. customer and kitchen

> **`Flight Booking websites`**
  - All airlines companies (Air India, Indigo, Jet Airways) have exposed their Web Service through an API, 
  - All agents and different flight booking websites like makemytrip.com, cleartrip.com, etc. access an API and populate data/status accordingly


1.2. Advantages of Web Service
---------------------
1.2. Why Web Service
---------------------
1.2. Benefits of Web Service
---------------------

Here are some of the benefits and advantages of using Web Services:


- **`Platform independent communication`**: Web Service provides platform/Operating System independent communication
- **`Applications can Exchange Data`**: Through Web Services, different applications/implementations can talk to each other and exchange data/information
- **`Exposing Business Functionality`**/existing functions on the network so other applications can use the functionality of your program
- **`Interoperability`** amongst applications (Web services allow various applications to talk/share data and services among themselves)
- Web Services use **`standardized industry protocol`** for the communication which everybody understands
- **`Reduction in cost`** of communication/Low-Cost Communication


1.3. Web Service Architecture
---------------------

The Web Services architecture consists of three distinct roles as given below:

1. **`Service Provider`**: The provider creates/implements the Web Service and makes it available on the internet to other client application who want to use it
2. **`Service Requestor`**: Requestor is a consumer/client application that utilizes an existing web service by sending an XML request. The client application can be a .Net, Java, JavaScript or other language application which looks some sort of functionality via a web service
3. **`Service Registry/Broker`**: The registry is a logically centralized directory of services where developers can publish new services or find existing ones ( like centralized clearinghouse or brokerage house for companies and their services). The broker is an application provides access to the `UDDI (Universal Description, Discovery, and Integration)` which enables the client application to locate the web service


1.4. Web Service Features
---------------------
1.4. Web Service Characteristics
---------------------

Web Services must have the following special behavioral features/characteristics: 

- **`XML-Based`**: Web Services uses XML to represent the data
- **`Loosely Coupled`**: Client/Consumer and the web service are not fixed/bound/tied to each other directly
- **`Ability to  Synchronous or Asynchronous functionality`**: Synchronicity specifies the binding of the client to the execution of the function, Asynchronous clients fetch their result at a later point in time, while synchronous clients receive their effect when the service has completed
- **`Supports Remote Procedure Calls(RPCs)`**: Web services allow consumers to invoke procedures, functions, and methods on remote objects using an XML-based protocol. Remote systems expose input and output framework that a web service must support
- **`Supports Document Exchange`**: One of the essential benefits of XML is its generic way of representing not only data but also complex documents, it can be as simple as representing a current address, or they can be as complex as representing an entire book or Request for Quotation (RFQ)
- **`Coarse-Grained`**: Object-oriented technologies such as Java expose their functions through individual methods or coarse-grained services that approach the right amount of business logic


1.5. How Web Service works?
---------------------

<pre>
                  <strong>Client                          Server</strong>
                  sends REQUEST ->                <- gives RESPONSE
                  (Consume Services)              (Provide various services to use) 
                                [ ueses <strong>Medium</strong> - HTTP/INTERNET                 
                                <strong>Format</strong> - XML/JSON ]
</pre>

- The client program bundle information into a SOAP message which is sent to web service as the body of an HTTP POST request
- The web service unpacks the SOAP request and converts to a command that application can understand and gives a response with required data/information
- The web service packages response into another SOAP message and sends back to the client program 
- The client program unpacks the SOAP message and starts with the necessary process


1.6. Types of Web Services
---------------------
1.6. Popular Web Services
---------------------

There are mainly/major two ways of implementing Web Services, popular Web Services Protocols are:

1. **`SOAP Web Services`**: `(Simple Object Access Protocol)`: [ *Medium*: HTTP (post), *Format*: XML ]
2. **`REST Web Services`**: `(REpresentational State Transfer)`: [ *Medium*: HTTP (get, post, put, delete), *Format*: XML/JSON/Text ]


1.7. Components of Web Services
---------------------
1.7. Components of Web Services: SOAP, WSDL, and UDDI
---------------------

While using/consuming web services, Service Consumer (client) needs to know:
- What the Web Service is?
- What are the different services available?
- What are the various components of Web Service?
- What's the structure and description of Web Service?
- What are the different/various functionalities/return types/parameters with Web Service?
- What are the request and response parameters?
- How to call, use and consume the Web Service?

All the standard Web Services work using the following components:

1. **`SOAP (Simple Object Access Protocol)`**:
    - SOAP is a W3C recommendation for communication between applications and format for sending messages
    - SOAP is an XML-based protocol for accessing web services and for exchanging information between computers/applications
    - SOAP is simple and extensible also a platform, language-independent

2. **`WSDL (Web Services Description Language)`**:
    - WSDL is an XML-based language for describing web services and how to access them
    - It's an XML based interface for the Web Services which describe all the attributes and functionalities, method name/parameter of the Web Service published by all Service Providers
    - WSDL is the standard format for describing a web service which UDDI uses

3. **`UDDI (Universal Description, Discovery, and Integration)`**:
    - UDDI is an XML-based standard for describing, publishing, finding/discovering and integrating web services
    - A Web Service Provider publishes his Web Service through WSDL on an online directory/registry from where consumers can query and search the Web Services
    - UDDI is a platform-independent and open framework can communicate via SOAP, CORBA, and Java RMI Protocol


2 Introduction to SOAP Web Services
=====================

2.1. What are SOAP Web Services?
---------------------

- SOAP (Simple Object Access Protocol), a W3C recommendation for communication between two applications
- SOAP is an XML-based protocol for accessing web services over HTTP
- Any Web Service that complies and follows some guidelines which are led down by **SOAP Web Services specifications** is a SOAP Web Service


2.2. SOAP Web Services Specifications/standards
---------------------
2.2. SOAP Building blocks
---------------------

There are two categories of SOAP Web Services specifications: as Basic specification and Extended specification:
1. Basic
    - **SOAP**
      - Protocol / Rules / Definitions related to how two different applications will talk to each other over the web
      - All SOAP message/information exchange happens with the common format: XML
        - XML messages have a pre-defined structure as **SOAP MESSAGE** which consists of Envelope, Header, and Body
          - **Envelope** - root element of a message
          - **Header** - components, complex types, authentication parameters
          - **Body** - actual request to be sent to the server
    - **WSDL (Web Services Description Language)**
    - **UDDI (Universal Description, Discovery, and Integration)**
2. Extended
    - Web Services Security (WS-Security)
    - Web Services Policy (WS-Policy)

### Who defines Web Services Specifications/standards
W3C (World Wide Web Consortium) - [An International community that develops open standards for worldwide web] defines and dictates all standards for Web Services


2.3. Disadvantages of Soap Web Services
---------------------

- **Slow**: SOAP uses XML format, whose parsing is slow and consumes more bandwidth and resource
- **WSDL dependent**: SOAP uses WSDL and doesn't have other mechanisms to discover the service


3 Introduction to REST Web Services
=====================
3 Introduction to REST API
=====================

3.1. What is REST API?
---------------------
- REST (REpresentational State Transfer) 
- REST is an architectural style
  - REST is not a protocol, 
  - there are no strict specifications, 
  - no central body like W3C to control specifications
- REST is a design principle, one can use design principles/methods to create a service, which creates **RESTful Web Services**

REST is an architectural style as well as an approach for communications purpose that is often used in various web services development
  - Introduced by Roy Fielding in the year 2000
  - It is often regarded as the `"language of the internet"`
  - It is a stateless client and server model
  - REST is used to build Web Services that are lightweight, maintainable, and scalable


3.2. What are RESTful Web Services?
---------------------

Any Web Service that complies and follows some guidelines which are led down by **REST architecture/principles** is a called a RESTful Web Service [A service which is built on the REST architecture is called a RESTful service]


3.3. Principles of REST API
---------------------
3.3. RESTFul Principles and Constraints
---------------------

There are many principles/constraints of REST architecture a Web Service needs to follow to become/deemed as REST API / RESTful API-Web Service:
1. **Uniform Interface**: 
    - **Resource** - Everything is a resource
      - any platform, any Database, any language - we can create a module or resource for Students, Employees or anything
    - **URI** - Any resource/data can be accessed by a URI
      - URI = Uniform Resource Identifier
      - http://domain.name/resource
      - http://website.com/students
      - https://website.com/employee/id=100
    - **HTTP** - Make explicit use of HTTP methods
      - HTTP = HyperText Transfer Protocol
      - HTTP methods are: GET, POST, PUT, DELETE
      - Using HTTP methods along with URI, we can REQUEST and can access/modify any resource or resource information
2. **Client-Server**: 
    - Client & Server are separate identities, Clients send REQUEST and Server RESPONDS with headers, status or response body
3. **Stateless**: 
    - All client-server communications are stateless
    - In case of REST, the server does not maintain any state of the system and client has to send the request which is complete/proper in itself (every request will be independent and will not be dependent on any previous requests)
    - Each request from the client to the server - must contain all the data that is necessary to handle the request, no need to store any data on the server
    - A server should not require to store the state of a session
    - As the server does not store any old/past/unwanted data, it improves Web Service performance
4. **Cacheable**:
    - Caching happens at the client-side
    - The client uses the **Cache-Control** header to determine whether to cache the resource (make a local copy) or not
    - The server generates responses that indicate whether they are cacheable or not to improve the performance by reducing number of requests for duplicate resources [server does it with the help of **Cache-Control** and **Last-Modified (date value)**]
5. **Layered System**:
    - Multiple Layers can exist between client and server
    - Layers can include **Proxies**, **Gateways**, **Caching** they are HTTP intermediaries
    - Layers can be used for message translations / improving performance with caching etc.
    - Enables security, load-balancing and share caching to improve application performance
    - **Proxies** - Proxy server evaluates, control its complexity and simplify the request
    - **Gateways** - Used to manage traffic on the network, protocol translations, etc.
    - **Caching** - Improves performance and scalability
6. **Code On Demand**:
    - Ability to download and execute code on the client-side


3.4. Features of REST API
---------------------
- Simpler than SOAP API
- Proper Documentation available
- Throws/Log proper Error messages


3.5. Methods of REST API
---------------------

<pre>
- <strong>Creat</strong>        =   <strong>POST</strong> method
- <strong>Read</strong>         =   <strong>GET</strong> method  
- <strong>Update</strong>       =   <strong>PUT</strong> method
- <strong>Delete</strong>       =   <strong>DELETE</strong> method
</pre>

1. **`POST`** – Create a new data/info/record using the RESTful web service
2. **`GET`** - Get a list of all data/info/record
3. **`PUT`** - Update all data/info/record
4. **`DELETE`** - Delete all data/info/record


3.6. Advantages of REST API
---------------------

- **Fast**: Due to no strict specification like SOAP, REST consumes less bandwidth and resource
- **Language and Platform independent**: Can be written in any programming language and executed in any platform
- **Permits different data format**: Plain Text, HTML, XML and JSON
- **Can use SOAP**: RESTful web services can use SOAP API/web services as the implementation


4 SOAP Vs REST
=====================
4 SOAP Vs. REST: Difference between Web API Services
=====================


4.1. SOAP vs REST Web Services
---------------------

There are many differences between SOAP and REST web services, some important differences are given below:

| SOAP Web Services/API               | REST Web Services/API               |
| ------------------------------------| ----------------------------------- |
| SOAP stands for **`Simple Object Access Protocol`** | REST stands for **`REpresentational State Transfer`** |
| SOAP is a **`protocol`**            | REST is an **`architectural style`** |
| SOAP can't use REST because it is a protocol but REST is an architectural pattern                               | REST can use SOAP web services as it is an architectural pattern/concept and can use any protocol like HTTP, SOAP |
| SOAP uses **`service interfaces`** to expose the business logic | REST uses **`URI (URL path)`** to expose business logic |
| SOAP requires **`more bandwidth and resource`** than REST | REST requires **`less bandwidth and resource`** than SOAP |
| SOAP is **`slow`** as compared to REST | REST is **`fast`** as compared to SOAP |
| SOAP permits **`XML`** data format only | REST permits different data format such as **`Plain text, HTML, JSON, XML`** etc. |
| SOAP is **`less preferred`** than REST   | REST IS **`more preferred`** than SOAP |


