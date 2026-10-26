# Knative (knative)

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
