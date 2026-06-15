# Service Fabric (service-fabric)

Azure Service Fabric is an open-source distributed systems platform for packaging, deploying, and managing scalable and reliable microservices and containers. Service Fabric powers many Microsoft Azure core services, and thousands of services at scale including Azure SQL Database, Azure Cosmos DB, Skype for Business, and Cortana. Service Fabric provides a programming model for building stateful and stateless microservices, reliable collections, and actor-based services. The Service Fabric REST API enables cluster management, application lifecycle, and service configuration.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/service-fabric/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/service-fabric/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Distributed Systems
- Microservices
- Containers
- Cloud Native
- Kubernetes
- Azure
- Open Source

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### Service Fabric Cluster Management API

The Service Fabric Cluster Management REST API enables management of Service Fabric clusters, nodes, applications, services, partitions, replicas, and health states. Provides operations for application lifecycle management (provision, create, upgrade, delete) and cluster health monitoring.

- **Human URL:** [https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-rest-based-model](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-rest-based-model)
- **Base URL:** `http://{cluster-endpoint}:19080`

#### Tags

- Distributed Systems
- Cluster Management
- Application Lifecycle
- Health Monitoring

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-rest-based-model)
- [Reference](https://docs.microsoft.com/en-us/rest/api/servicefabric/)
- [Git Hub](https://github.com/microsoft/service-fabric)
- [OpenAPI](openapi/service-fabric-cluster-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/service-fabric-cluster.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/service-fabric-cluster.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/service-fabric-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/service-fabric-application-structure.json)
- [Spectral Rules](rules/service-fabric-rules.yml)
- [Capabilities](capabilities/cluster-management.yaml)

### Service Fabric SDK

Service Fabric SDK provides client libraries for .NET, Java, and Go for building Service Fabric services and interacting with the cluster. The SDK includes Reliable Collections, Reliable Actors, and the Reliable Services programming model.

- **Human URL:** [https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started)

#### Tags

- SDK
- .NET
- Java
- Microservices
- Reliable Collections

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started)
- [Nu Get](https://www.nuget.org/packages/Microsoft.ServiceFabric/)
- [Maven](https://mvnrepository.com/artifact/com.microsoft.servicefabric/sf-actors)
- [Postman Collection](collections/service-fabric-cluster.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/service-fabric-cluster.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://docs.microsoft.com/en-us/azure/service-fabric/)
- [Git Hub](https://github.com/microsoft/service-fabric)
- [Documentation](https://docs.microsoft.com/en-us/azure/service-fabric/)
- [Getting Started](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started)
- [Reference](https://docs.microsoft.com/en-us/rest/api/servicefabric/)
- [Changelog](https://github.com/microsoft/service-fabric/releases)
- [License](https://github.com/microsoft/service-fabric/blob/master/LICENSE)
- [JSON Schema](json-schema/service-fabric-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/service-fabric-application-structure.json)
- [J S O N L D Context](json-ld/service-fabric-context.jsonld)
- [Examples](examples/service-fabric-create-application-example.json)
- [Examples](examples/service-fabric-get-cluster-health-example.json)
- [Vocabulary](vocabulary/service-fabric-vocabulary.yml)
- [Spectral Rules](rules/service-fabric-rules.yml)
- [Capabilities](capabilities/cluster-management.yaml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
