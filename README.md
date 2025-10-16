# 🧩 rridane 

> Building, scaling, and teaching modern cloud-native platforms

Bienvenue 👋

Vous trouverez ici tous les **outils que j’utilise au quotidien** pour :

* Maintenir une plateforme **cloud-native à l’état de l’art**
* Optimiser l'expérience dev et les statistiques de déploiements
* Accompagner et former des **développeurs juniors** comme des plus expérimentés

Une sélection d’outils modulaires pour **CTOs, Platform Engineers et VP Engineering**, couvrant tout le cycle de vie d’une plateforme moderne — du provisioning à la formation des équipes.

---

## ⚙️ Infrastructure as Code (Ansible)

* [**ansible-kubernetes-admin**](https://github.com/rridane/ansible-kubernetes-admin) — Bootstrap de clusters Kubernetes HA (admin, masters, workers, LB)
* [**ansible-base-systems**](https://github.com/rridane/ansible-base-systems) — Configuration des systèmes de base Linux

---

## 🐹 Pipelines & Automation (Go)

* [**golang-pipeyard**](https://github.com/rridane/golang-pipeyard) — Puissante librairie Go pour construire des pipelines CLI avec injection automatique de dépendances

---

## 🏗️ Terraform Cloud-Native Kit

* [**terraform-kubernetes-cloudnative-kit**](https://github.com/rridane/terraform-kubernetes-cloudnative-kit) — Ensemble de modules Terraform pour gérer vos composants cloud-native :

  * [OpenTelemetry Collector Generator](https://github.com/rridane/terraform-kubernetes-cloudnative-kit/tree/main/modules/observability-opentelemetry-collector)
  * [Bind9 & DNS Publication Management](https://github.com/rridane/terraform-kubernetes-cloudnative-kit/tree/main/modules/networking-bind9)
  * [Ingress Route Management](https://github.com/rridane/terraform-kubernetes-cloudnative-kit/tree/main/modules/networking-ingress-route-transformer)
  * [Cert-Manager TLS Management](https://github.com/rridane/terraform-kubernetes-cloudnative-kit/tree/main/modules/security-cert-manager)

---

## ☸️ Helm & ArgoCD Cloud-Native Components

* [**Parca**](https://github.com/rridane/helm-argocd-cloudnative-kit/tree/main/parca) — Monitoring applicatif des ressources
* [**Filebrowser**](https://github.com/rridane/helm-argocd-cloudnative-kit/tree/main/filebrowser) — Explorateur de fichiers web pour vos équipes

---

## 📚 Fiches & Deep Dives

Au-delà du code, je mets à disposition des **fiches techniques** et *deep dives* que j’utilise pour former et transmettre.
Elles permettent d’expliquer des concepts complexes et servent de support pédagogique pour les équipes.

| Fiche                                                                                                                  | Contenu                                                                   | Niveau                 |
| ---------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | ---------------------- |
| [**Ultimate Scaleup Kit**](https://github.com/rridane/public-notes-rr/blob/main/ultimate_scaleup_kit.adoc)             | Stratégies et patterns pour accompagner la scalabilité d’une organisation | Vision CTO             |
| [**Kubernetes Networking**](https://github.com/rridane/public-notes-rr/blob/main/devops/kubernetes_networking.adoc)    | CNI, services, policies, overlay/underlay                                 | Intermédiaire / Avancé |
| [**OAuth2**](https://github.com/rridane/public-notes-rr/blob/main/security/authentication_mechanisms/oauth2.adoc)      | Flux d’authentification, grant types, bonnes pratiques                    | Fondamental            |
| [**SAML Cheatsheet**](https://github.com/rridane/public-notes-rr/blob/main/cheatsheets/saml_cheatsheet.adoc)           | Rappels condensés, assertions, schémas                                    | Cheat sheet            |
| [**DNS Basic**](https://github.com/rridane/public-notes-rr/blob/main/networking/protocols/dns/dns_basic_overview.adoc) | Fondamentaux du DNS (zones, TTL, résolutions)                             | Débutant               |
| [**DNS Advanced**](https://github.com/rridane/public-notes-rr/blob/main/networking/protocols/dns/dns_advanced.adoc)    | Cas complexes, délégations, optimisation                                  | Avancé                 |

> 🔗 Retrouvez l’ensemble des fiches dans le repo [**public-notes-rr**](https://github.com/rridane/public-notes-rr)

---

> 🌍 **CTO / Head of Engineering opportunity ?** → Contactez-moi en message privé
