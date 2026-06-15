# Knative (knative)

Knative is a CNCF graduated platform that extends Kubernetes to provide serverless capabilities. It consists of Serving for deploying and scaling serverless workloads with automatic scale-to-zero, and Eventing for building event-driven architectures with declarative event routing and delivery. Knative abstracts away infrastructure complexity so developers can focus on writing code.

**APIs.json:** [https://knative.dev](https://knative.dev)

## Scope

- **Type:** Index

## Tags

- Auto-Scaling
- Cloud Native
- Event-Driven
- Graduated
- Kubernetes
- Serverless

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Knative Serving API

Knative Serving extends the Kubernetes API with custom resources for deploying serverless workloads. The Service, Route, Configuration, and Revision resources enable automatic scaling including scale-to-zero, traffic splitting between revisions, and progressive rollouts. Serving handles container lifecycle, networking, and autoscaling automatically.

- **Human URL:** [https://knative.dev/docs/serving/](https://knative.dev/docs/serving/)

#### Tags

- Auto-Scaling
- Serverless
- Serving

#### Properties

- [Documentation](https://knative.dev/docs/serving/)
- [Reference](https://knative.dev/docs/serving/reference/serving-api/)
- [GitHub Repository](https://github.com/knative/serving)
- [OpenAPI](openapi/knative-serving-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/knative-serving-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/knative-serving-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/knative-serving-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Knative Eventing API

Knative Eventing provides a set of Kubernetes custom resources for building event-driven architectures. It includes Broker and Trigger resources for event routing, Channel and Subscription for pub/sub messaging, and source resources for connecting external event producers to the eventing mesh. Events conform to the CloudEvents specification.

- **Human URL:** [https://knative.dev/docs/eventing/](https://knative.dev/docs/eventing/)

#### Tags

- Event-Driven
- Events
- Pub/Sub

#### Properties

- [Documentation](https://knative.dev/docs/eventing/)
- [Reference](https://knative.dev/docs/eventing/reference/eventing-api/)
- [GitHub Repository](https://github.com/knative/eventing)
- [OpenAPI](openapi/knative-eventing-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/knative-eventing-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/knative-eventing-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/knative-cloudevents-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/knative-eventing-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Knative Functions

Knative Functions enables developers to create, build, and deploy stateless, event-driven functions as Knative Services using the func CLI or the kn func plugin. Functions can be written in multiple languages and are automatically deployed as auto-scaling Knative Services that respond to HTTP requests or CloudEvents.

- **Human URL:** [https://knative.dev/docs/functions/](https://knative.dev/docs/functions/)

#### Tags

- CLI
- Event-Driven
- Functions
- Serverless

#### Properties

- [Documentation](https://knative.dev/docs/functions/)
- [Getting Started](https://knative.dev/docs/getting-started/about-knative-functions/)
- [GitHub Repository](https://github.com/knative/func)
- [Postman Collection](collections/knative-eventing-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/knative-eventing-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/knative-serving-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/knative-serving-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Knative CLI (kn)

The Knative CLI (kn) provides a command-line interface for creating and managing Knative resources including Services, Revisions, Routes, event sources, and Brokers. It simplifies tasks like traffic splitting and autoscaling configuration without requiring direct YAML editing.

- **Human URL:** [https://knative.dev/docs/client/](https://knative.dev/docs/client/)

#### Tags

- CLI
- Developer Tools
- Kubernetes

#### Properties

- [Documentation](https://knative.dev/docs/client/)
- [GitHub Repository](https://github.com/knative/client)
- [Postman Collection](collections/knative-eventing-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/knative-eventing-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/knative-serving-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/knative-serving-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/knative)
- [JSON-LD](json-ld/knative-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Website](https://knative.dev/)
- [Documentation](https://knative.dev/docs/)
- [Getting Started](https://knative.dev/docs/getting-started/)
- [Blog](https://knative.dev/blog/)
- [Changelog](https://knative.dev/docs/reference/relnotes/)
- [GitHub Organization](https://github.com/knative)
- [GitHub Repository](https://github.com/knative/docs)
- [Community](https://knative.dev/community/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
