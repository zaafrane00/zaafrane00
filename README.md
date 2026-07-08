<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1D9E75,100:378ADD&height=180&section=header&text=Hamza%20Zaafrane&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=DevOps%20Engineer%20%7C%20CKA%20Certified%20%7C%20Kubernetes%20%26%20AWS&descAlignY=58&descSize=18" width="100%" alt="Header banner" />

</div>

<p align="center">
  <img src="https://img.shields.io/badge/DevOps%20Engineer-4%2B%20years-378ADD?style=for-the-badge" alt="DevOps Engineer, 4+ years" />
  <img src="https://img.shields.io/badge/CKA-Certified-0F6E56?style=for-the-badge" alt="CKA Certified" />
  <img src="https://img.shields.io/badge/Based%20in-Tunisia-D85A30?style=for-the-badge" alt="Based in Tunisia" />
</p>

I run production EKS clusters that need to stay up. That means real incidents, real root causes, and real fixes — not just YAML tutorials.

I'm currently open to **remote DevOps roles**.

<br>

## What I actually do

- **Kubernetes at scale** — manage EKS clusters across regions, autoscaled with Karpenter.
- **GitOps** — ArgoCD-driven deployments, including live major-version upgrades with zero downtime.
- **Ingress & security** — Traefik Gateway Api and Nginx-Ingress routing, RBAC design, and incident response when it breaks in production.
- **Secrets & config** — Vault, Helm, Terraform for infrastructure as code.
- **CI/CD** — Jenkins pipelines shipping to AWS ECR.
- **Observability** — Grafana dashboards, Prometheus metrics, and Loki log aggregation across production clusters.

<br>

## How the pieces fit together

<div align="center">
<img src="architecture.svg" width="100%" alt="Diagram showing code flowing from Git through ArgoCD and Terraform into an EKS cluster, where Karpenter autoscales nodes, Traefik handles ingress, Vault manages secrets, and Datadog observes everything" />
</div>

This is the shape of most of my production work: code lands in Git, ArgoCD syncs it into the cluster, Karpenter keeps nodes sized to load, Traefik routes traffic in, Vault keeps secrets out of manifests, and Grafana, Prometheus, and Loki watch all of it.

<br>

## A few things I've shipped

- 🔥 **Diagnosed a full production outage** caused by a Traefik RBAC gap that blocked all public services — traced it to a ClusterRoleBinding mismatch introduced by a Helm upgrade, and fixed the single point of failure it exposed.
- ⬆️ **Upgraded ArgoCD across a major version bump** while protecting existing NetworkPolicies from being silently overwritten by `selfHeal` and `prune`.
- 📦 **Migrated Karpenter through two major versions** (1.8 → 1.11), safely transferring CRD ownership without losing running nodes.
- 🖥️ **Designed a remote cloud dev environment** (Coder + ArgoCD ApplicationSet + EFS) to remove the need for developers to clone a multi-GB monorepo onto their laptops.
- 🐕 **Deployed Falco to production via ArgoCD** and diagnosed a pod-scheduling deadlock caused by an overly broad `podAntiAffinity` rule.
- 🗃️ **Migrated SonarQube's database** from embedded Bitnami PostgreSQL to an external instance — full pg_dump/restore with zero data loss across a mandatory intermediate-version upgrade path.

I write these up as I go — not polished war stories, just what actually happened and what I'd do differently next time.

<br>

## Currently exploring

- Remote-first DevOps and Platform Engineering roles.
- Deeper observability work — custom Grafana dashboards, PromQL, and log-based alerting on Kubernetes.
- Developer-experience tooling that makes Kubernetes less painful for the people who aren't infra specialists.

<br>

## Contact

<p align="left">
<a href="mailto:zaafranehamza@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.linkedin.com/in/hamza-zaafrane/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://github.com/zaafrane00"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<br>

## Tech stack

<p align="left">
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" />
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
<img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" alt="ArgoCD" />
<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<br>
<img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" alt="Helm" />
<img src="https://img.shields.io/badge/Vault-000000?style=for-the-badge&logo=vault&logoColor=white" alt="Vault" />
<img src="https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white" alt="Traefik" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
<br>
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana" />
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus" />
<img src="https://img.shields.io/badge/Loki-F5A623?style=for-the-badge&logo=grafana&logoColor=white" alt="Loki" />
</p>

<br>

## GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=zaafrane00&show_icons=true&count_private=true&theme=tokyonight&hide_border=true" alt="Hamza's GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zaafrane00&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=zaafrane00&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D" alt="Hamza's streak stats" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=zaafrane00&label=Profile%20views&color=1D9E75&style=for-the-badge" alt="Profile views" />
</p>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:378ADD,100:1D9E75&height=100&section=footer" width="100%" alt="Footer banner" />
</div>
