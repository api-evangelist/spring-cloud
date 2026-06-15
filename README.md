# Spring Cloud (spring-cloud)

Spring Cloud provides tools for developers to quickly build some of the common patterns in distributed systems including configuration management, service discovery, circuit breakers, intelligent routing, micro-proxy, control bus, and distributed tracing. It builds on the Spring Boot approach to simplify microservice development and operations across cloud environments.

**APIs.json:** [https://spring.io/projects/spring-cloud](https://spring.io/projects/spring-cloud)

## Tags

- Circuit Breaker
- Cloud Native
- Distributed Systems
- Java
- Microservices
- Service Discovery
- Spring Framework

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Spring Cloud Config

Externalized configuration management backed by Git, providing server and client-side support for configuration in distributed systems with encryption, refresh, and multi-environment support.

- **Human URL:** [https://spring.io/projects/spring-cloud-config](https://spring.io/projects/spring-cloud-config)
- **Base URL:** `http://localhost:8888`

#### Tags

- Configuration
- Distributed Config
- Git
- Microservices

#### Properties

- [Documentation](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/)
- [Git Hub](https://github.com/spring-cloud/spring-cloud-config)
- [JSON Schema](json-schema/spring-cloud-config-properties.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/spring-cloud-gateway-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-cloud-gateway-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Cloud Netflix Eureka

Service discovery using Netflix Eureka for registering and discovering microservices, providing self-registration, client-side discovery, heartbeat-based health checks, and zone-aware load balancing.

- **Human URL:** [https://spring.io/projects/spring-cloud-netflix](https://spring.io/projects/spring-cloud-netflix)
- **Base URL:** `http://localhost:8761`

#### Tags

- Eureka
- Registry
- Service Discovery

#### Properties

- [Documentation](https://docs.spring.io/spring-cloud-netflix/docs/current/reference/html/)
- [Git Hub](https://github.com/spring-cloud/spring-cloud-netflix)
- [Postman Collection](collections/spring-cloud-gateway-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-cloud-gateway-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Cloud Gateway

Intelligent routing and filtering for microservices built on Spring WebFlux with predicates, filters, load balancing, circuit breaking, and rate limiting.

- **Human URL:** [https://spring.io/projects/spring-cloud-gateway](https://spring.io/projects/spring-cloud-gateway)
- **Base URL:** `http://localhost:8080`

#### Tags

- API Gateway
- Filtering
- Load Balancing
- Routing

#### Properties

- [Documentation](https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/)
- [Git Hub](https://github.com/spring-cloud/spring-cloud-gateway)
- [OpenAPI](openapi/spring-cloud-gateway-actuator-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spring-cloud-gateway-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-cloud-gateway-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/spring-cloud-service-instance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/spring-cloud-service-registry-structure.json)
- [J S O N L D Context](json-ld/spring-cloud-context.jsonld)
- [Spectral Rules](rules/spring-cloud-gateway-rules.yml)

### Spring Cloud Stream

Framework for building event-driven microservices connected with shared messaging systems including Apache Kafka and RabbitMQ with consumer groups and partitioning.

- **Human URL:** [https://spring.io/projects/spring-cloud-stream](https://spring.io/projects/spring-cloud-stream)
- **Base URL:** `https://spring.io/projects/spring-cloud-stream`

#### Tags

- Event-Driven
- Kafka
- Messaging
- RabbitMQ

#### Properties

- [Documentation](https://docs.spring.io/spring-cloud-stream/docs/current/reference/html/)
- [Git Hub](https://github.com/spring-cloud/spring-cloud-stream)
- [Getting Started](https://spring.io/guides/gs/spring-cloud-stream/)
- [Postman Collection](collections/spring-cloud-gateway-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-cloud-gateway-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Cloud Circuit Breaker

Abstraction across different circuit breaker implementations including Resilience4J and Spring Retry, providing bulkhead, rate limiting, time limiting, and fallback patterns.

- **Human URL:** [https://spring.io/projects/spring-cloud-circuitbreaker](https://spring.io/projects/spring-cloud-circuitbreaker)
- **Base URL:** `https://spring.io/projects/spring-cloud-circuitbreaker`

#### Tags

- Circuit Breaker
- Fault Tolerance
- Resilience
- Resilience4J

#### Properties

- [Documentation](https://docs.spring.io/spring-cloud-circuitbreaker/docs/current/reference/html/)
- [Git Hub](https://github.com/spring-cloud/spring-cloud-circuitbreaker)
- [Postman Collection](collections/spring-cloud-gateway-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-cloud-gateway-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Cloud OpenFeign

Declarative REST client with support for Spring MVC annotations and HttpMessageConverters, providing load-balanced HTTP calls with Ribbon or Spring Cloud LoadBalancer integration.

- **Human URL:** [https://spring.io/projects/spring-cloud-openfeign](https://spring.io/projects/spring-cloud-openfeign)
- **Base URL:** `https://spring.io/projects/spring-cloud-openfeign`

#### Tags

- Declarative Client
- Feign
- HTTP
- REST Client

#### Properties

- [Documentation](https://docs.spring.io/spring-cloud-openfeign/docs/current/reference/html/)
- [Git Hub](https://github.com/spring-cloud/spring-cloud-openfeign)
- [Postman Collection](collections/spring-cloud-gateway-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-cloud-gateway-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Cloud Kubernetes

Integration with Kubernetes providing service discovery via DNS and Kubernetes API, ConfigMap and Secret-backed property sources, and load balancing for Spring Boot applications deployed in Kubernetes clusters.

- **Human URL:** [https://spring.io/projects/spring-cloud-kubernetes](https://spring.io/projects/spring-cloud-kubernetes)
- **Base URL:** `https://spring.io/projects/spring-cloud-kubernetes`

#### Tags

- ConfigMap
- Container Orchestration
- Kubernetes
- Service Discovery

#### Properties

- [Documentation](https://docs.spring.io/spring-cloud-kubernetes/docs/current/reference/html/)
- [Git Hub](https://github.com/spring-cloud/spring-cloud-kubernetes)
- [Postman Collection](collections/spring-cloud-gateway-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-cloud-gateway-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://spring.io/projects/spring-cloud)
- [Documentation](https://docs.spring.io/spring-cloud/)
- [GitHub Organization](https://github.com/spring-cloud)
- [Blog](https://spring.io/blog/category/cloud)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-cloud)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework.cloud)
- [Vocabulary](vocabulary/spring-cloud-vocabulary.yml)

## Maintainers

**FN:** VMware Tanzu (Spring Team)
**Email:** support@vmware.com
**URL:** https://spring.io/team
