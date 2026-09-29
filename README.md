# Hi, I'm Shane 👋

> 🧭 A CIO and CIDO who still builds: business-driven technology and digital strategy, backed by hands-on infrastructure and code.

I'm a technology and digital strategy executive who happens to be a well-rounded infrastructure
engineer, systems integrator and application designer. I work in healthcare IT today, but the
work carries to any industry. What I build here is automation, AI tooling, libraries, plugins,
charts and CI actions, made for anyone to use, not only for my own work. I write mostly **Go** and
**TypeScript**, with some Python and shell. I lead best when strategy and delivery sit in the same
room, and these repos are where I keep my hands on the delivery side. Issues and pull requests are
welcome on any of the repos below.

## ✨ Highlights

- 🤖 **Automation and AI tooling:** release, changelog, documentation and repository automation that keeps a portfolio of projects moving with little hand work.
- 🧰 **Go helper packages:** small building blocks for Go services, covering logging, tracing, errors, databases and messaging.
- 🏥 **HL7 v2 in Go and Node:** message builders, MLLP clients and servers, and Fastify plugins for healthcare integration.
- ☸️ **Kubernetes and DNS:** Helm charts and an ExternalDNS provider for self-hosted clusters.
- 🚀 **Release automation:** GitHub Actions for changelogs and versioned documentation.

## 🐹 Go

### Helper packages

- [go-apperr](https://github.com/Bugs5382/go-apperr): coded application errors with stable, reportable numeric codes and pluggable logging and tracing.
- [go-authz](https://github.com/Bugs5382/go-authz): a small, dependency-free authorization engine with composable rules, RBAC and a responsibility matrix.
- [go-certkit](https://github.com/Bugs5382/go-certkit): parse, inspect and convert X.509 certificate and key containers (PEM, DER, PKCS#12, PKCS#7, JKS).
- [go-email](https://github.com/Bugs5382/go-email): a dependency-light email client with RFC 5322 envelopes, multipart rendering and middleware over a pluggable transport.
- [go-log](https://github.com/Bugs5382/go-log): zerolog logging for Go services with OpenTelemetry trace correlation.
- [go-otel](https://github.com/Bugs5382/go-otel): a small OpenTelemetry bootstrap for Go services.
- [go-postgres](https://github.com/Bugs5382/go-postgres): PostgreSQL wiring with a tuned pgxpool, health checks and transactions that retry serialization failures.
- [go-rabbitmq](https://github.com/Bugs5382/go-rabbitmq): RabbitMQ connections, publishers and consumers that reconnect on their own.
- [go-redis](https://github.com/Bugs5382/go-redis): resilient Redis connections with sentinel failover and health checks.
- [go-seed](https://github.com/Bugs5382/go-seed): an idempotent database seed runner whose ordered steps verify the rows they claim to seed.

### Libraries

- [go-hl7](https://github.com/Bugs5382/go-hl7): an HL7 v2.x library with a typed message builder, an MLLP/TLS client and server, batch support and the full value tables.
- [go-saga-orchestration](https://github.com/Bugs5382/go-saga-orchestration): a saga orchestrator and CEL rule evaluator, embedded as a library or run as a service.
- [go-astronomy](https://github.com/Bugs5382/go-astronomy): observer-aware sun, moon, star and constellation positions, twilight bands and moon phases.
- [go-weather](https://github.com/Bugs5382/go-weather): a provider-agnostic weather vocabulary with Open-Meteo, NWS and NOAA SWPC adapters.

## ⚡ Fastify and Node

- [fastify-rabbitmq](https://github.com/Bugs5382/fastify-rabbitmq): a Fastify plugin for RabbitMQ, built on amqplib.
- [fastify-hl7](https://github.com/Bugs5382/fastify-hl7): a Fastify plugin for sending and receiving HL7 v2 messages over MLLP.
- [node-hl7](https://github.com/Bugs5382/node-hl7): the Node.js HL7 client and server packages in one monorepo.
- [node-astronomy](https://github.com/Bugs5382/node-astronomy): astronomy data for the sun, moon and planets as an npm package.
- [saga-flow-designer](https://github.com/Bugs5382/saga-flow-designer): React components for viewing and editing saga-orchestration workflows and runs.

## ☸️ Helm and Kubernetes

- [helm-gitlab](https://github.com/Bugs5382/helm-gitlab): a self-hosted GitLab chart that brings its own PostgreSQL HA, Valkey, SeaweedFS and Traefik.
- [helm-technitium-chart](https://github.com/Bugs5382/helm-technitium-chart): run the Technitium DNS server on Kubernetes.
- [external-dns-technitium-webhook](https://github.com/Bugs5382/external-dns-technitium-webhook): a Technitium provider for ExternalDNS.

## 🤖 GitHub Actions

- [changelog-updater-action](https://github.com/Bugs5382/changelog-updater-action): updates `CHANGELOG.md` from the release-drafter notes for each release.
- [typedoc-pages-action](https://github.com/Bugs5382/typedoc-pages-action): builds versioned TypeDoc sites and publishes them to GitHub Pages, keeping every version.

## 🧠 Claude

### Status line

- [claude-code-statusline-usage](https://github.com/Bugs5382/claude-code-statusline-usage): a Claude Code status line that shows plan usage (session and weekly) and saves it for scripts to read.

## 🛠 Tools

- [golic](https://github.com/Bugs5382/golic): injects license headers into source files, and checks them in CI.
- [project-learning-lessons](https://github.com/Bugs5382/project-learning-lessons): the code from my lessons and videos, free to reuse.

## 🏢 Organizations

- [the-rabbit-hole-tech](https://github.com/the-rabbit-hole-tech): shared tooling for my Node projects, including [eslint-config](https://github.com/the-rabbit-hole-tech/eslint-config) and [docs-theme](https://github.com/the-rabbit-hole-tech/docs-theme).
- [CryptOS-PKI](https://github.com/CryptOS-PKI): an immutable, API-driven PKI operating system. It applies the Talos Linux approach to certificate authorities: no SSH, no shell, mTLS gRPC only, and CA keys sealed in the TPM.
