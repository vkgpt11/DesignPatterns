## why do we need Singleton?

- In C#, the Singleton pattern will ensure that there is only one instance of a class is created in the CLR. 
- It is used to provide global point of access to the object. 
- In terms of practical use Singleton patterns are used in logging, caches, thread pools, configuration settings, device driver objects. 
- Design pattern is often used in conjunction with Factory design pattern. This pattern is also used in Service Locator

https://stackoverflow.com/questions/228164/on-design-patterns-when-should-i-use-the-singleton

## What is the difference between Builder Design pattern and Factory Design pattern?
https://stackoverflow.com/questions/757743/what-is-the-difference-between-builder-design-pattern-and-factory-design-pattern

## What are some common, real world examples of using the Builder Pattern? What does it buy you? Why not just use a Factory Pattern?
https://stackoverflow.com/questions/328496/when-would-you-use-the-builder-pattern?noredirect=1&lq=1


## what all five cloud design patterns?
1. Cache-Aside: Load data on demand into a cache from a data store
2. Command and Query Responsibility Segregation (CQRS) pattern: Segregate operations that read data from operations that update data by using separate interfaces. This can maximize performance,   scalability, and security. Supports the evolution of the system over time through higher flexibility, and prevents update commands from causing merge conflicts at the domain level.

3. Publisher-Subscriber pattern:Enable an application to announce events to multiple interested consumers aynchronously, without coupling the senders to the receivers.

4. Circuit Breaker pattern: Handle faults that might take a variable amount of time to recover from, when connecting to a remote service or resource. This can improve the stability and resiliency of an application.

5. Health Endpoint Monitoring pattern: Implement functional checks in an application that external tools can access through exposed endpoints at regular intervals. This can help to verify that applications and services are performing correctly.




