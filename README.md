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

Not summaries — each one rebuilds a system from first principles: down to the wire format, the kernel path, or the framework source.

**🖧 Systems & networking**
* [HTTP/1 → HTTP/3 & gRPC](https://github.com/rridane/public-notes-rr/blob/main/networking/protocols/from_http_to_http3_and_grpc.adoc) — why the stream-id is the pivot invention; multiplexing, HPACK, QUIC over UDP, gRPC anatomy
* [Linux kernel networking (L2/L3)](https://github.com/rridane/public-notes-rr/blob/main/networking/linux_kernel_networking.adoc) — the RX/TX path rebuilt: NAPI, skb, bridge FDB, FIB, qdisc/tc
* [Kubernetes networking from scratch](https://github.com/rridane/public-notes-rr/blob/main/devops/kubernetes_networking.adoc) — CNI from veth/bridge/VXLAN/Calico-BGP up to kube-proxy
* [DNS, from zones to DNSSEC](https://github.com/rridane/public-notes-rr/blob/main/networking/protocols/dns/dns_advanced.adoc) — resolution, delegation, SPF/DKIM/DMARC, DNSSEC ([basics](https://github.com/rridane/public-notes-rr/blob/main/networking/protocols/dns/dns_basic_overview.adoc))

**🏗️ Software architecture & internals**
* [Flutter framework internals](https://github.com/rridane/public-notes-rr/blob/main/frontend/flutter/deep_dive_flutter_internal_framework.adoc) — bindings, build/layout/paint pipeline, scheduler
* [Flutter gesture handling](https://github.com/rridane/public-notes-rr/blob/main/frontend/flutter/deep_dive_gesture_handling.adoc) — hit testing, the gesture arena, event dispatch
* [Authorization: RBAC → ABAC → ReBAC](https://github.com/rridane/public-notes-rr/blob/main/security/rbac.adoc) — models in depth, with a real access-governance story

**🔐 Security & identity**
* [OAuth2, hardened](https://github.com/rridane/public-notes-rr/blob/main/security/authentication_mechanisms/oauth2.adoc) — grant types + PKCE, DPoP, mTLS, FAPI
* [SAML](https://github.com/rridane/public-notes-rr/blob/main/cheatsheets/saml_cheatsheet.adoc) — assertions, bindings, replay protection

**🗄️ Data & foundations**
* [CloudNativePG — Postgres HA on Kubernetes](https://github.com/rridane/public-notes-rr/blob/main/databases/cloudnative-pg-operator.adoc) — failover state machine, quorum as R+W>N, backup/PITR
* [Probability, Bernoulli → Bayes](https://github.com/rridane/public-notes-rr/blob/main/mathematics/probability/bayes.adoc) — the rigorous base under anomaly detection & AIOps

> 🔗 ~250 more in [public-notes-rr](https://github.com/rridane/public-notes-rr)

---

> 🌍 **Open to staff / principal engineer & architect roles where deep systems engineering meets software architecture — with a focus on observability & AIOps — or to building something ambitious together.** → reach out by DM

![](https://hit.yhype.me/github/profile?account_id=34446644)
