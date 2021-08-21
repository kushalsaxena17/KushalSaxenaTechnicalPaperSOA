# Service-Oriented Architecture

Service-Oriented Architecture (SOA) is an architectural approach in which applications make use of services available in the network. In this architecture, services are provided to form applications, through a communication call over the internet.

>SOA allows users to combine a large number of facilities from existing services to form applications.

>SOA encompasses a set of design principles that structure system development and provide means for integrating components into a coherent and decentralized system

>SOA based computing packages functionalities into a set of interoperable services, which can be integrated into different software systems belonging to separate business domains.

&nbsp;

There are two major roles within Service-oriented Architecture:

1. **Service provider:** The service provider is the maintainer of the service and the organization that makes available one or more services for others to use. To advertise services, the provider can publish them in a registry, together with a service contract that specifies the nature of the service, how to use it, the requirements for the service, and the fees charged.

2. **Service consumer:** The service consumer can locate the service metadata in the registry and develop the required client components to bind and use the service.
![Image of Service consumer](https://media.geeksforgeeks.org/wp-content/uploads/Screenshot-245.png)
Services might aggregate information and data retrieved from other services or create workflows of services to satisfy the request of a given service consumer. This practice is known as service orchestration Another important interaction pattern is service choreography, which is the coordinated interaction of services without a single point of control.

## Components of SOA:
![Image of Components](https://media.geeksforgeeks.org/wp-content/uploads/Screenshot-248.png)

## Guiding Principles of SOA:
1. **Standardized service contract:** Specified through one or more service description documents.*
2. **Loose coupling:** Services are designed as self-contained components, maintain relationships that minimize dependencies on other services.
3. **Abstraction:** A service is completely defined by service contracts and description documents. They hide their logic, which is encapsulated within their implementation.*
4. **Reusability:** Designed as components, services can be reused more effectively, thus reducing development time and the associated costs.
5. **Autonomy:** Services have control over the logic they encapsulate and, from a service consumer point of view, there is no need to know about their implementation.

## Practical Applications:
1. SOA infrastructure is used by many armies and air force to deploy situational awareness systems.
2. SOA is used to improve the healthcare delivery.
3. Nowadays many apps are games and they use inbuilt functions to run. For example, an app might need GPS so it uses inbuilt GPS functions of the device. This is SOA in mobile solutions.
4. SOA helps maintain museums a virtualized storage pool for their information and content.

## Reference links:
* https://en.wikipedia.org/wiki/Service-oriented_architecture
* https://www.ibm.com/in-en/cloud/learn/soa
* https://medium.com/@SoftwareDevelopmentCommunity/what-is-service-oriented-architecture-fa894d11a7ec
* https://searchapparchitecture.techtarget.com/definition/service-oriented-architecture-SOA
