# Knative

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

**Areas:** Auto-Scaling · Cloud-Native · Event-Driven · Graduated · Kubernetes · Serverless

## Knative on APIs.io

Everything profiled for Knative is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/knative/](https://apis.io/providers/knative/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [Knative Functions](https://apis.io/apis/knative/knative-functions/) — Knative Functions enables developers to create, build, and deploy stateless, event-driven functions as Knative Services using the func CLI or the kn func…
- [Knative CLI (kn)](https://apis.io/apis/knative/knative-cli/) — The Knative CLI (kn) provides a command-line interface for creating and managing Knative resources including Services, Revisions, Routes, event sources, and…
- [Knative Brokers API](https://apis.io/apis/knative/knative-brokers-api/) — Knative Broker resources collect pools of events that can be consumed using Triggers. Brokers provide event routing with filtering, guaranteed delivery, and…
- [Knative Channels API](https://apis.io/apis/knative/knative-channels-api/) — Knative Channel resources represent a generic pub/sub messaging channel. Channels receive events and fan them out to all Subscriptions. The default channel…
- [Knative Configurations API](https://apis.io/apis/knative/knative-configurations-api/) — Knative Configuration resources maintain the desired state for a deployment by capturing container templates. Each update to a Configuration creates a new…
- [Knative DomainMappings API](https://apis.io/apis/knative/knative-domainmappings-api/) — Knative DomainMapping resources map a custom domain name to a Knative Service, enabling services to be served under custom hostnames with automatic TLS…
- [Knative Revisions API](https://apis.io/apis/knative/knative-revisions-api/) — Knative Revision resources are immutable snapshots of application code and configuration at a point in time. Revisions are created by Configuration updates…
- [Knative Routes API](https://apis.io/apis/knative/knative-routes-api/) — Knative Route resources manage the network endpoints and traffic distribution across Revisions. Routes support percentage-based traffic splitting for canary…
- [Knative Subscriptions API](https://apis.io/apis/knative/knative-subscriptions-api/) — Knative Subscription resources define a delivery destination for events sent to a Channel. Each Subscription routes events from a Channel to a subscriber…
- [Knative Triggers API](https://apis.io/apis/knative/knative-triggers-api/) — Knative Trigger resources define filtered delivery options for events arriving at a Broker. A Trigger selects events by attribute filters and routes…
- [Knative APIS API](https://apis.io/apis/knative/knative-apis-api/) — The Apis API from Knative — 2 operation(s) for apis.
- [Knative Event Sources API](https://apis.io/apis/knative/knative-event-sources-api/) — Knative event source resources connect external event producers to the eventing mesh. Built-in sources include ApiServerSource for Kubernetes API events,…
- [Knative Event Types API](https://apis.io/apis/knative/knative-event-types-api/) — Knative EventType resources maintain a catalog of event types that can be consumed from Brokers. EventTypes help consumers discover what events are…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Knative Eventing CloudEvents](https://apis.io/asyncapis/knative/knative-cloudevents-asyncapi/)

#### Event channels (3)

Individual events and webhooks the provider emits.

- [/broker](https://apis.io/channels/knative/broker/)
- [/channel](https://apis.io/channels/knative/channel/)
- [/sink](https://apis.io/channels/knative/sink/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Knative Agentic Access](https://apis.io/agentic-access/knative/knative-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Knative Eventing Resources](https://apis.io/schemas/knative/knative-eventing/)
- [Knative Serving Resources](https://apis.io/schemas/knative/knative-serving/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Knative Context](https://apis.io/jsonld/knative/knative-context/)

#### Collections (24)

Postman and Open Collection request collections.

- [Knative Eventing Apis API](https://apis.io/collections/knative/open-knative-apis-api/)
- [Knative Eventing Apis Brokers API](https://apis.io/collections/knative/open-knative-brokers-api/)
- [Knative Eventing Apis Channels API](https://apis.io/collections/knative/open-knative-channels-api/)
- [Knative Eventing Apis Configurations API](https://apis.io/collections/knative/open-knative-configurations-api/)
- [Knative Eventing Apis DomainMappings API](https://apis.io/collections/knative/open-knative-domainmappings-api/)
- [Knative Eventing API](https://apis.io/collections/knative/open-knative-eventing-api/)
- [Knative Eventing Apis EventSources API](https://apis.io/collections/knative/open-knative-eventsources-api/)
- [Knative Eventing Apis EventTypes API](https://apis.io/collections/knative/open-knative-eventtypes-api/)
- [Knative Eventing Apis Revisions API](https://apis.io/collections/knative/open-knative-revisions-api/)
- [Knative Eventing Apis Routes API](https://apis.io/collections/knative/open-knative-routes-api/)
- [Knative Serving API](https://apis.io/collections/knative/open-knative-serving-api/)
- [Knative Eventing Apis Subscriptions API](https://apis.io/collections/knative/open-knative-subscriptions-api/)
- [Knative Eventing Apis Triggers API](https://apis.io/collections/knative/open-knative-triggers-api/)
- [Knative Eventing Apis API](https://apis.io/collections/knative/postman-knative-apis-api/)
- [Knative Eventing Apis Brokers API](https://apis.io/collections/knative/postman-knative-brokers-api/)
- [Knative Eventing Apis Channels API](https://apis.io/collections/knative/postman-knative-channels-api/)
- [Knative Eventing Apis Configurations API](https://apis.io/collections/knative/postman-knative-configurations-api/)
- [Knative Eventing Apis DomainMappings API](https://apis.io/collections/knative/postman-knative-domainmappings-api/)
- [Knative Eventing Apis EventSources API](https://apis.io/collections/knative/postman-knative-eventsources-api/)
- [Knative Eventing Apis EventTypes API](https://apis.io/collections/knative/postman-knative-eventtypes-api/)
- [Knative Eventing Apis Revisions API](https://apis.io/collections/knative/postman-knative-revisions-api/)
- [Knative Eventing Apis Routes API](https://apis.io/collections/knative/postman-knative-routes-api/)
- [Knative Eventing Apis Subscriptions API](https://apis.io/collections/knative/postman-knative-subscriptions-api/)
- [Knative Eventing Apis Triggers API](https://apis.io/collections/knative/postman-knative-triggers-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Knative — asyncapi rules](https://apis.io/rules/knative/knative-asyncapi-spectral-rules/)
- [Knative — jsonschema rules](https://apis.io/rules/knative/knative-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Knative Authentication](https://apis.io/security/knative/knative-authentication/)
- [Knative Domain Security](https://apis.io/security/knative/knative-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Knative Plans Pricing](https://apis.io/plans/knative/knative-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Knative Rate Limits](https://apis.io/rate-limits/knative/knative-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Knative Finops](https://apis.io/finops/knative/knative-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://knative.dev/)
- [Documentation](https://knative.dev/docs/)
- [Getting started](https://knative.dev/docs/getting-started/)
- [Changelog](https://knative.dev/docs/reference/relnotes/)
- [Blog](https://knative.dev/blog/)
- [GitHub](https://github.com/knative)

## API Evangelist rating

**Kin Score 47.1** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 68.8 |
| Contract governance | 13.6 |
| Operational transparency | 39.5 |
| Developer ergonomics | 48.8 |
| Access clarity | 7.9 |

**Agent readiness 23.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/knative/](https://apis.io/providers/knative/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Knative: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/knative/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
