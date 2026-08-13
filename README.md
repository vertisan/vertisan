# 👋 Hi, I'm Pawel

**DevSecOps & Platform Engineer** 

I automate the boring parts of infrastructure - from a project's CI/CD up to provisioning a whole K8s cluster with monitoring and GitOps from a single form.

Day-to-day: **Kubernetes, Terraform, GitOps, Vault, Ansible, AWS/GCP**; ex-Developer (PHP, Node.js), which is why I still like writing tooling in Python & Go.

I maintain a few things you can actually use:

- 🪖 [**Helm charts**](https://helm.vrs-factory.dev) - starting with a RouterOS (MikroTik) exporter for Prometheus, because no sensible chart existed and I didn't want to babysit static manifests.
- 🗄 [**Vault Snapshot Agent**](https://github.com/vertisan/vault-snapshot-agent) - a small binary that automates HashiCorp Vault backups. Vault secures your secrets; someone should secure Vault.
- 👹 [**Terraform modules**](https://github.com/orgs/vrs-factory/repositories?q=terraform-&type=all) - mostly built for specific cases, but the Fork button is right there.
- 😈 [**LeDo**](https://github.com/paramah/ledo) - a CLI that makes working with Docker on a project less painful. A friend's project I help develop.
- 📖 [**Symfony: The Fast Track**](https://symfony.com/book) - I've helped translate the Polish edition since day one.
- 📺 [**Twitch Helix Provider for OAuth 2.0**](https://github.com/orgs/vrs-factory/repositories?q=terraform-&type=all) - One of my first creations in the open-source world. Still active - [still popular](https://packagist.org/packages/vertisan/oauth2-twitch-helix/stats)!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/pawel-farys/) 
[![GitLab](https://img.shields.io/badge/GitLab-orange?logo=gitlab&logoColor=white&style=for-the-badge)](https://gitlab.com/vertisan)

---

## 🛠️ Stack

[![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](#)
[![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)](#)
[![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](#)
[![ArgoCD](https://img.shields.io/badge/argocd-%23ef7b4d.svg?style=for-the-badge&logo=argo&logoColor=white)](#)
[![HCP Vault](https://img.shields.io/badge/vault-FFCF25.svg?style=for-the-badge&logo=vault&logoColor=white)](#)
[![Ansible](https://img.shields.io/badge/ansible-000000.svg?style=for-the-badge&logo=ansible&logoColor=white)](#)
[![AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)](#)
[![Python](https://img.shields.io/badge/python-%23306998.svg?style=for-the-badge&logo=python&logoColor=white)](#)

Also regularly: Helm, Kustomize, Packer, Prometheus, Grafana, Go, PostgreSQL, Redis, Nginx.

**Clouds** - most production experience on AWS (EKS, EC2 & ASG, DynamoDB, R53, SQS, SNS), GCP is evolving 😋

---

## 🏠 Homelab

My playground, and where most of the above gets tested before I trust it anywhere else.

**Hardware**

| Toy | Spec |
|---|---|
| Lenovo ThinkCentre M720q Tiny | i5-8500T, 64 GB RAM, 1 TB NVMe |
| Lenovo ThinkCentre M720q Tiny | i5-8500T, 32 GB RAM, 1 TB NVMe |
| Lenovo ThinkCentre M920q Tiny | i7-8700T, 64 GB RAM, 1 TB NVMe |
| Synology DS720+ | 2× 4 TB, 512 GB NVMe cache |
| Network | MikroTik RB5009UG+S+IN, UniFi U6+ |

**Software**

- **Proxmox** + **Packer** - virtualization and image building
- **K3s** - the cluster itself
- **Terraform** - Proxmox VMs, cloud envs, Vault, Cloudflare, and much more
- **Ansible** - stateless provisioning for K3s, Vault, load balancers, and so much other stuff!
- **ArgoCD** - GitOps
- **HashiCorp Vault** (+ VSO) - secrets
- **Cloudflare & Traefik** - DNS and reverse proxy
- **HAProxy, Keepalived, MetalLB** - load balancing and VIPs
- **Prometheus, Grafana** - monitoring; **Pushover** for alerts
- **Tailscale** - VPN
- **Renovate** - dependency updates

---

Questions, ideas, or want to compare homelab notes? [Reach out on LinkedIn](https://www.linkedin.com/in/pawel-farys/).
