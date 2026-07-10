# Asim Abdalla

### Infrastructure & Realtime Architect

> Systems that survive load, failure, and time.

I’m a Tech Lead responsible for architecture direction, engineering standards, reviews, roadmap decisions, mentoring, and hiring across production platforms where cloud infrastructure, realtime communication, and application architecture meet. My work spans GCP and Cloudflare, with earlier AWS experience, from Kubernetes and multi-tenant SaaS to WebSocket delivery platforms.

I care about clear failure modes, observable systems, safe delivery, and infrastructure that becomes easier—not harder—to operate as it grows.

## Selected impact

- Designed realtime infrastructure supporting **eight-figure daily WebSocket session volume**.
- Led platform architecture for a multi-tenant education product operating at **multi-million daily HTTP request volume**.
- Led an **AWS-to-GCP production migration** with a controlled cutover measured in minutes.

## Systems I build

| Area | Production toolkit |
| --- | --- |
| Platforms & security | GKE, Cloud Run, Cloudflare Workers, Terraform, GitOps, private networking, workload isolation |
| Realtime | Durable Objects, WebSockets, RealtimeKit, Soketi, Redis |
| Reliability | Grafana [loki - mimir, logs and metrics], autoscaling, capacity planning, failure recovery |
| Application & data | Laravel Octane, TypeScript/Node.js, PostgreSQL, Cloud SQL, Meilisearch |

## Engineering case studies

### Realtime delivery platforms

Designed realtime platforms on Cloudflare Durable Objects and on GKE/Soketi, using Redis-backed horizontal scaling where applicable, autoscaling, network isolation, and independent deployment pipelines.

### Elastic database capacity

Designed health-aware read-replica scaling and routing for bursty database workloads, including safe draining, storage-aware provisioning, and tests derived from production failure modes.

### Multi-cloud platform migration

Moved production workloads from AWS to GCP while coordinating application, data, DNS, and infrastructure cutover. The target platform uses infrastructure as code, GitOps delivery, and end-to-end observability.

## How I work

- Architecture should make failure explicit and recovery boring.
- Observability is part of the design, not an afterthought.
- The best platform removes operational work from product teams.
- Performance, security, and cost are engineering constraints—not cleanup tasks.

Most of my recent production work lives in private company repositories, so the examples here describe the engineering decisions without exposing customer code or internal systems.

## Connect

Saudi Arabia · [LinkedIn](https://www.linkedin.com/in/asim-abdallah/)
