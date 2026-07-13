# Asim Abdalla

### Infrastructure & Realtime Architect

> Systems that survive load, failure, and time.

Senior backend/platform engineer (7+ years) focused on architecture that survives load, failure, and time. I lead design and delivery across multi-tenant SaaS, realtime connection planes, and cloud platforms on **GCP** and **Cloudflare**, with earlier **AWS** production ownership. Day-to-day toolkit: Kubernetes/GKE, Terraform, GitOps, PostgreSQL, Redis, TypeScript/Node.js, Laravel/PHP, observability, and high-volume HTTP/WebSocket systems.

Most recent production systems live in private company repositories. Public work below is **reference engineering** that proves the same decision quality without exposing employer or customer code.

## Production impact (professional systems)

| Signal | Result |
| --- | --- |
| HTTP plane | ~**4M requests/day** on multi-tenant education platforms |
| Realtime plane | **12M+ WebSocket connection sessions/day** |
| Cloud migration | **AWS → GCP** production cutover with ~**20 minutes** controlled downtime |
| Leadership | Architecture direction, standards, reviews, mentoring, hiring |

## Public engineering evidence

| Repository | What it proves |
| --- | --- |
| [spring-payments-platform](https://github.com/asim-altayb/spring-payments-platform) | Java 17 / Spring Boot payments reference: idempotent transfers, immutable double-entry ledger, optimistic concurrency, transactional outbox, JWT scopes, signed webhooks, Testcontainers CI |
| [realtime-platform-blueprint](https://github.com/asim-altayb/realtime-platform-blueprint) | Working WebSocket reference: tenant isolation, presence, backpressure, rate limits, Redis fan-out, metrics, load tests |
| [production-platform-blueprints](https://github.com/asim-altayb/production-platform-blueprints) | Sanitized platform patterns: Terraform modules, GKE defaults, Argo CD GitOps, observability, incident/rollback runbooks |
| [whatsapp-api-laravel](https://github.com/asim-altayb/whatsapp-api-laravel) | Production-oriented Laravel package for WhatsApp Cloud API integrations |

### Engineering gists (concise patterns)

- [Spring/PostgreSQL idempotency](https://gist.github.com/asim-altayb/077acb1802780b7f8dca56a42a19c5fa)
- [Outbox worker + `FOR UPDATE SKIP LOCKED`](https://gist.github.com/asim-altayb/f9fe196f3cbe15ab23bae1ce5dd560f3)
- [Optimistic concurrency + safe retry](https://gist.github.com/asim-altayb/c5861df4a3efeb22656dd24b3b68eb2a)
- [Spring Security JWT scopes](https://gist.github.com/asim-altayb/607e1fa67a2ed79e7cbf9a0918611041)
- [HMAC webhook signing](https://gist.github.com/asim-altayb/4877e49dd5396082e1e463573fc6c271)
- [PostgreSQL immutable ledger constraints](https://gist.github.com/asim-altayb/4ab544e0728fce8aa81a920bf501c80f)

## Systems I design

| Area | Toolkit |
| --- | --- |
| Platforms & delivery | GKE, Cloud Run, Cloudflare Workers, Terraform, GitOps (Argo CD), private networking, Workload Identity |
| Realtime | WebSockets, Durable Objects patterns, Soketi/Redis fan-out, tenant isolation, backpressure |
| Reliability | Grafana / Prometheus / Loki, autoscaling, capacity planning, failure recovery, runbooks |
| Application & data | Laravel Octane, TypeScript/Node.js, PostgreSQL, Redis, Cloud SQL |

## Case studies (production experience, private code)

### Realtime delivery platforms
Designed and operated multi-tenant realtime infrastructure (Cloudflare Durable Objects and GKE/Soketi/Redis paths) with autoscaling, network isolation, independent deploy pipelines, and reconnect-friendly client contracts—supporting eight-figure daily session volume.

### Multi-tenant HTTP platforms
Architecture leadership for education SaaS operating at multi-million daily HTTP request volume: service boundaries, database capacity tactics, observability, and delivery safety.

### AWS → GCP migration
Led production migration coordinating application, data, DNS, and infrastructure cutover with infrastructure-as-code, GitOps delivery, and end-to-end observability. Cutover measured in minutes (~20) for the controlled maintenance window.

## How I work

- Architecture should make failure explicit and recovery boring.
- Observability is part of the design, not an afterthought.
- The best platform removes operational work from product teams.
- Performance, security, and cost are engineering constraints—not cleanup tasks.
- Public portfolio code is honest about scope: strong mechanisms, not fake product surface area.

## Connect

Saudi Arabia · [LinkedIn](https://www.linkedin.com/in/asim-abdallah/) · [GitHub](https://github.com/asim-altayb) · [sudoasim.dev](https://sudoasim.dev)
