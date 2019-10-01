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

3. [Introduction to REST Web Services](#3-introduction-to-rest-web-services)


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
2. **`Service Requestor`**: Requestor is consumer/client application that utilizes an existing web service by sending an XML request. The client application can be a .Net, Java, JavaScript or other language application which looks some sort of functionality via a web service
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
- What are different/various functionalities/return types/parameters with Web Service?
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




3 Introduction to REST Web Services
=====================
3 Introduction to REST API
=====================

