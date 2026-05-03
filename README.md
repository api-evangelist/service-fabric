# Service Fabric

**URL:** [https://raw.githubusercontent.com/api-evangelist/service-fabric/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/service-fabric/refs/heads/main/apis.yml)

Azure Service Fabric is an open-source distributed systems platform for packaging, deploying, and managing scalable and reliable microservices and containers. Service Fabric powers many Microsoft Azure core services including Azure SQL Database, Azure Cosmos DB, and Skype for Business. It provides a programming model for stateful and stateless microservices using Reliable Collections and Reliable Actors.

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### Service Fabric Cluster Management API

The Service Fabric Cluster Management REST API enables management of clusters, nodes, applications, services, partitions, replicas, and health states. Provides full application lifecycle management and cluster health monitoring.

**Human URL:** [https://docs.microsoft.com/en-us/rest/api/servicefabric/](https://docs.microsoft.com/en-us/rest/api/servicefabric/)
**Base URL:** `http://{cluster-endpoint}:19080`

#### Tags

Distributed Systems, Cluster Management, Application Lifecycle, Health Monitoring

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/azure/service-fabric/)
- [REST API Reference](https://docs.microsoft.com/en-us/rest/api/servicefabric/)
- [GitHub](https://github.com/microsoft/service-fabric)
- [OpenAPI](openapi/service-fabric-cluster-openapi.yml)

---

### Service Fabric SDK

Service Fabric SDK provides client libraries for .NET, Java, and Go for building Service Fabric services and interacting with the cluster. Includes Reliable Collections, Reliable Actors, and the Reliable Services programming model.

**Human URL:** [https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started)

#### Tags

SDK, .NET, Java, Microservices, Reliable Collections

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started)
- [NuGet](https://www.nuget.org/packages/Microsoft.ServiceFabric/)
- [Maven](https://mvnrepository.com/artifact/com.microsoft.servicefabric/sf-actors)

---

## Common Properties

- [Documentation](https://docs.microsoft.com/en-us/azure/service-fabric/)
- [GitHub](https://github.com/microsoft/service-fabric)
- [Getting Started](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started)
- [REST API Reference](https://docs.microsoft.com/en-us/rest/api/servicefabric/)
- [Changelog](https://github.com/microsoft/service-fabric/releases)
- [License](https://github.com/microsoft/service-fabric/blob/master/LICENSE)

## Artifacts

### OpenAPI Specifications

| File | Description |
|------|-------------|
| [service-fabric-cluster-openapi.yml](openapi/service-fabric-cluster-openapi.yml) | Service Fabric REST API v9.1 — cluster health, nodes, applications, services |

### JSON Schemas

| File | Description |
|------|-------------|
| [service-fabric-application-schema.json](json-schema/service-fabric-application-schema.json) | JSON Schema for the Service Fabric Application resource |

### JSON Structures

| File | Description |
|------|-------------|
| [service-fabric-application-structure.json](json-structure/service-fabric-application-structure.json) | Field-by-field structural documentation for the Application resource |

### JSON-LD Context

| File | Description |
|------|-------------|
| [service-fabric-context.jsonld](json-ld/service-fabric-context.jsonld) | JSON-LD context mapping Service Fabric vocabulary to schema.org |

### Examples

| File | Description |
|------|-------------|
| [service-fabric-create-application-example.json](examples/service-fabric-create-application-example.json) | Create a Service Fabric application |
| [service-fabric-get-cluster-health-example.json](examples/service-fabric-get-cluster-health-example.json) | Get cluster health state |

### Rules

| File | Description |
|------|-------------|
| [service-fabric-rules.yml](rules/service-fabric-rules.yml) | Spectral ruleset enforcing Service Fabric API conventions |

### Capabilities

| File | Description |
|------|-------------|
| [capabilities/cluster-management.yaml](capabilities/cluster-management.yaml) | Unified cluster management workflow — nodes, applications, services, health |
| [capabilities/shared/service-fabric-api.yaml](capabilities/shared/service-fabric-api.yaml) | Per-API Naftiko consumed definition for the Service Fabric REST API |

### Vocabulary

| File | Description |
|------|-------------|
| [service-fabric-vocabulary.yml](vocabulary/service-fabric-vocabulary.yml) | Domain vocabulary for Service Fabric distributed systems concepts |

## Maintainers

**Email:** kin@apievangelist.com
