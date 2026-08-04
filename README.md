# Spring Cloud (spring-cloud)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
