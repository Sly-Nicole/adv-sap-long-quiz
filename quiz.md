## Assignment in Advanced Systems Integration & Architecture

PALILLEO

1. Define Service Oriented Architecture(SOA).
   Service-oriented architecture (SOA) is a method of software development that uses software components called services to create business applications. Each service provides a business capability, and services can also communicate with each other across platforms and languages.

2. List and discuss the characteristics of SOA.
   a. Loose Coupling - it allows for flexibility and easier maintenance because in one service do not affect others. it also reduces dependecies between services.
   b. Interoperability - because SAO uses standards for communication, it ensures the smooth communication between different services. Integration of different kinds of systems and application is possible even thou they are built with different technologies.
   c. Reusability - It reduces redundancy and minimize operational costs to the enterprise, it also enchance consistency, and time.

3. Define Microservices.
   Microservices, also known as the microservices architecture, is an architectural style that structures a software application as a collection of small, independent, and loosely coupled services. Each microservice represents a specific business capability and runs as a separate process, communicating with other microservices through well-defined APIs (Application Programming Interfaces).

4. List and discuss the benefits of using Microservices.
   a. Scalability - Microservices has the ability to perform well based on the organizations need, it will be able to adapat even in increase demand overtime.
   b.Modularity and Flexibility - It allows for independent development, deployment, and scaling of individual services, making it resilient, with failures in one service not affectign the entrire system.
   c.Technology Diversity - It allows the use of different programming languages and technologies, giving the flexibility that promotes innovation.

5. List and discuss the similarities and differences of SOA and Microservices.

   Similarities

   1. Service-Oriented - Both SOA and microservices emphasize the use of services as essential building blocks, as their name implies they both offer services wether its small or huge.
   2. Reusability - They both encourage the reuse of services to improve efficiencvy and reduce redundancy
   3. Interoperability - They both ensures that services can work together seamlessly wether they are both created with the same technology or not.

   Difference

   1. Size and Score - As their Implies SOA tend to be larger and more comprehensive while on the otherhand Microservices focuses on components that represent specific business capabilities.
   2. Data Management - SOA relies of centralized data store, while microservices often have their own databases.
   3. Deployment - SOA is deployed as a whole or part of larger application while Microservices are independent deployable, allowing for granular releases.

6. Define Web Services - Web services are software systems designed to support interoperable machine-to-machine communication over a network. They provide a standardized way for different applications and systems to communicate and exchange data regardless of the programming languages, platforms, or technologies they are built on.

7. List and discuss the benefits of using Web Services.

   1. Interoperability: Regardless of the underlying technologies, web services provide seamless data sharing and communication between various applications and systems.

   2. Standardized Protocols: For client-server connection, web services frequently employ standard communication protocols like HTTP (Hypertext Transfer Protocol). Data sharing is frequently done via other protocols like REST (Representational State Transfer) and SOAP (Simple Object Access Protocol).

   3. Data Exchange Formats: Web services arrange and exchange data using standardized formats like JSON (JavaScript Object Notation) and XML (eXtensible Markup Language).

8. List and discuss the characteristics of Web Services.

   1. Flexibility - By distributing several instances among servers, web services can be horizontally scaled to meet growing demand.
      Scalability is crucial because it guarantees that web services can handle rising user counts or volumes of data without sacrificing efficiency.

   1. Service Breakdown - Higher-level services that provide more sophisticated functionality can be created by combining or composing web services.
      Significance: The construction of modular and reusable services is facilitated by service composition, which permits the production of applications with a wide range of complex functionalities.

9. List and discuss the distinct roles in Web Services Architecture.

   1. Lifecycle Management of Services - includes web service development, deployment, retirement, and planning.
      oversees all aspects of the service's lifespan, including versioning, deprecation, and updates.
      makes certain that services follow rules and are in line with corporate objectives.

   2. Manager of Service Security - puts in place and sustains web services security safeguards.
      oversees encryption, authorization, and authentication to safeguard information and guarantee the integrity of communication.
      guarantees adherence to security guidelines and regulations.

   3. Assurance of Service Quality (QA) - guarantees the dependability and quality of web services.
      tests the service to make sure it performs as promised in the contract.
      keeps an eye on the service's dependability, scalability, and performance.

10. List and discuss the Web Services Components.

11. Security Guidelines (such as WS-Security) - One of the most important aspects of web services is security. A set of guidelines for securing data flow and communication between web service providers and customers is defined by standards such as WS-Security. Features like digital signatures, encryption, and authentication are included in this.

12. Intermediary - Software that makes it easier for distributed systems to communicate and exchange data is known as middleware. To improve connectivity and communication, middleware in the context of web services may comprise elements like message queues, service buses, and other integration tools.

13. Service Termination - The URL or URI where a web service is hosted and accessible is known as the service endpoint. It acts as the point of contact between service users and the online service.
