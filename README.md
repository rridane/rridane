# rridane 

> Designing and building end-to-end systems, from resilient cloud-native backends to high-performance front-ends.

Here you'll find the tools I use daily to:

- Build and operate state-of-the-art cloud-native platforms
- Improve developer experience and deployment metrics
- Design high-performance applications, front to back
- Mentor junior and senior engineers

A curated set of modular tools covering the full lifecycle of a platform: provisioning, delivery, observability, security and identity, developer experience. I build with them and run them in production.

## Cluster provisioning (OVH / Hetzner / kubeadm / RKE2)

- [terraform-ovh-k8s-infra](https://github.com/rridane/terraform-ovh-k8s-infra): hybrid Public Cloud and bare-metal over vRack, with L2 VIPs (kube-vip, Cilium) instead of a managed load balancer
- [terraform-hcloud-k8s-infra](https://github.com/rridane/terraform-hcloud-k8s-infra): Hetzner Kubernetes infrastructure, with etcd-quorum and CIDR validations
- [k8s-bootstrap-framework](https://github.com/rridane/k8s-bootstrap-framework): kubeadm and RKE2 bootstrap. Step catalogue, Go runner with plan-before-apply.

## Infrastructure as code (Ansible)

- [ansible-kubernetes-admin](https://github.com/rridane/ansible-kubernetes-admin): bootstrap HA Kubernetes clusters (admins, masters, workers, load balancers)
- [ansible-base-systems](https://github.com/rridane/ansible-base-systems): base system configuration for Linux environments

## Pipelines and automation (Go)

- [golang-pipeyard](https://github.com/rridane/golang-pipeyard): a Go framework that treats CI/CD as a product. Typed stages compiled to one binary per organization, automatic dependency injection, native DORA metrics, SLSA-attested releases.

## Terraform cloud-native kit

- [terraform-kubernetes-cloudnative-kit](https://github.com/rridane/terraform-kubernetes-cloudnative-kit): a Terraform module collection for cloud-native components.
  - [OpenTelemetry Collector generator](https://github.com/rridane/terraform-kubernetes-cloudnative-kit/tree/main/modules/monitoring-opentelemetry)
  - [Bind9 and DNS publication](https://github.com/rridane/terraform-kubernetes-cloudnative-kit/tree/main/modules/networking-bind9)
  - [Ingress route management](https://github.com/rridane/terraform-kubernetes-cloudnative-kit/tree/main/modules/networking-ingress-route-transformer)
  - [Cert-Manager TLS](https://github.com/rridane/terraform-kubernetes-cloudnative-kit/tree/main/modules/security-cert-manager)
  - [Vault policies, roles and secrets engines (PKI)](https://github.com/rridane/terraform-kubernetes-cloudnative-kit/tree/main/modules/security-vault)

## Helm and ArgoCD cloud-native components

- [CloudNativePG](https://github.com/rridane/helm-argocd-cloudnative-kit/tree/main/cloudnative-pg): production Postgres-as-a-service. HA bootstrap, backup and PITR, connection pooler.
- [OpenTelemetry](https://github.com/rridane/helm-argocd-cloudnative-kit/tree/main/opentelemetry): collector and agent with tail sampling, spanmetrics and k8sattributes, into Mimir, Loki, Tempo and Pyroscope
- [otlp-replay](https://github.com/rridane/otlp-replay): a companion Python tool. Replays archived OpenTelemetry traces into an Apache Iceberg table, idempotent per period, hexagonal (five ports), contract-tested across in-memory, Ray and Iceberg.
- [Rancher RBAC](https://github.com/rridane/helm-argocd-cloudnative-kit/tree/main/rancher-rbac): declarative, multi-cluster RBAC as code
- [Gateway HTTP routes](https://github.com/rridane/helm-argocd-cloudnative-kit/tree/main/gateway-http-routes): Gateway API HTTPRoute management
- [Parca](https://github.com/rridane/helm-argocd-cloudnative-kit/tree/main/parca): continuous CPU and memory profiling
- [Filebrowser](https://github.com/rridane/helm-argocd-cloudnative-kit/tree/main/filebrowser): web-based file browser for teams

## Engineering deep-dives

Technical sheets and deep dives I write to teach and document. They explain complex concepts clearly and serve as practical material for engineering teams.

Systems and networking

- [HTTP/1 to HTTP/3 and gRPC](https://github.com/rridane/public-notes-rr/blob/main/networking/protocols/from_http_to_http3_and_grpc.adoc): a deep dive on gRPC and HTTP/3, starting from HTTP/1 (Advanced)
- [Linux kernel networking (L2/L3)](https://github.com/rridane/public-notes-rr/blob/main/networking/linux_kernel_networking.adoc): how a packet travels through the Linux kernel, end to end (Advanced)
- [Kubernetes networking from scratch](https://github.com/rridane/public-notes-rr/blob/main/devops/kubernetes_networking.adoc): CNI, services, network policies, overlay and underlay (Intermediate/Advanced)
- [DNS, from zones to DNSSEC](https://github.com/rridane/public-notes-rr/blob/main/networking/protocols/dns/dns_advanced.adoc): zones, TTL and resolution, through delegations and DNSSEC. [Basics here](https://github.com/rridane/public-notes-rr/blob/main/networking/protocols/dns/dns_basic_overview.adoc). (Beginner to Advanced)

Software architecture and internals

- [Flutter framework internals](https://github.com/rridane/public-notes-rr/blob/main/frontend/flutter/deep_dive_flutter_internal_framework.adoc): internal bindings, build pipeline, scheduler mechanics (Advanced)
- [Flutter gesture handling](https://github.com/rridane/public-notes-rr/blob/main/frontend/flutter/deep_dive_gesture_handling.adoc): hit testing, gesture arena, event dispatching (Advanced)
- [Authorization: RBAC, ABAC, ReBAC](https://github.com/rridane/public-notes-rr/blob/main/security/rbac.adoc): the main authorization models, explained (Intermediate)

Security and identity

- [OAuth2](https://github.com/rridane/public-notes-rr/blob/main/security/authentication_mechanisms/oauth2.adoc): authentication flows, grant types, best practices (Fundamental)
- [SAML](https://github.com/rridane/public-notes-rr/blob/main/cheatsheets/saml_cheatsheet.adoc): condensed reminders, assertions and diagrams (Cheat sheet)

Data and foundations

- [CloudNativePG, Postgres HA on Kubernetes](https://github.com/rridane/public-notes-rr/blob/main/databases/cloudnative-pg-operator.adoc): failover, backup and replication on Kubernetes (Advanced)
- [Probability, Bernoulli to Bayes](https://github.com/rridane/public-notes-rr/blob/main/mathematics/probability/bayes.adoc): probability from the ground up (Fundamental)

---

Open to roles where deep systems engineering meets software architecture, especially around observability and AIOps, or anything ambitious to build together. Reach out.
