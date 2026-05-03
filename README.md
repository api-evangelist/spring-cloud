# Spring Cloud

Spring Cloud provides tools for developers to quickly build some of the common patterns in distributed systems including configuration management, service discovery, circuit breakers, intelligent routing, micro-proxy, control bus, and distributed tracing. It builds on the Spring Boot approach to simplify microservice development and operations across cloud environments.

**URL:** https://spring.io/projects/spring-cloud

## Tags

Circuit Breaker, Cloud Native, Distributed Systems, Java, Microservices, Service Discovery, Spring Framework

## APIs

### Spring Cloud Config

Externalized configuration management backed by Git, providing server and client-side support for configuration in distributed systems with encryption, refresh, and multi-environment support.

**Human URL:** https://spring.io/projects/spring-cloud-config  
**Base URL:** http://localhost:8888

**Tags:** Configuration, Distributed Config, Git, Microservices

### Spring Cloud Netflix Eureka

Service discovery using Netflix Eureka for registering and discovering microservices, providing self-registration, client-side discovery, heartbeat-based health checks, and zone-aware load balancing.

**Human URL:** https://spring.io/projects/spring-cloud-netflix  
**Base URL:** http://localhost:8761

**Tags:** Eureka, Registry, Service Discovery

### Spring Cloud Gateway

Intelligent routing and filtering for microservices built on Spring WebFlux with predicates, filters, load balancing, circuit breaking, and rate limiting.

**Human URL:** https://spring.io/projects/spring-cloud-gateway  
**Base URL:** http://localhost:8080

**Tags:** API Gateway, Filtering, Load Balancing, Routing

**Properties:**
- [OpenAPI](openapi/spring-cloud-gateway-actuator-openapi.yml)
- [JSON Schema](json-schema/spring-cloud-service-instance-schema.json)
- [JSON Structure](json-structure/spring-cloud-service-registry-structure.json)
- [JSON-LD Context](json-ld/spring-cloud-context.jsonld)
- [Spectral Rules](rules/spring-cloud-gateway-rules.yml)
- [Naftiko Capability](capabilities/microservice-platform.yaml)

### Spring Cloud Stream

Framework for building event-driven microservices connected with shared messaging systems including Apache Kafka and RabbitMQ with consumer groups and partitioning.

**Human URL:** https://spring.io/projects/spring-cloud-stream

**Tags:** Event-Driven, Kafka, Messaging, RabbitMQ

### Spring Cloud Circuit Breaker

Abstraction across different circuit breaker implementations including Resilience4J and Spring Retry, providing bulkhead, rate limiting, time limiting, and fallback patterns.

**Human URL:** https://spring.io/projects/spring-cloud-circuitbreaker

**Tags:** Circuit Breaker, Fault Tolerance, Resilience, Resilience4J

### Spring Cloud OpenFeign

Declarative REST client with support for Spring MVC annotations and HttpMessageConverters, providing load-balanced HTTP calls with Ribbon or Spring Cloud LoadBalancer integration.

**Human URL:** https://spring.io/projects/spring-cloud-openfeign

**Tags:** Declarative Client, Feign, HTTP, REST Client

### Spring Cloud Kubernetes

Integration with Kubernetes providing service discovery via DNS and Kubernetes API, ConfigMap and Secret-backed property sources, and load balancing for Spring Boot applications deployed in Kubernetes clusters.

**Human URL:** https://spring.io/projects/spring-cloud-kubernetes

**Tags:** ConfigMap, Container Orchestration, Kubernetes, Service Discovery

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [spring-cloud-gateway-actuator-openapi.yml](openapi/spring-cloud-gateway-actuator-openapi.yml) | Spring Cloud Gateway Actuator API |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [spring-cloud-config-properties.json](json-schema/spring-cloud-config-properties.json) | Spring Cloud application configuration properties schema |
| [spring-cloud-service-instance-schema.json](json-schema/spring-cloud-service-instance-schema.json) | Service instance registration schema |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [spring-cloud-service-registry-structure.json](json-structure/spring-cloud-service-registry-structure.json) | Service registry, instance, and route structure documentation |

### JSON-LD Contexts

| Context | Description |
|---------|-------------|
| [spring-cloud-context.jsonld](json-ld/spring-cloud-context.jsonld) | Spring Cloud linked data context |

### Examples

| Example | Description |
|---------|-------------|
| [spring-cloud-eureka-registration-example.json](examples/spring-cloud-eureka-registration-example.json) | Eureka service registration configuration |
| [spring-cloud-circuit-breaker-example.json](examples/spring-cloud-circuit-breaker-example.json) | Circuit breaker with Resilience4J and fallback |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [spring-cloud-gateway-rules.yml](rules/spring-cloud-gateway-rules.yml) | API design rules for Spring Cloud gateway conventions |

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [capabilities/microservice-platform.yaml](capabilities/microservice-platform.yaml) | Microservice platform management workflow |
| [capabilities/shared/spring-cloud-gateway-actuator.yaml](capabilities/shared/spring-cloud-gateway-actuator.yaml) | Shared Gateway Actuator API consumer definition |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [spring-cloud-vocabulary.yml](vocabulary/spring-cloud-vocabulary.yml) | Spring Cloud domain vocabulary and distributed systems terminology |

## Common Properties

- [Website](https://spring.io/projects/spring-cloud)
- [Documentation](https://docs.spring.io/spring-cloud/)
- [GitHub Organization](https://github.com/spring-cloud)
- [Blog](https://spring.io/blog/category/cloud)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-cloud)
- [Maven Repository](https://mvnrepository.com/artifact/org.springframework.cloud)

## Maintainers

**Name:** VMware Tanzu (Spring Team)  
**Email:** support@vmware.com  
**URL:** https://spring.io/team
