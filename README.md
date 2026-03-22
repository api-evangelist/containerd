# Containerd (containerd)
An industry-standard container runtime with an emphasis on simplicity, robustness and portability

**URL:** [Visit APIs.json URL](https://containerd.io/)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Container Runtime, Cloud Native, Kubernetes, Docker, OCI, gRPC, CRI

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-03-18 

## APIs

### Containerd gRPC API
Core gRPC API for managing the full container lifecycle including containers, images, content, snapshots, namespaces, tasks, leases, events, and plugins. Provides low-level access to all containerd functionality through Protocol Buffers service definitions.

**Human URL:** [https://github.com/containerd/containerd/tree/main/api](https://github.com/containerd/containerd/tree/main/api)


#### Tags:

 - gRPC, Container Runtime, Lifecycle Management

#### Properties

- [Documentation](https://containerd.io/docs/)
- [Reference](https://github.com/containerd/containerd/tree/main/api)
- [JSONSchema](json-schema/containerd-config-schema.json)
- [JSONSchema](json-schema/containerd-oci-runtime-spec-schema.json)

### Containerd CRI API
Container Runtime Interface (CRI) implementation that enables Kubernetes to use containerd as its container runtime. Supports pod sandbox management, container lifecycle operations, image pulling, and streaming APIs for exec, attach, and port-forward.

**Human URL:** [https://github.com/containerd/containerd/tree/main/pkg/cri](https://github.com/containerd/containerd/tree/main/pkg/cri)


#### Tags:

 - CRI, Kubernetes, Container Runtime

#### Properties

- [Documentation](https://containerd.io/docs/)
- [Reference](https://github.com/containerd/containerd/tree/main/pkg/cri)
- [JSONSchema](json-schema/containerd-config-schema.json)

### Containerd Metrics API
The containerd metrics plugin exposes a Prometheus-compatible HTTP endpoint for scraping runtime metrics. When enabled via the metrics.address configuration option in config.toml, it serves Prometheus text format metrics covering gRPC request counts, latency histograms, snapshot usage, content store statistics, and task lifecycle events.

**Human URL:** [https://containerd.io/docs/](https://containerd.io/docs/)


#### Tags:

 - Metrics, Prometheus, Observability

#### Properties

- [Documentation](https://containerd.io/docs/)
- [OpenAPI](openapi/containerd-metrics-openapi.yml)

### Containerd NRI API
The Node Resource Interface (NRI) is a framework for plugging extensions into OCI-compatible container runtimes. NRI plugins receive lifecycle event notifications and can make controlled modifications to container configurations before creation, enabling domain-specific resource management without modifying the runtime itself.

**Human URL:** [https://github.com/containerd/nri](https://github.com/containerd/nri)


#### Tags:

 - NRI, Plugins, Extensibility, Kubernetes

#### Properties

- [Documentation](https://github.com/containerd/containerd/blob/main/docs/NRI.md)
- [GitHubRepository](https://github.com/containerd/nri)

## Common Properties

- [Website](https://containerd.io/)
- [Documentation](https://containerd.io/docs/)
- [Getting Started](https://containerd.io/docs/getting-started/)
- [GitHub Organization](https://github.com/containerd)
- [GitHubRepository](https://github.com/containerd/containerd)
- [Change Log](https://github.com/containerd/containerd/releases)
- [Community](https://cloud-native.slack.com/)
- [JSON-LD](json-ld/containerd-context.jsonld)
- [JSONSchema](json-schema/containerd-config-schema.json)
- [JSONSchema](json-schema/containerd-oci-runtime-spec-schema.json)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
