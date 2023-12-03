## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).

Using software components known as services to build business applications is known as service-oriented architecture, or SOA. Every service offers a certain business function, and they can converse with one another in multiple languages and platforms.

2. List and discuss the characteristics of SOA.

Standardized Service Contract: Services adhere to a service-description. A service needs to have some information that defines what the service is about.
Loose Coupling: Services minimize dependencies on each other. So if the service functionality breaks at several points in time, this should not crush the client application or stop it from running.
Service Abstraction: Services wrap the logic they encapsulate from the unknown external world. The service shouldn't show how it performs its functionality.
Service Reusability: Logic is divided into services to maximize re-use.
Service Autonomy: Services must control the logic they encapsulate.
Service Statelessness: Services should stay stateless. This determines that services should not keep data from one state to the other. This would be required to be done from each client application.
Service Discoverability: Services can be discovered (usually in a service registry). We have previously viewed this in the theory of the UDDI, which performs a registry which can contain information about the web service.
Service Composability: It breaks large problems into tiny problems.
Service Interoperability: Services should use standards that provide different supporters to use the service. This is examined so obviously these days that it is frequently dropped as a principle.

3. Define Microservices.

The microservice architecture enables an organization to deliver large, complex applications rapidly, frequently, reliably and sustainably - a necessity for competing and winning in today’s world.

4. List and discuss the benefits of using Microservices.

Improved Productivity- Breaking an application down into smaller autonomous fragments makes it easier to build and maintain. Each service can be developed, deployed, and managed independently, and can utilize different programming languages, different technology, and different software environments based on the needs of each. 
Better Resiliency - Implementing microservice-based architecture adds ease to the process of  identifying and resolving the root cause of performance issues. The improved fault isolation offered by individual modules means larger applications remain unaffected by a single failure.
Increase Scalability - The fact that each service can be written in a different language or technology allows DevOps teams to choose the most appropriate tech stack for each module without concerns about incompatibility. 

5. List and discuss the similarities and differences of SOA and Microservices.

SOA is not dynamic and cannot fit for different purposes. They must be adapted or redeveloped every time a critical architecture piece of the involved technology changes. On the contrary, microservices try to be more independent by building on standardized interfaces that are valid across different technologies. However, there are often different standards, which can in the end lead to the same challenge that SOA has.
SOA typically shares fundamental components across different services. On the contrary, microservices usually have everything they need within the service, duplicated in every single microservice. Microservices are hence a bit slower, but less dependent on underlying services in order to work.

6. Define Web Services.

Web services are a type of internet software that use standardized messaging protocols and are made available from an application service provider's web server for use by a client or other web-based programs.
Web services can range from major services such as storage management or customer relationship management (CRM) down to much more limited services such as the furnishing of a stock quote or the checking of bids for an auction item. The term is sometimes also referred to as application services.
Users can access some web services through a peer-to-peer arrangement rather than by going to a central server. Some services can communicate with other services. This exchange of procedures and data is generally enabled by a class of software known as middleware.

7. List and discuss the benefits of using Web Services.

Revealing the Existing Function on Framework

A web administration is a managed code that can be remotely called using HTTP; it tends to be started using HTTP inquiries. Web administrations empower you to uncover the handiness of your present code over the framework. At the point when it is uncovered on the framework, other applications can use the handiness of your program.

Interoperability

Web service interoperability objectives are to give consistent and programmed associations starting with one programming application and then onto the next. Cleanser, WSDL, and UDDI conventions characterize a self-depicting approach to finding and calling a product application strategy – paying little mind to area or stage. The system marshals the information into XML request and response documents and transfers them between software packages using HTTP or message-based protocols. Interoperability issues creep in at the disclosure, definition, and solicitation/reaction instruments.

Ordered Protocol

Web administrations use the institutionalized industry-standard show for correspondence. All four layers (Service Transport, XML Messaging, Service Description, and Service Discovery layers) use well-described displays in the web organizations’ show stack. This systematization of the show stack gives the business various focal points, for instance, a wide extent of choices, a decline in the cost due to contention, and augmentation in the quality.

8. List and discuss the characteristics of Web Services.

Web services are self-contained
On the client side, no additional software is required. A programming language with XML and HTTP client support is enough to get you started. On the server side, you only require an HTTP server and a SOAP server.

Web services are self-describing
A web Service Description Language (WSDL) file provides all of the information you need to implement a web service as a provider or to invoke a web service as a requester.

Web services can be published, located, and invoked across the web
This service requester uses established light-weight Internet Standards such as HTTP to invoke the service provider. It leverages the existing infrastructure.

Web services are modular
Simple web services can be aggregated to form more complex ones, either using workflow techniques or by calling lower-layer web services from a web service implementation. Web services can be chained together to perform higher-level business functions. This shortens development time and enables best-of-breed implementations.

Web services are language independent and interoperable
The client and server can be implemented in different environments. Any language can be used to implement web service clients and servers.

Web services are inherently open and standards-based
XML and HTTP are the major technical foundations for web services. A large part of the web service technology has been built using open-source projects.

Hence, vendor independence and interoperability are realistic goals.

Web services are loosely coupled
A service requester needs to know the interface to a web service but not the details of how it has been implemented.

Web services provide programmatic access
This approach provides no graphical user interface; it operates at the code level.

Web services provide the ability to wrap existing applications.
Existing applications can be integrated easily into the service-oriented architecture by implementing the web service as an interface to the application.

9. List and discuss the distinct roles in Web Services Architecture.

Provider - The provider creates the web service and makes it available to client applications who want to use it.

Requestor - A requestor is nothing but the client application that needs to contact a web service. The client application can be a .Net, Java, or any other language-based application which looks for some sort of functionality via a web service.

Broker - The broker is nothing but the application which provides access to the UDDI. 

Publish - A provider informs the broker (service registry) about the existence of the web service by using the broker's publish interface to make the service accessible to clients.

Find - The requestor consults the broker to locate a published web service.

Bind - With the information it gained from the broker (service registry) about the web service, the requestor is able to bind, or invoke, the web service.

10. List and discuss the Web Services Components.

The basic web services platform is XML + HTTP. All the standard web services work using the following components −

SOAP (Simple Object Access Protocol)
    UDDI (Universal Description, Discovery and Integration)
    WSDL (Web Services Description Language)
    SOAP (Simple Object Access Protocol):
    SOAP stands for Simple Object Access Protocol.
    SOAP is a XML-based protocol for accessing web services.
    SOAP is a W3C recommendation for communication between applications.
    SOAP is XML based, so it is platform independent and language independent.
    It can be used with Java, .Net or PHP language on any platform.
UDDI :
    UDDI stands for Universal Description, Discovery and Integration
    UDDI is an XML based standard for describing, publishing and finding webservices.
    It can communicate via SOAP.
    It uses WSDL to describe interfaces to webservices.
WSDL :
    WSDL stands for Web Services Description Language.
    WSDL is an XML based language for describing webservices and how to access them.
    It is XML based protocol for information exchange in decentralized and distributed environments.
    It is an integral part of UDDI, an XML based worldwide business registry.
    It allows people and other companies to access the service.
