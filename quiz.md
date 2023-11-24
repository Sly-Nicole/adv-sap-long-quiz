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

6. Define Web Services

   - Web services are software systems designed to support interoperable machine-to-machine communication over a network. They provide a standardized way for different applications and systems to communicate and exchange data regardless of the programming languages, platforms, or technologies they are built on.

7. List and discuss the benefits of using Web Services.

   1. Interoperability: Regardless of the underlying technologies, web services provide seamless data sharing and communication between various applications and systems.

   2. Standardized Protocols: For client-server connection, web services frequently employ standard communication protocols like HTTP (Hypertext Transfer Protocol). Data sharing is frequently done via other protocols like REST (Representational State Transfer) and SOAP (Simple Object Access Protocol).

   3. Low Costg Communication: Web services use SOAP over HTTP because, that provides a standardized protocol for communication. it makes use of the existing infrastructure of the internet making it a cost effective choice fro communication.

8. List and discuss the characteristics of Web Services.

   1. XML-Based - XML-based characteristic of web services is foundational for achieving interoperability, platform independence, and standardization in the exchange of data between distributed systems. It serves as a universal language for communication, enabling diverse applications and services to work together seamlessly.

   2. Loosely Coupled - In a loosely coupled system, the client and web service have a flexible connection, allowing the web service interface to evolve independently. In contrast, tightly coupled systems bind client and server logic closely, necessitating updates in one when the other changes.

   3. Coarse-Grained - In Java, services use distinct methods for enterprise-level operations. Adopting a coarse-grained approach is recommended, encapsulating significant functionality in interfaces. Web services simplify this process, defining services with the right business logic.

   4. Ability to be Synchronous or Asynchronous - Synchronicity in service invocation determines how tightly the client is bound to the service execution. In synchronous scenarios, the client pauses, awaiting the service to finish before proceeding. Conversely, asynchronous operations enable the client to invoke a service and continue with other tasks. Asynchronous clients retrieve results later, while synchronous clients get results upon the service's completion. Asynchronous capability is vital for fostering loosely coupled systems.

   5. Enables Remote Procedure Calls (RPCs) -Web services empower clients to trigger processes on distant objects through a protocol grounded in XML. These remote procedures outline the necessary input and output parameters, creating a conduit for effective communication between clients and remote entities.

   6. Supports Document Exchange - XML's versatility extends beyond data representation to encompass complex document structures. These documents range from simple ones, such as current addresses, to intricate ones, like complete books or Request for Quotation (RFQ). Web services seamlessly enable the transparent exchange of such documents, promoting effective business integration.

9. List and discuss the distinct roles in Web Services Architecture.

   1. Provider - The provider creates and offers a web service, developing functionalities, specifying protocols, and hosting it on a server. They provide a clear service description, including endpoint and security details.

   2. Requestor - The requestor, a client app in languages like .Net or Java, communicates with a web service to access specific functionalities, serving its functional needs.

   3. Broker - The broker, within web services architecture, functions as the application that facilitates access to UDDI (Universal Description, Discovery, and Integration).

   4. Publish - Providers inform the service registry (broker) about the web service via the broker's publish interface, making services accessible to clients and simplifying discovery and integration.

   5. Find - The requestor checks with the broker to discover a published web service.

   6. Bind - Using the information acquired from the broker (service registry) about the web service, the requestor can establish a connection and invoke the desired functionality.

10. List and discuss the Web Services Components.

SOAP (Simple Object Access Protocol)

- SOAP is an OS-agnostic, XML-based communication protocol. It facilitates seamless information exchange between applications, operating independently of platforms and languages. By defining how to encode HTTP headers and XML files, SOAP ensures effective communication while supporting server firewalls for enhanced security.

WSDL (Web Services Description Language)

- WSDL is an XML-based language designed for describing and accessing web services. As a crucial component of UDDI, it enables businesses to list themselves and their services on the internet. Functioning as a navigation tool, WSDL guides individuals and other businesses in accessing these services. This language, written in XML, plays an integral role in the standardized description and accessibility of web services.

UDDI (Universal Description, Discovery, and Integration)

- UDDI is an XML-based standard for describing, publishing, and discovering web services. As a vital component in the trio of foundational web service standards with SOAP and WSDL, UDDI utilizes WSDL to detail web service interfaces. This open, platform-independent framework acts as a distributed registry, enhancing the visibility and accessibility of web services.
