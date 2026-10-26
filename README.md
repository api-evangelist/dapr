# Dapr (dapr)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Dapr (Distributed Application Runtime) is a portable, event-driven runtime that makes it easy for developers to build resilient, stateless, and stateful applications that run on the cloud and edge. It provides building block APIs for state management, pub/sub messaging, service invocation, bindings, actors, workflows, secrets, configuration, distributed locks, cryptography, jobs scheduling, health checks, and metadata.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Distributed Systems
- Microservices
- Platform
- Pub/Sub
- State Management
- Workflows

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### Dapr State Management API

The Dapr State Management API provides key/value-based state management capabilities for distributed applications. It supports saving, retrieving, deleting, and performing bulk and transactional operations on application state using pluggable state stores.

- **Human URL:** [https://docs.dapr.io/reference/api/state_api/](https://docs.dapr.io/reference/api/state_api/)

#### Tags

- Distributed Systems
- Key Value
- State Management

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/state_api/)
- [OpenAPI](openapi/dapr-state-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dapr-state-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dapr-state-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/state-item.json) — [JSON Schema](https://json-schema.org/specification)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/state-management/)
- [Client  Libraries](https://docs.dapr.io/sdks/)

### Dapr Pub/Sub API

The Dapr Pub/Sub API enables publish and subscribe messaging between applications. It supports publishing events to topics, bulk publishing, and discovering topic subscriptions using the CloudEvents 1.0 specification.

- **Human URL:** [https://docs.dapr.io/reference/api/pubsub_api/](https://docs.dapr.io/reference/api/pubsub_api/)

#### Tags

- CloudEvents
- Events
- Messaging
- Pub/Sub

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/pubsub_api/)
- [OpenAPI](openapi/dapr-pubsub-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dapr-pubsub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dapr-pubsub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/dapr-pubsub-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/cloud-event.json) — [JSON Schema](https://json-schema.org/specification)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/pubsub/)
- [Client  Libraries](https://docs.dapr.io/sdks/)

### Dapr Service Invocation API

The Dapr Service Invocation API enables applications to communicate with each other through well-known endpoints using HTTP methods. Dapr acts as a reverse proxy with built-in service discovery, distributed tracing, and error handling.

- **Human URL:** [https://docs.dapr.io/reference/api/service_invocation_api/](https://docs.dapr.io/reference/api/service_invocation_api/)

#### Tags

- Microservices
- Service Discovery
- Service Invocation

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/service_invocation_api/)
- [OpenAPI](openapi/dapr-service-invocation-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dapr-service-invocation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dapr-service-invocation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/service-invocation/)
- [Client  Libraries](https://docs.dapr.io/sdks/)

### Dapr Bindings API

The Dapr Bindings API enables applications to trigger and invoke external resources through output bindings, and receive events from external resources through input bindings. Supported bindings include Kafka, RabbitMQ, Azure Event Hubs, AWS SQS, GCP Storage, and more.

- **Human URL:** [https://docs.dapr.io/reference/api/bindings_api/](https://docs.dapr.io/reference/api/bindings_api/)

#### Tags

- Bindings
- Event-Driven
- Integrations

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/bindings_api/)
- [OpenAPI](openapi/dapr-bindings-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dapr-bindings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dapr-bindings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/binding.json) — [JSON Schema](https://json-schema.org/specification)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/bindings/)
- [Client  Libraries](https://docs.dapr.io/sdks/)

### Dapr Secrets API

The Dapr Secrets API provides a consistent way to retrieve application secrets from various secret stores, including Hashicorp Vault, AWS Secrets Manager, Azure Key Vault, GCP Secret Manager, and Kubernetes Secrets.

- **Human URL:** [https://docs.dapr.io/reference/api/secrets_api/](https://docs.dapr.io/reference/api/secrets_api/)

#### Tags

- Key Management
- Secrets
- Security

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/secrets_api/)
- [OpenAPI](openapi/dapr-secrets-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dapr-secrets.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dapr-secrets.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/secret.json) — [JSON Schema](https://json-schema.org/specification)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/secrets/)
- [Client  Libraries](https://docs.dapr.io/sdks/)

### Dapr Actors API

The Dapr Actors API provides virtual actor capabilities for distributed applications, including actor method invocation, state management, timers, and reminders with guaranteed single-threaded execution and message ordering.

- **Human URL:** [https://docs.dapr.io/reference/api/actors_api/](https://docs.dapr.io/reference/api/actors_api/)

#### Tags

- Actors
- Distributed Systems
- Virtual Actors

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/actors_api/)
- [OpenAPI](openapi/dapr-actors-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dapr-actors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dapr-actors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/actor.json) — [JSON Schema](https://json-schema.org/specification)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/actors/)
- [Client  Libraries](https://docs.dapr.io/sdks/)

### Dapr Workflow API

The Dapr Workflow API provides the ability to manage workflow instances, including starting, getting status, pausing, resuming, terminating, purging, and raising events to workflows.

- **Human URL:** [https://docs.dapr.io/reference/api/workflow_api/](https://docs.dapr.io/reference/api/workflow_api/)

#### Tags

- Distributed Systems
- Orchestration
- Workflows

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/workflow_api/)
- [OpenAPI](openapi/dapr-workflow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dapr-workflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dapr-workflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/workflow.json) — [JSON Schema](https://json-schema.org/specification)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/workflow/)
- [Client  Libraries](https://docs.dapr.io/sdks/)

### Dapr Configuration API

The Dapr Configuration API enables applications to retrieve and subscribe to configuration items from supported configuration stores, allowing applications to react to configuration changes in real time.

- **Human URL:** [https://docs.dapr.io/reference/api/configuration_api/](https://docs.dapr.io/reference/api/configuration_api/)

#### Tags

- Configuration
- Distributed Systems
- Subscriptions

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/configuration_api/)
- [OpenAPI](openapi/dapr-configuration-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dapr-configuration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dapr-configuration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/configuration-item.json) — [JSON Schema](https://json-schema.org/specification)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/configuration/)
- [Client  Libraries](https://docs.dapr.io/sdks/)

### Dapr Distributed Lock API

The Dapr Distributed Lock API enables applications to acquire and release locks on shared resources, ensuring mutual exclusion across multiple application instances using a lease-based locking mechanism.

- **Human URL:** [https://docs.dapr.io/reference/api/distributed_lock_api/](https://docs.dapr.io/reference/api/distributed_lock_api/)

#### Tags

- Concurrency
- Coordination
- Distributed Lock

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/distributed_lock_api/)
- [OpenAPI](openapi/dapr-distributed-lock-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dapr-distributed-lock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dapr-distributed-lock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/distributed-lock/)
- [Client  Libraries](https://docs.dapr.io/sdks/)

### Dapr Cryptography API

The Dapr Cryptography API enables applications to perform cryptographic operations such as encrypting and decrypting data using configured cryptography components, without exposing cryptographic keys to the application.

- **Human URL:** [https://docs.dapr.io/reference/api/cryptography_api/](https://docs.dapr.io/reference/api/cryptography_api/)

#### Tags

- Cryptography
- Encryption
- Security

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/cryptography_api/)
- [OpenAPI](openapi/dapr-cryptography-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dapr-cryptography.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dapr-cryptography.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/cryptography/)
- [Client  Libraries](https://docs.dapr.io/sdks/)

### Dapr Jobs API

The Dapr Jobs API enables applications to schedule, retrieve, and delete jobs for future execution at specific times or intervals using cron expressions or duration specifications.

- **Human URL:** [https://docs.dapr.io/reference/api/jobs_api/](https://docs.dapr.io/reference/api/jobs_api/)

#### Tags

- Cron
- Jobs
- Scheduling

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/jobs_api/)
- [OpenAPI](openapi/dapr-jobs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dapr-jobs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dapr-jobs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/job.json) — [JSON Schema](https://json-schema.org/specification)
- [Reference](https://docs.dapr.io/developing-applications/building-blocks/jobs/)
- [Client  Libraries](https://docs.dapr.io/sdks/)

### Dapr Health API

The Dapr Health API provides health check endpoints for the Dapr sidecar, usable with container orchestrators like Kubernetes for readiness and liveness probes.

- **Human URL:** [https://docs.dapr.io/reference/api/health_api/](https://docs.dapr.io/reference/api/health_api/)

#### Tags

- Health
- Kubernetes
- Monitoring

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/health_api/)
- [OpenAPI](openapi/dapr-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dapr-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dapr-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://docs.dapr.io/operations/observability/healthchecks/)

### Dapr Metadata API

The Dapr Metadata API provides information about the Dapr sidecar, including application connection details, registered components, active subscriptions, and HTTP endpoints. It also allows setting custom metadata attributes.

- **Human URL:** [https://docs.dapr.io/reference/api/metadata_api/](https://docs.dapr.io/reference/api/metadata_api/)

#### Tags

- Metadata
- Observability
- Runtime

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/metadata_api/)
- [OpenAPI](openapi/dapr-metadata-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dapr-metadata.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dapr-metadata.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/metadata.json) — [JSON Schema](https://json-schema.org/specification)
- [Reference](https://docs.dapr.io/operations/observability/)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/daprdev)
- [Website](https://dapr.io/)
- [Documentation](https://docs.dapr.io/)
- [Getting Started](https://docs.dapr.io/getting-started/)
- [Blog](https://blog.dapr.io/)
- [GitHub Organization](https://github.com/dapr)
- [GitHub Repository](https://github.com/dapr/dapr)
- [S D Ks](https://docs.dapr.io/sdks/)
- [Community](https://discord.gg/ptHhX6jc34)
- [Changelog](https://github.com/dapr/dapr/blob/master/CHANGELOG.md)
- [Security](https://github.com/dapr/dapr/security/policy)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/dapr)
- [JSON-LD](json-ld/dapr-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/dapr-vocabulary.yml)
- [Rules](rules/dapr-rules.yml)
- [Capabilities](capabilities/dapr-capabilities.yml)
- [L L Ms Txt](https://dapr.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
