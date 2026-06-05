# Containerd (containerd)

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
