# 🧩 rridane

> Designing and building end-to-end systems — from resilient cloud-native backends to high-performance front-end experiences.
Welcome 👋

Here you’ll find all the **tools I use daily** to:

* Maintain a **state-of-the-art cloud-native platform**
* Optimize the developer experience and deployment metrics
* Design and build high-performance applications, from front-end experiences to resilient back-end systems
* Mentor and train **junior and senior developers** alike

A curated selection of modular tools — spanning the full lifecycle of a modern platform: provisioning, software architecture, observability, and developer experience.

---

## ⚙️ Infrastructure as Code (Ansible)

* [**ansible-kubernetes-admin**](https://github.com/rridane/ansible-kubernetes-admin) — Bootstrap HA Kubernetes clusters (admins, masters, workers, load balancers)
* [**ansible-base-systems**](https://github.com/rridane/ansible-base-systems) — Base system configuration for Linux environments

---

## 🚚 Pipelines & Automation (Go)

* [**golang-pipeyard**](https://github.com/rridane/golang-pipeyard) — A powerful and elegant Go library to build CLI pipelines with automatic dependency injection

---

## ✏ Terraform Cloud-Native Kit

* [**terraform-kubernetes-cloudnative-kit**](https://github.com/rridane/terraform-kubernetes-cloudnative-kit) — A complete Terraform module collection to manage your cloud-native components:

  * [OpenTelemetry Collector Generator](https://github.com/rridane/terraform-kubernetes-cloudnative-kit/tree/main/modules/monitoring-opentelemetry)
  * [Bind9 & DNS Publication Management](https://github.com/rridane/terraform-kubernetes-cloudnative-kit/tree/main/modules/networking-bind9)
  * [Ingress Route Management](https://github.com/rridane/terraform-kubernetes-cloudnative-kit/tree/main/modules/networking-ingress-route-transformer)
  * [Cert-Manager TLS Management](https://github.com/rridane/terraform-kubernetes-cloudnative-kit/tree/main/modules/security-cert-manager)
  * [Vault — policies, roles & secrets engines (PKI)](https://github.com/rridane/terraform-kubernetes-cloudnative-kit/tree/main/modules/security-vault)

---

## ☸️ Helm & ArgoCD Cloud-Native Components

* [**CloudNativePG**](https://github.com/rridane/helm-argocd-cloudnative-kit/tree/main/cloudnative-pg) — production Postgres-as-a-service: HA bootstrap, backup/PITR, connection pooler
* [**OpenTelemetry**](https://github.com/rridane/helm-argocd-cloudnative-kit/tree/main/opentelemetry) — collector + agent with tail-sampling, spanmetrics, k8sattributes → Mimir / Loki / Tempo / Pyroscope
* [**Rancher RBAC**](https://github.com/rridane/helm-argocd-cloudnative-kit/tree/main/rancher-rbac) — declarative, multi-cluster RBAC as code
* [**Gateway HTTP Routes**](https://github.com/rridane/helm-argocd-cloudnative-kit/tree/main/gateway-http-routes) — Gateway API HTTPRoute management
* [**Parca**](https://github.com/rridane/helm-argocd-cloudnative-kit/tree/main/parca) — continuous CPU/memory profiling
* [**Filebrowser**](https://github.com/rridane/helm-argocd-cloudnative-kit/tree/main/filebrowser) — web-based file browser for teams

---

## 📚 Engineering deep-dives

Beyond the code, I also share **technical sheets** and *deep dives* that I use to teach and document. They explain complex concepts in a clear way and serve as practical learning material for engineering teams.

**🖧 Systems & networking**
* [HTTP/1 → HTTP/3 & gRPC](https://github.com/rridane/public-notes-rr/blob/main/networking/protocols/from_http_to_http3_and_grpc.adoc) — a deep dive on gRPC and HTTP/3, starting from HTTP/1 _(Advanced)_
* [Linux kernel networking (L2/L3)](https://github.com/rridane/public-notes-rr/blob/main/networking/linux_kernel_networking.adoc) — how a packet travels through the Linux kernel, end to end _(Advanced)_
* [Kubernetes networking from scratch](https://github.com/rridane/public-notes-rr/blob/main/devops/kubernetes_networking.adoc) — CNI, services, network policies, overlay/underlay _(Intermediate / Advanced)_
* [DNS, from zones to DNSSEC](https://github.com/rridane/public-notes-rr/blob/main/networking/protocols/dns/dns_advanced.adoc) — from zones, TTL and resolution to delegations and DNSSEC ([basics](https://github.com/rridane/public-notes-rr/blob/main/networking/protocols/dns/dns_basic_overview.adoc)) _(Beginner → Advanced)_

**🏗️ Software architecture & internals**
* [Flutter framework internals](https://github.com/rridane/public-notes-rr/blob/main/frontend/flutter/deep_dive_flutter_internal_framework.adoc) — the internal bindings, build pipeline, and scheduler mechanics _(Advanced)_
* [Flutter gesture handling](https://github.com/rridane/public-notes-rr/blob/main/frontend/flutter/deep_dive_gesture_handling.adoc) — the gesture system: hit testing, gesture arena, and event dispatching _(Advanced)_
* [Authorization: RBAC → ABAC → ReBAC](https://github.com/rridane/public-notes-rr/blob/main/security/rbac.adoc) — the main authorization models, explained _(Intermediate)_

**🔐 Security & identity**
* [OAuth2](https://github.com/rridane/public-notes-rr/blob/main/security/authentication_mechanisms/oauth2.adoc) — authentication flows, grant types, best practices _(Fundamental)_
* [SAML](https://github.com/rridane/public-notes-rr/blob/main/cheatsheets/saml_cheatsheet.adoc) — condensed reminders, assertions, and diagrams _(Cheat sheet)_

**🗄️ Data & foundations**
* [CloudNativePG — Postgres HA on Kubernetes](https://github.com/rridane/public-notes-rr/blob/main/databases/cloudnative-pg-operator.adoc) — failover, backup, and replication on Kubernetes _(Advanced)_
* [Probability, Bernoulli → Bayes](https://github.com/rridane/public-notes-rr/blob/main/mathematics/probability/bayes.adoc) — probability from the ground up _(Fundamental)_

---

> 🌍 **Any role where deep systems engineering meets software architecture — especially around observability & AIOps — or something ambitious to build together? Feel free to reach out.**

![](https://hit.yhype.me/github/profile?account_id=34446644)
