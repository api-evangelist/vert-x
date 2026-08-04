# Vert.x (vert-x)

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

Eclipse Vert.x is a toolkit for building reactive applications on the JVM, providing support for multiple languages including Java, JavaScript, Groovy, Ruby, and Kotlin with an event-driven, non-blocking architecture. Part of the Eclipse Foundation under the Eclipse Public License 2.0. Vert.x follows a polyglot, unopinionated model allowing developers to build microservices, web applications, IoT backends, and event-driven systems with high concurrency using a small memory footprint.

**URL:** [https://vertx.io/](https://vertx.io/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Event-Driven, Frameworks, Java, JVM, Microservices, Polyglot, Reactive, Eclipse Foundation, Open Source

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-03

## APIs

### Vert.x Core
The core toolkit for building reactive, event-driven applications on the JVM. Provides the event loop, verticle deployment, event bus, HTTP server and client, TCP/UDP networking, and the fundamental async programming model used by all Vert.x components.

**Human URL:** [https://vertx.io/docs/vertx-core/java/](https://vertx.io/docs/vertx-core/java/)

#### Tags:

 - Event-Driven, Event Loop, Verticles, Event Bus, Reactive, JVM

#### Properties

- [Documentation](https://vertx.io/docs/vertx-core/java/)
- [GettingStarted](https://vertx.io/get-started/)
- [GitHubRepository](https://github.com/eclipse-vertx/vert.x)
- [MavenPackage](https://central.sonatype.com/artifact/io.vertx/vertx-core)
- [JSONSchema](json-schema/vertx-config.json)
- [JSONStructure](json-structure/vertx-config-structure.json)
- [JSONSchema](json-schema/vertx-deployment-descriptor.json)
- [JSONStructure](json-structure/vertx-deployment-descriptor-structure.json)

### Vert.x Web
A set of building blocks for building web applications and RESTful HTTP microservices with Vert.x. Provides routing, request handling, session management, template engine support, and WebSocket handling on top of Vert.x Core HTTP server.

**Human URL:** [https://vertx.io/docs/vertx-web/java/](https://vertx.io/docs/vertx-web/java/)

#### Tags:

 - REST, HTTP, Web Framework, Routing, WebSocket

#### Properties

- [Documentation](https://vertx.io/docs/vertx-web/java/)
- [GitHubRepository](https://github.com/eclipse-vertx/vert.x)
- [MavenPackage](https://central.sonatype.com/artifact/io.vertx/vertx-web)

### Vert.x OpenAPI
Vert.x OpenAPI provides OpenAPI 3.1 specification support for Vert.x, enabling contract-driven API development with automatic request/response validation, routing, and API specification serving for Vert.x Web applications.

**Human URL:** [https://vertx.io/docs/vertx-openapi/java/](https://vertx.io/docs/vertx-openapi/java/)

#### Tags:

 - OpenAPI, API Specification, Validation, Contract-Driven

#### Properties

- [Documentation](https://vertx.io/docs/vertx-openapi/java/)
- [GitHubRepository](https://github.com/eclipse-vertx/vertx-openapi)
- [MavenPackage](https://central.sonatype.com/artifact/io.vertx/vertx-openapi)

### Vert.x gRPC
A Vert.x-native gRPC implementation providing a reactive, non-blocking gRPC client and server built on top of Vert.x HTTP/2. Supports protobuf service definitions with Vert.x Future and stream-based APIs.

**Human URL:** [https://vertx.io/docs/vertx-grpc/java/](https://vertx.io/docs/vertx-grpc/java/)

#### Tags:

 - gRPC, Protocol Buffers, HTTP/2, Streaming

#### Properties

- [Documentation](https://vertx.io/docs/vertx-grpc/java/)
- [GitHubRepository](https://github.com/eclipse-vertx/vertx-grpc)
- [MavenPackage](https://central.sonatype.com/artifact/io.vertx/vertx-grpc)

### Vert.x SQL Client
A high-performance reactive SQL client for Vert.x supporting PostgreSQL, MySQL, Microsoft SQL Server, IBM DB2, and Oracle databases. Provides a non-blocking, fully reactive API for executing queries, transactions, and batch operations.

**Human URL:** [https://vertx.io/docs/vertx-pg-client/java/](https://vertx.io/docs/vertx-pg-client/java/)

#### Tags:

 - SQL, Database, PostgreSQL, MySQL, Reactive

#### Properties

- [Documentation](https://vertx.io/docs/vertx-pg-client/java/)
- [GitHubRepository](https://github.com/eclipse-vertx/vertx-sql-client)
- [MavenPackage](https://central.sonatype.com/artifact/io.vertx/vertx-pg-client)

### Vert.x Auth
Authentication and authorization support for Vert.x applications. Provides JWT, OAuth2, JDBC, MongoDB, and WebAuthn/FIDO2 authentication providers with a unified async security API that integrates with Vert.x Web routing.

**Human URL:** [https://vertx.io/docs/vertx-auth-common/java/](https://vertx.io/docs/vertx-auth-common/java/)

#### Tags:

 - Authentication, Authorization, JWT, OAuth2, Security

#### Properties

- [Documentation](https://vertx.io/docs/vertx-auth-common/java/)
- [GitHubRepository](https://github.com/eclipse-vertx/vertx-auth)
- [MavenPackage](https://central.sonatype.com/artifact/io.vertx/vertx-auth-common)

### Vert.x Health Check
A Vert.x component for implementing health check endpoints for Kubernetes liveness and readiness probes. Provides a composable health procedure mechanism that aggregates multiple health checks into a single HTTP endpoint response.

**Human URL:** [https://vertx.io/docs/vertx-health-check/java/](https://vertx.io/docs/vertx-health-check/java/)

#### Tags:

 - Health Check, Kubernetes, Observability, Liveness, Readiness

#### Properties

- [Documentation](https://vertx.io/docs/vertx-health-check/java/)
- [GitHubRepository](https://github.com/eclipse-vertx/vertx-health-check)
- [MavenPackage](https://central.sonatype.com/artifact/io.vertx/vertx-health-check)
- [JSONSchema](json-schema/vertx-health-check-schema.json)
- [JSONStructure](json-structure/vertx-health-check-structure.json)

## Common Properties

- [Website](https://vertx.io/)
- [Documentation](https://vertx.io/docs/)
- [GettingStarted](https://vertx.io/get-started/)
- [GitHubOrganization](https://github.com/eclipse-vertx)
- [Blog](https://vertx.io/blog/)
- [PrivacyPolicy](https://www.eclipse.org/legal/privacy.php)
- [TermsOfService](https://www.eclipse.org/legal/termsofuse.php)
- [License](https://www.eclipse.org/legal/epl-2.0/)
- [Changelog](https://github.com/eclipse-vertx/vert.x/blob/master/CHANGELOG.adoc)
- [MavenCentral](https://central.sonatype.com/search?q=io.vertx)
- [Forums](https://groups.google.com/forum/#!forum/vertx)
- [StackOverflow](https://stackoverflow.com/questions/tagged/vert.x)

## Features

| Name | Description |
|------|-------------|
| Event-Driven Architecture | Non-blocking event loop model with verticles for concurrent request handling without traditional threading overhead. |
| Polyglot Support | Write Vert.x applications in Java, JavaScript, Groovy, Kotlin, Scala, and Ruby on the same JVM platform. |
| Event Bus | Distributed message-passing backbone enabling communication between verticles across nodes in a cluster. |
| Reactive HTTP Client and Server | High-performance HTTP/1.1 and HTTP/2 server and client with WebSocket, SSE, and gRPC support. |
| OpenAPI Contract Validation | Automatic request and response validation against OpenAPI 3.1 specifications using vertx-openapi. |
| Reactive SQL Clients | Non-blocking, fully reactive SQL clients for PostgreSQL, MySQL, MSSQL, DB2, and Oracle. |
| Authentication and Authorization | Pluggable security providers for JWT, OAuth2, JDBC, MongoDB, LDAP, and WebAuthn/FIDO2. |
| Health Checks | Composable health check procedures for Kubernetes liveness and readiness probe endpoints. |
| Clustering | Built-in cluster support via Hazelcast, Infinispan, Zookeeper, or Apache Ignite for distributed deployments. |
| Virtual Threads | Java 21 virtual thread support enabling synchronous-style code in Vert.x worker verticles. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservices Backend | Build lightweight, high-concurrency microservices with Vert.x Web routing, service proxy patterns, and event bus communication. |
| API Gateway | Implement reactive API gateways using vertx-http-proxy with routing, authentication, and rate limiting. |
| Real-Time Applications | Build WebSocket and SSE-based real-time applications for live dashboards, chat, and notification systems. |
| IoT Data Ingestion | Handle high-volume MQTT and TCP data streams from IoT devices using Vert.x non-blocking networking. |
| Contract-First REST APIs | Develop OpenAPI 3.1 contract-first REST APIs with automatic validation using vertx-openapi and vertx-web. |

## Integrations

| Name | Description |
|------|-------------|
| Quarkus | Vert.x is the reactive engine underlying Quarkus, providing the event loop and HTTP server for Quarkus applications. |
| Kubernetes | Deploy Vert.x verticles on Kubernetes with health check endpoints, clustering, and horizontal pod autoscaling. |
| Apache Kafka | Vert.x Kafka Client provides reactive, non-blocking Kafka producer and consumer integration. |
| Redis | Vert.x Redis Client enables async Redis operations for caching, pub/sub, and session storage. |
| Hazelcast | Hazelcast cluster manager for distributed Vert.x deployments with shared data and event bus clustering. |
| Micrometer | Vert.x Micrometer Metrics provides application metrics integration with Prometheus and Grafana. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [vertx-config.json](json-schema/vertx-config.json)
- [vertx-deployment-descriptor.json](json-schema/vertx-deployment-descriptor.json)
- [vertx-health-check-schema.json](json-schema/vertx-health-check-schema.json)

### JSON Structure

- [vertx-config-structure.json](json-structure/vertx-config-structure.json)
- [vertx-deployment-descriptor-structure.json](json-structure/vertx-deployment-descriptor-structure.json)
- [vertx-health-check-structure.json](json-structure/vertx-health-check-structure.json)

### JSON-LD

- [vert-x-context.jsonld](json-ld/vert-x-context.jsonld)

### Examples

- [vertx-config-example.json](examples/vertx-config-example.json)
- [vertx-deployment-descriptor-example.json](examples/vertx-deployment-descriptor-example.json)
- [vertx-health-check-example.json](examples/vertx-health-check-example.json)

## Vocabulary

- [Vert.x Vocabulary](vocabulary/vert-x-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 7 actions, 1 workflow, and 3 personas across Vert.x reactive toolkit components

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
