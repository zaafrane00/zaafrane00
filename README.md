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

<svg width="900" height="440" viewBox="0 0 900 440" xmlns="http://www.w3.org/2000/svg">
<defs>
<marker id="arrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
<path d="M2 1L8 5L2 9" fill="none" stroke="#57606a" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
</marker>
</defs>
<rect width="900" height="440" fill="#0d1117"/>

<!-- Git -->
<rect x="40" y="40" width="160" height="64" rx="10" fill="#21262d" stroke="#8b949e" stroke-width="1"/>
<text x="120" y="66" text-anchor="middle" fill="#c9d1d9" font-family="Segoe UI, Arial" font-size="15" font-weight="600">Git repo</text>
<text x="120" y="88" text-anchor="middle" fill="#8b949e" font-family="Segoe UI, Arial" font-size="12">Helm + manifests</text>

<line x1="200" y1="72" x2="278" y2="72" stroke="#57606a" stroke-width="1.5" marker-end="url(#arrow)"/>

<!-- ArgoCD -->
<rect x="280" y="40" width="160" height="64" rx="10" fill="#2d2440" stroke="#a29bfe" stroke-width="1"/>
<text x="360" y="66" text-anchor="middle" fill="#d6cdfe" font-family="Segoe UI, Arial" font-size="15" font-weight="600">ArgoCD</text>
<text x="360" y="88" text-anchor="middle" fill="#b8aef0" font-family="Segoe UI, Arial" font-size="12">GitOps sync</text>

<line x1="440" y1="72" x2="518" y2="72" stroke="#57606a" stroke-width="1.5" marker-end="url(#arrow)"/>

<!-- Terraform -->
<rect x="520" y="40" width="200" height="64" rx="10" fill="#2d2440" stroke="#a29bfe" stroke-width="1"/>
<text x="620" y="66" text-anchor="middle" fill="#d6cdfe" font-family="Segoe UI, Arial" font-size="15" font-weight="600">Terraform</text>
<text x="620" y="88" text-anchor="middle" fill="#b8aef0" font-family="Segoe UI, Arial" font-size="12">Infra as code</text>

<line x1="360" y1="104" x2="360" y2="164" stroke="#57606a" stroke-width="1.5" marker-end="url(#arrow)"/>

<!-- EKS container -->
<rect x="60" y="168" width="740" height="210" rx="24" fill="#0c2d2a" stroke="#3fb68c" stroke-width="1"/>
<text x="84" y="200" fill="#7ee0c4" font-family="Segoe UI, Arial" font-size="16" font-weight="600">Amazon EKS cluster</text>
<text x="84" y="222" fill="#5fc6a8" font-family="Segoe UI, Arial" font-size="13">us-east-2 and eu-west-1</text>

<!-- Karpenter -->
<rect x="90" y="240" width="190" height="70" rx="12" fill="#0b2942" stroke="#58a6ff" stroke-width="1"/>
<text x="185" y="270" text-anchor="middle" fill="#a5d6ff" font-family="Segoe UI, Arial" font-size="15" font-weight="600">Karpenter</text>
<text x="185" y="292" text-anchor="middle" fill="#7fb8e8" font-family="Segoe UI, Arial" font-size="12">Node autoscaling</text>

<!-- Traefik -->
<rect x="305" y="240" width="190" height="70" rx="12" fill="#0b2942" stroke="#58a6ff" stroke-width="1"/>
<text x="400" y="270" text-anchor="middle" fill="#a5d6ff" font-family="Segoe UI, Arial" font-size="15" font-weight="600">Traefik</text>
<text x="400" y="292" text-anchor="middle" fill="#7fb8e8" font-family="Segoe UI, Arial" font-size="12">Ingress and routing</text>

<!-- Vault -->
<rect x="520" y="240" width="190" height="70" rx="12" fill="#0b2942" stroke="#58a6ff" stroke-width="1"/>
<text x="615" y="270" text-anchor="middle" fill="#a5d6ff" font-family="Segoe UI, Arial" font-size="15" font-weight="600">Vault</text>
<text x="615" y="292" text-anchor="middle" fill="#7fb8e8" font-family="Segoe UI, Arial" font-size="12">Secrets management</text>

<line x1="400" y1="310" x2="400" y2="340" stroke="#57606a" stroke-width="1.5" marker-end="url(#arrow)"/>
<text x="400" y="332" text-anchor="middle" fill="#8b949e" font-family="Segoe UI, Arial" font-size="12">Metrics + logs + traces</text>

<!-- Grafana stack -->
<rect x="230" y="345" width="140" height="55" rx="10" fill="#3a2a1a" stroke="#f2a24a" stroke-width="1"/>
<text x="300" y="372" text-anchor="middle" fill="#f9c98a" font-family="Segoe UI, Arial" font-size="14" font-weight="600">Grafana</text>
<text x="300" y="389" text-anchor="middle" fill="#e8b678" font-family="Segoe UI, Arial" font-size="10">Dashboards</text>

<rect x="380" y="345" width="140" height="55" rx="10" fill="#2a1a30" stroke="#e6522c" stroke-width="1"/>
<text x="450" y="372" text-anchor="middle" fill="#f4a688" font-family="Segoe UI, Arial" font-size="14" font-weight="600">Prometheus</text>
<text x="450" y="389" text-anchor="middle" fill="#e89478" font-family="Segoe UI, Arial" font-size="10">Metrics</text>

<rect x="530" y="345" width="140" height="55" rx="10" fill="#241f3a" stroke="#8c7ae6" stroke-width="1"/>
<text x="600" y="372" text-anchor="middle" fill="#c4b8f5" font-family="Segoe UI, Arial" font-size="14" font-weight="600">Loki</text>
<text x="600" y="389" text-anchor="middle" fill="#a99ce0" font-family="Segoe UI, Arial" font-size="10">Log aggregation</text>
</svg>

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

- DevOps and Platform Engineering roles.
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
