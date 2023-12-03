## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
SOA is a software development method that uses existing components or services that can be reused for different applications. It also allows different systems or applications to communicate with each other through a common interface.
It is a software development that is scalable for big companies. For code reusability.
2. List and discuss the characteristics of SOA.
Standardized Service Contracts - This is a rule we follow when we design services so that they can work well with other services in the same inventory. The contracts also tell us what the service can do and what it expects from us.

Loose Coupling - This is a way of making services independent from each other, so that they can change without affecting the users who depend on them.

Abstraction - This is a way of hiding the technical details of a service and focusing on the business process it supports. This makes the service more flexible and adaptable.

Reusability - This is a way of avoiding duplication and waste by using existing services whenever possible, or creating new services that can be used for multiple purposes.

Autonomy - This is a way of giving services the power and control to make their own decisions, without needing approval or interference from others.

Statelessness - This is a way of reducing the amount of information a service needs to remember or store, so that it can perform better and faster.

Discoverability - This is a way of making services easy to find and understand by providing metadata that describes their purpose and capabilities to humans and systems.

Composability - This is a way of solving complex problems by breaking them down into smaller and simpler parts, and using services to combine them.

Interoperability - This is a way of making services compatible and able to share data with each other, by following common standards and protocols.

3. Define Microservices.
Microservices are similar to SOA, but they are used to create applications that can grow and recover more easily. They are like building blocks that can be arranged in different ways to form larger applications. Microservices are small, independent components that work together through a common interface.


4. List and discuss the benefits of using Microservices.

Independently deployable - This is the main feature of microservices, which means that each service can be deployed separately without affecting the others. The services are small and communicate with each other through networks, and this gives us more options to solve the problems we encounter.

Right tool for job - This is one of the advantages of using microservices, which allows us to use the best tool for each task. Microservices can store and process more data by breaking it into smaller pieces, and each service can use its own language and framework to communicate with the application we want.

Precise Scaling - With microservices, we can deploy and scale each service individually and precisely. This means that we can handle a large number of tasks at the same time, and do it efficiently and accurately.

5. List and discuss the similarities and differences of SOA and Microservices.

Similarities Reuse - Both SOA and Microservices try to avoid creating new services when there are existing ones that can be reused. SOA searches for available services, while Microservices copy and paste code and accept data duplication.

Synchronous calls - Both SOA and Microservices use synchronous protocols to make their services available across the enterprise. However, Microservices only use synchronous calls when they need to wait for another service’s response before proceeding.

Data duplication - Both SOA and Microservices consist of collections of services that perform specific functions. They also have to deal with complex data synchronization patterns because of data duplication.

Differences between SOA and Microservices

Communication - SOA uses an Enterprise Service Bus (ESB) to handle communication between services, but this can be a single point of failure for the whole enterprise if one service slows down. Microservices use simpler messaging systems like APIs that enable faster communication and are developed independently with their own communication protocols.

Interoperability - SOA sets standards for services to share data and ensure that they don’t get reduced. Interoperability means the ability of different software programs to exchange data. Microservices are also able to exchange and use information across systems, but they have more flexibility and autonomy.

Service granularity - Microservices have very specialized services that do one thing only, while SOA services can vary from small and specialized to enterprise-wide and general.

Speed - SOA simplifies development and troubleshooting, but it also makes SOA operate more slowly than Microservices. Microservices allow developers to work on small and independent parts of an application that can be quickly deployed and tested without affecting the rest of the application.

6. Define Web Services
This refers to a software system that has the ability to interact and exchange information with other software systems, or operate across a network.

7. List and discuss the benefits of using Web Services 
Network Functionality Exposure: This allows users to utilize functions of existing code over the network. It also enables other applications to leverage the functionality of your program.

Interoperability: This is the capacity of a system or application to exchange data securely and automatically. Without interoperability, systems are unable to interpret or use data to achieve common objectives.

Standardized Protocol: Web Services use a standardized protocol, which is a set of rules and guidelines that dictate how different software systems can communicate with each other over a network. The focus of web services is on the protocol, not the implementations.

Low-Cost Communication: Web services use SOAP, a lightweight protocol for creating web APIs and exchanging structured information, making it a cost-effective solution for implementing web services over the internet.

8. List and discuss the characteristics of Web Services 
XML, or Extensible Markup Language, is a type of markup language that encodes documents in a format that is accessible and readable to both humans and machines.

The term “loosely coupled” refers to the level of dependency between various components of a system. A web service can evolve over time without requiring the client to adjust their interaction with the service.

Coarse-Grained web services are Java services that are exposed through individual methods. These services are designed to offer a wider range of functionality compared to their fine-grained counterparts.

Web services can operate in both synchronous and asynchronous modes. For instance, in a synchronous mode, the client waits for the server to return a response, allowing the client application to track the status of the web service’s execution. In an asynchronous mode, the client can invoke a service and allow it to execute its function independently.

Web services support Remote Procedure Calls (RPCs), which enable a program to call procedures and functions on remote objects. RPCs are typically synchronous, meaning the client must wait for a response after making a request.

Web services facilitate document exchange by using XML to represent data in a generic manner. This allows applications to share and collaborate on data, thereby enhancing data integration.

9. List and discuss the distinct roles in Web Services Architecture
The provider is responsible for creating the web service and making it accessible to the client application that wishes to utilize it.

The requestor can be a web browser or a client application that initiates a service request.

The broker is an application that provides access to UDDI, enabling the client application to connect to the web service.

The publish function informs the service registry or broker about the activities occurring within the web service using the service registry’s publish interface.

The find function involves the service requester querying the service registry to determine the location of the service provided by the service provider.

The bind function involves a collection of service providers and requestors, including the service access path, calling parameters, transport protocol, and security requirements.

10. List and discuss the web services components
In the context of web services, SOAP stands for Simple Object Access Protocol. It utilizes XML as a payload or request body, with all requests and responses being transported via XML. It is both platform and language independent.

WSDL, or Web Services Description Language, plays a crucial role in web services as it specifies the location of the web service for request pick-up. It also serves as a guide for individuals and businesses to access the service.

UDDI, which stands for Universal Description Discovery and Integration, is provided by the service provider in web services. It uses WSDL to describe the interface to web services.
