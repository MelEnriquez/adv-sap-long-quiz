## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).

- Service Oriented Architecture (SOA) is an architecture model or design of a software development that is responsible in simplifying complex software systems. SOA makes services reusable , and this "services" can communicate across different platform and language to be used in creating a new application.

2. List and discuss the characteristics of SOA.

- STANDARDIZED SERVICE CONTRACT: This characteristic refers that service needs information such as overall purpose and capabilities to form a service contract.
- LOOSE COUPLING: This characteristic minimizes dependencies on each software and creates boundaries so that services will not stop from running if problem occurs.
- ABSTRACTION: This characteristic refers to when the service hides the logic that are encapsulated from the outside world so that information within the service is limited and can easily be utilized.
- SERVICE REUSABILITY: This characteristic intends to maximize reusability to enable flexibility and minimize redundancy.
- STATELESSNESS: This characteristic minimize and reduce resource consumptions in order to increase service scalability.
- DISCOVERABILITY: This characteristic provides discovery service such as registry that allows the purpose and capabilities to communication with humans.
- COMPOSABILITY: This characteristic is responsible in breaking down large and complex problems into smaller problem.
- INTEROPERABILITY: This characteristic allows services to run in a different platform and architectures.

3. Define Microservices.

- Microservices is a cloud-native architectural approach to software development that builds individual or single application as a collection of services. It handles discrete tasks and features that make the application more agile, scalable, and resilient.

4. List and discuss the benefits of using Microservices.

- IMPROVED PRODUCTIVITY: Microservices are easier to maintainas it breaks down applications into smaller fragments which make adding, removing, and updating software more conveniently.
- SIMPLER TO DEPLOY: Microservices are independently deployable, as their small-sized services help clear boundaries between team members so they can easily understand the code and contribute to it quickly.
- INCREASED SCALABILITY: Microservices can be used in different languages with its own communication protocol, making it adaptable to people and appreciate each without any problem.
- OPTIMIZE BUSINESS FUNCTIONALITY: Microservices works on individual or single modules, making the team members on optimizing and improving the functionalities of the business.

5. List and discuss the similarities and differences of SOA and Microservices.

- SIMILARITIES: The similarities of SOA and Microservices is that both of them are used in creating services that allows their team member to build, deploy, and manage applications much efficiently for cloud improvements.

-DIFFERENCES:

- COMMUNICATION: SOA communication require both parties to share the same communication mechanisms while Microservices are independently works with its own communication protocol.
- INTEROPERABILITY: SOA are open to different message protocols while Microservices keeps message protocols simple and lightweight, making things easier to understand by the users.
- SERVICE GRANULARITY: SOA services can be used in small and wide enterprises while Microservices are already designed for complexity and dependencies or the whole application.
- SPEED: SOA focused on simplifying and troubleshooting while Microservices are smaller, and the deployment speed is much quicker.

6. Define Web Services.

- Web Services are meant for applications. This contains series of programs that makes the application an application. It is also a collections of open protocols used in exchanging data between applications and system with the programming languages that they used. 

7. List and discuss the benefits of using Web Services.

- REVEALING THE EXISTING FUNCTION ON NETWORK: Web Services code can be manage and can remotely invoke using HTTP. It allows other applications to use the functionality of your program.
- INTEROPERABILITY: Web Services objective is to give applications the chance to talk and share data among themselves. With this, it can create an application that are much simpler to understand.
- STANDARDIZE PROTOCOL: Web Services uses standardized protocols that gives businesses that advantages to gather up wide range of choices for the betterment of its application.
- EASE OF USE: As mentioned to the first benefit, since it allows other application to use the functionality of your program, this also means that users can easily utilized and access the services via internet. 

8. List and discuss the characteristics of Web Services.

- XML-BASED: XML is a software-hardware independent tool for storing and transporting data, so using this, it allows the web services to work without the need of networking, operating system, or platform binding.
- COARSE-GRAINED: Course-grained is a method in which it returns the data of applications. With this, it allows web services in  wrapping up one or more coarse-grained services that gives user the access to the right amount of logic.
- LOOSELY COUPLED: Web Services are loosely coupled, meaning that the user's capabilities does not have anything to do with the web service, or they do not have affect with the service. Web Service can change over time by itself without the thought of whom will interact to it.
- CAPABILITY TO BE SYNCHRONOUS AND ASYNCHRONOUS: In Synchronous, it allows users to invoked existing web protocols and waits patiently for the the service to be completed. Vise versa to what happened in Asynchronous where users can invoked the existing service, adding or executing other functions without the need to wait for the service to be completed.

9. List and discuss the distinct roles in Web Services Architecture.

- PROVIDER: He/She is the one who creates web services and grant users in using the applications that they created.
- REQUESTOR: Is an application which contacts the web services for functionalities.
- BROKER: Is an application that uses UDDI, that is also an XML-based standard that focused on finding the location of the web services.
- PUBLISH: It is where it gives users the access to utilize the services/applications.
- FIND: It is where requestor request to look and locate the published web services
- BIND: It is where the requestor will be able invoke the web services after all the information the requestor need has been gathered.

10. List and discuss the Web Services Components.

- SOAP(Simple Object Access Protocol): SOAP is an XML-based protocol that is responsible for coomunicating and exchanging informations between applications.
- UDDI(Universal Description, Discovery and Integration): UDDI is an XML-based standard that is responsible in finding the location of the web services.
- WSDL(Web Services Description Language): WSDL is an XML-based language that is responsible in allowing users to have access within the services.