# Microservices-2
**Tasks:**
1. Implement 2 patterns from pool using Spring Cloud and/or K8s;
Pool is this: service-registry, circuit-breaker, api-gateway.
2. Document your decision in README.md in your repo.
3. Make pull requests.

## Overview
This is a simple "Bookstore App" that contains:
- Book microservice
- Author microservice
- Spring Cloud API Gateway
- Netflix Eureka service registry

## Glossary
1. Author
2. Book

## Implemented patterns
### Service registry
The *service registry pattern* is a key part of service discovery. The registry is a database containing the network locations of service instances. A service registry needs to be highly available and up-to-date. One of the most popular implementations of this pattern is *Eureka Service Registry*.

### Api gateway
The *api gateway pattern* is a service that provides a single-entry point for certain groups of microservices. It's similar to the *Facade pattern* from object-oriented design, but in this case, it's part of a distributed system.
