# Containerd (containerd)

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

An industry-standard container runtime with an emphasis on simplicity, robustness and portability.

**APIs.json:** [https://containerd.io/](https://containerd.io/)

## Scope

- **Type:** Index

## Tags

- Cloud Native
- Container Runtime
- CRI
- Docker
- gRPC
- Kubernetes
- OCI

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Containerd gRPC API

Core gRPC API for managing the full container lifecycle including containers, images, content, snapshots, namespaces, tasks, leases, events, and plugins. Provides low-level access to all containerd functionality through Protocol Buffers service definitions.

- **Human URL:** [https://github.com/containerd/containerd/tree/main/api](https://github.com/containerd/containerd/tree/main/api)

#### Tags

- Container Runtime
- gRPC
- Lifecycle Management

#### Properties

- [Documentation](https://containerd.io/docs/)
- [Reference](https://github.com/containerd/containerd/tree/main/api)
- [JSON Schema](json-schema/containerd-config-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/containerd-oci-runtime-spec-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/containerd-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/containerd-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Containerd CRI API

Container Runtime Interface (CRI) implementation that enables Kubernetes to use containerd as its container runtime. Supports pod sandbox management, container lifecycle operations, image pulling, and streaming APIs for exec, attach, and port-forward.

- **Human URL:** [https://github.com/containerd/containerd/tree/main/pkg/cri](https://github.com/containerd/containerd/tree/main/pkg/cri)

#### Tags

- Container Runtime
- CRI
- Kubernetes

#### Properties

- [Documentation](https://containerd.io/docs/)
- [Reference](https://github.com/containerd/containerd/tree/main/pkg/cri)
- [JSON Schema](json-schema/containerd-config-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/containerd-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/containerd-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Containerd Metrics API

The containerd metrics plugin exposes a Prometheus-compatible HTTP endpoint for scraping runtime metrics. When enabled via the metrics.address configuration option in config.toml, it serves Prometheus text format metrics covering gRPC request counts, latency histograms, snapshot usage, content store statistics, and task lifecycle events.

- **Human URL:** [https://containerd.io/docs/](https://containerd.io/docs/)

#### Tags

- Metrics
- Observability
- Prometheus

#### Properties

- [Documentation](https://containerd.io/docs/)
- [OpenAPI](openapi/containerd-metrics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/containerd-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/containerd-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Containerd NRI API

The Node Resource Interface (NRI) is a framework for plugging extensions into OCI-compatible container runtimes. NRI plugins receive lifecycle event notifications and can make controlled modifications to container configurations before creation, enabling domain-specific resource management without modifying the runtime itself.

- **Human URL:** [https://github.com/containerd/nri](https://github.com/containerd/nri)

#### Tags

- Extensibility
- Kubernetes
- NRI
- Plugins

#### Properties

- [Documentation](https://github.com/containerd/containerd/blob/main/docs/NRI.md)
- [GitHub Repository](https://github.com/containerd/nri)
- [Postman Collection](collections/containerd-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/containerd-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://containerd.io/)
- [Documentation](https://containerd.io/docs/)
- [Getting Started](https://containerd.io/docs/getting-started/)
- [GitHub Organization](https://github.com/containerd)
- [GitHub Repository](https://github.com/containerd/containerd)
- [Changelog](https://github.com/containerd/containerd/releases)
- [Community](https://cloud-native.slack.com/)
- [C N C F  Project](https://www.cncf.io/projects/containerd/)
- [License](https://github.com/containerd/containerd/blob/main/LICENSE)
- [JSON-LD](json-ld/containerd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/containerd-config-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/containerd-oci-runtime-spec-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](rules/containerd-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
