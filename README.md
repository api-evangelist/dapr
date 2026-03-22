# Dapr (dapr)
Dapr (Distributed Application Runtime) is a portable, event-driven runtime that makes it easy for developers to build resilient, stateless, and stateful applications that run on the cloud and edge. It provides building block APIs for state management, pub/sub messaging, service invocation, bindings, actors, workflows, secrets, configuration, distributed locks, cryptography, jobs scheduling, health checks, and metadata.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Workflows, State Management, Pub/Sub, Microservices, Distributed Systems, Platform

## Timestamps

- **Created:** 2025-01-08 
- **Modified:** 2026-03-18 

## APIs

### Dapr State Management API
The Dapr State Management API provides key/value-based state management capabilities for distributed applications. It supports saving, retrieving, deleting, and performing bulk and transactional operations on application state using pluggable state stores.

**Human URL:** [https://docs.dapr.io/reference/api/state_api/](https://docs.dapr.io/reference/api/state_api/)


#### Tags:

 - State Management, Key Value, Distributed Systems

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/state_api/)
- [OpenAPI](openapi/dapr-state-management-openapi.yml)
- [JSONSchema](json-schema/state-item.json)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/state-management/)
- [Client Libraries](https://docs.dapr.io/sdks/)

### Dapr Pub/Sub API
The Dapr Pub/Sub API enables publish and subscribe messaging between applications. It supports publishing events to topics, bulk publishing, and discovering topic subscriptions using the CloudEvents 1.0 specification.

**Human URL:** [https://docs.dapr.io/reference/api/pubsub_api/](https://docs.dapr.io/reference/api/pubsub_api/)


#### Tags:

 - Pub/Sub, Messaging, Events, CloudEvents

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/pubsub_api/)
- [OpenAPI](openapi/dapr-pubsub-openapi.yml)
- [AsyncAPI](asyncapi/dapr-pubsub-asyncapi.yml)
- [JSONSchema](json-schema/cloud-event.json)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/pubsub/)
- [Client Libraries](https://docs.dapr.io/sdks/)

### Dapr Service Invocation API
The Dapr Service Invocation API enables applications to communicate with each other through well-known endpoints using HTTP methods. Dapr acts as a reverse proxy with built-in service discovery, distributed tracing, and error handling.

**Human URL:** [https://docs.dapr.io/reference/api/service_invocation_api/](https://docs.dapr.io/reference/api/service_invocation_api/)


#### Tags:

 - Service Invocation, Microservices, Service Discovery

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/service_invocation_api/)
- [OpenAPI](openapi/dapr-service-invocation-openapi.yml)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/service-invocation/)
- [Client Libraries](https://docs.dapr.io/sdks/)

### Dapr Bindings API
The Dapr Bindings API enables applications to trigger and invoke external resources through output bindings, and receive events from external resources through input bindings. Supported bindings include Kafka, RabbitMQ, Azure Event Hubs, AWS SQS, GCP Storage, and more.

**Human URL:** [https://docs.dapr.io/reference/api/bindings_api/](https://docs.dapr.io/reference/api/bindings_api/)


#### Tags:

 - Bindings, Integrations, Event-Driven

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/bindings_api/)
- [OpenAPI](openapi/dapr-bindings-openapi.yml)
- [JSONSchema](json-schema/binding.json)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/bindings/)
- [Client Libraries](https://docs.dapr.io/sdks/)

### Dapr Secrets API
The Dapr Secrets API provides a consistent way to retrieve application secrets from various secret stores, including Hashicorp Vault, AWS Secrets Manager, Azure Key Vault, GCP Secret Manager, and Kubernetes Secrets.

**Human URL:** [https://docs.dapr.io/reference/api/secrets_api/](https://docs.dapr.io/reference/api/secrets_api/)


#### Tags:

 - Secrets, Security, Key Management

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/secrets_api/)
- [OpenAPI](openapi/dapr-secrets-openapi.yml)
- [JSONSchema](json-schema/secret.json)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/secrets/)
- [Client Libraries](https://docs.dapr.io/sdks/)

### Dapr Actors API
The Dapr Actors API provides virtual actor capabilities for distributed applications, including actor method invocation, state management, timers, and reminders with guaranteed single-threaded execution and message ordering.

**Human URL:** [https://docs.dapr.io/reference/api/actors_api/](https://docs.dapr.io/reference/api/actors_api/)


#### Tags:

 - Actors, Virtual Actors, Distributed Systems

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/actors_api/)
- [OpenAPI](openapi/dapr-actors-openapi.yml)
- [JSONSchema](json-schema/actor.json)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/actors/)
- [Client Libraries](https://docs.dapr.io/sdks/)

### Dapr Workflow API
The Dapr Workflow API provides the ability to manage workflow instances, including starting, getting status, pausing, resuming, terminating, purging, and raising events to workflows.

**Human URL:** [https://docs.dapr.io/reference/api/workflow_api/](https://docs.dapr.io/reference/api/workflow_api/)


#### Tags:

 - Workflows, Orchestration, Distributed Systems

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/workflow_api/)
- [OpenAPI](openapi/dapr-workflow-openapi.yml)
- [JSONSchema](json-schema/workflow.json)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/workflow/)
- [Client Libraries](https://docs.dapr.io/sdks/)

### Dapr Configuration API
The Dapr Configuration API enables applications to retrieve and subscribe to configuration items from supported configuration stores, allowing applications to react to configuration changes in real time.

**Human URL:** [https://docs.dapr.io/reference/api/configuration_api/](https://docs.dapr.io/reference/api/configuration_api/)


#### Tags:

 - Configuration, Subscriptions, Distributed Systems

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/configuration_api/)
- [OpenAPI](openapi/dapr-configuration-openapi.yml)
- [JSONSchema](json-schema/configuration-item.json)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/configuration/)
- [Client Libraries](https://docs.dapr.io/sdks/)

### Dapr Distributed Lock API
The Dapr Distributed Lock API enables applications to acquire and release locks on shared resources, ensuring mutual exclusion across multiple application instances using a lease-based locking mechanism.

**Human URL:** [https://docs.dapr.io/reference/api/distributed_lock_api/](https://docs.dapr.io/reference/api/distributed_lock_api/)


#### Tags:

 - Distributed Lock, Concurrency, Coordination

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/distributed_lock_api/)
- [OpenAPI](openapi/dapr-distributed-lock-openapi.yml)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/distributed-lock/)
- [Client Libraries](https://docs.dapr.io/sdks/)

### Dapr Cryptography API
The Dapr Cryptography API enables applications to perform cryptographic operations such as encrypting and decrypting data using configured cryptography components, without exposing cryptographic keys to the application.

**Human URL:** [https://docs.dapr.io/reference/api/cryptography_api/](https://docs.dapr.io/reference/api/cryptography_api/)


#### Tags:

 - Cryptography, Security, Encryption

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/cryptography_api/)
- [OpenAPI](openapi/dapr-cryptography-openapi.yml)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/cryptography/)
- [Client Libraries](https://docs.dapr.io/sdks/)

### Dapr Jobs API
The Dapr Jobs API enables applications to schedule, retrieve, and delete jobs for future execution at specific times or intervals using cron expressions or duration specifications.

**Human URL:** [https://docs.dapr.io/reference/api/jobs_api/](https://docs.dapr.io/reference/api/jobs_api/)


#### Tags:

 - Jobs, Scheduling, Cron

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/jobs_api/)
- [OpenAPI](openapi/dapr-jobs-openapi.yml)
- [JSONSchema](json-schema/job.json)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/jobs/)
- [Client Libraries](https://docs.dapr.io/sdks/)

### Dapr Health API
The Dapr Health API provides health check endpoints for the Dapr sidecar, usable with container orchestrators like Kubernetes for readiness and liveness probes.

**Human URL:** [https://docs.dapr.io/reference/api/health_api/](https://docs.dapr.io/reference/api/health_api/)


#### Tags:

 - Health, Monitoring, Kubernetes

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/health_api/)
- [OpenAPI](openapi/dapr-health-openapi.yml)
- [Reference](https://docs.dapr.io/operations/observability/healthchecks/)

### Dapr Metadata API
The Dapr Metadata API provides information about the Dapr sidecar, including application connection details, registered components, active subscriptions, and HTTP endpoints. It also allows setting custom metadata attributes.

**Human URL:** [https://docs.dapr.io/reference/api/metadata_api/](https://docs.dapr.io/reference/api/metadata_api/)


#### Tags:

 - Metadata, Runtime, Observability

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/metadata_api/)
- [OpenAPI](openapi/dapr-metadata-openapi.yml)
- [JSONSchema](json-schema/metadata.json)
- [Reference](https://docs.dapr.io/operations/observability/)

## Common Properties

- [Website](https://dapr.io/)
- [Documentation](https://docs.dapr.io/)
- [Getting Started](https://docs.dapr.io/getting-started/)
- [Blog](https://blog.dapr.io/)
- [GitHub Organization](https://github.com/dapr)
- [GitHubRepository](https://github.com/dapr/dapr)
- [SDKs](https://docs.dapr.io/sdks/)
- [Community](https://discord.gg/ptHhX6jc34)
- [Change Log](https://github.com/dapr/dapr/blob/master/CHANGELOG.md)
- [Security](https://github.com/dapr/dapr/security/policy)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/dapr)
- [JSON-LD](json-ld/dapr-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
