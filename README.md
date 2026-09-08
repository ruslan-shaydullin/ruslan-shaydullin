# Ruslan Shaydullin

**Senior DevOps Engineer · Kubernetes, GitOps & reliability**

I build and operate delivery platforms for fintech systems, and contribute fixes to the tools behind them. Six years in production infrastructure; currently at **Innotech**, based in **Astana, Kazakhstan**.

[LinkedIn](https://www.linkedin.com/in/ruslan-shaydullin-80030a28b) · [Email](mailto:shaydullin.r.d@outlook.com) · [Contribution notes](https://github.com/ruslan-shaydullin/ruslan-shaydullin/blob/main/CONTRIBUTIONS.md)

## Selected upstream work

These changes were **merged upstream**. Each link opens the implementation, tests, and maintainer discussion.

| Project | What I contributed |
| :--- | :--- |
| **[Helm · #32281](https://github.com/helm/helm/pull/32281)** | Implemented Go parsing of GnuPG `pubring.kbx` keyrings for chart provenance verification, with bounds checks, malformed-input tests, and legacy-keyring compatibility. |
| **[Flux source-controller · #2127](https://github.com/fluxcd/source-controller/pull/2127)** | Added OCI source revisions to event metadata so notification consumers can correlate artifacts with source commits; included controller tests and documentation. |
| **[Flux CLI · #5885](https://github.com/fluxcd/flux2/pull/5885)** | Added `--add-ignore-paths` to artifact build, push, and diff commands to extend existing exclusions; covered flag combinations with tests. |

Also contributed [test cleanup to the OpenTelemetry Collector](https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/49676). [Browse my merged pull requests →](https://github.com/pulls?q=is%3Apr+is%3Amerged+author%3Aruslan-shaydullin+-user%3Aruslan-shaydullin)

## Production experience

- **Migration:** led the move of 100+ microservices from OpenShift to Kubernetes across 10 clusters serving 15,000+ RPS, with a zero-downtime production traffic cutover.
- **Delivery:** replaced Jinja2/Ansible deployment flows with versioned Helm charts and unified rollback procedures; built a pipeline that halved publication time.
- **Efficiency:** reduced private-cloud resource consumption by 25% while maintaining a 99.9% SLO.
- **Operations:** Istio mTLS and authorization policies, TLS rotation, production on-call, blameless incident reviews, and mentoring seven engineers.

## What I build

**[Crewboss](https://github.com/ruslan-shaydullin/crewboss)** — an experimental framework for coordinating coding agents with role-based permissions, task orchestration, a web dashboard, and review/CI gates. The repository contains the reference runtime, tests, and architecture notes.

**Quarter** — a personal finance app in development. Building the native iOS client with SwiftUI and SwiftData, a transactional outbox for sync retries, and budget indicators that compare spending with elapsed time. Source is currently private.

## Toolbox

| Area | Tools |
| :--- | :--- |
| Platforms | Kubernetes, OpenShift, Docker, Istio, Linux |
| Delivery & infrastructure | Helm, Terraform, Ansible, Jenkins, TeamCity, AWS, OpenStack |
| Observability & data | Prometheus, Grafana, Elastic Stack, Kafka, PostgreSQL, Redis |
| Code | Go for upstream contributions; Python, Bash, Groovy, Java, SQL |

## Work with me

Interested in Senior DevOps, SRE, and infrastructure roles: **remote from Kazakhstan** through B2B/EOR, or employer-sponsored relocation. English C1; Russian native.

[Get in touch](mailto:shaydullin.r.d@outlook.com) · [Professional background on LinkedIn](https://www.linkedin.com/in/ruslan-shaydullin-80030a28b)
