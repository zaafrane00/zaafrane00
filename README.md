# Hi, I'm Hamza 👋

**DevOps Engineer | CKA Certified | Building resilient AWS/Kubernetes infrastructure**

I run production EKS clusters that need to stay up. That means real incidents, real root causes, and real fixes — not just YAML tutorials.

---

## What I actually do

- **Kubernetes at scale** — manage EKS clusters across `us-east-2` and `eu-west-1`, autoscaled with Karpenter.
- **GitOps** — ArgoCD-driven deployments, including live version upgrades without downtime.
- **Ingress & security** — Traefik routing, RBAC, and incident response when it breaks in production.
- **Secrets & config** — Vault, Helm, Terraform for infrastructure as code.
- **CI/CD** — Jenkins pipelines shipping to AWS ECR.
- **Observability** — Datadog APM, infrastructure monitoring, and database monitoring on Kubernetes.

## A few things I've shipped

- Diagnosed and fixed a full production outage caused by a Traefik RBAC gap that blocked all public services — traced it to a ClusterRoleBinding mismatch after a Helm upgrade.
- Upgraded ArgoCD across a major version bump while protecting existing NetworkPolicies from being silently overwritten by `selfHeal`.
- Migrated Karpenter through two major versions, safely transferring CRD ownership without losing running nodes.
- Designed a remote cloud dev environment (Coder + ArgoCD ApplicationSet) to kill the need for developers to clone a full monorepo locally.

I write about these as I go — not polished war stories, just what actually happened and what I'd do differently.

## Currently exploring

- Remote-first DevOps roles.
- Deeper Datadog observability (APM, DBM, admission-controller instrumentation).
- Better developer-experience tooling on top of Kubernetes.

## Contact

- 📧 **Email:** zaafranehamza@gmail.com
- 💼 **LinkedIn:** [linkedin.com/in/hamza-zaafrane](https://www.linkedin.com/in/hamza-zaafrane/)

---

## Tech Stack

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-000000?style=for-the-badge&logo=vault&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white)

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=zaafrane00&show_icons=true&count_private=true&theme=tokyonight&hide_border=true" alt="Hamza's GitHub Stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zaafrane00&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=zaafrane00&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D" alt="Hamza's Streak Stats" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=zaafrane00&label=Profile%20views&color=6c5ce7&style=flat" alt="Profile views" />
</p>
