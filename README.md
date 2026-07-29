<h1 align="center">Hi, I'm Jubeth S B 👋</h1>
<h3 align="center">Cloud & DevSecOps Engineer — Kubernetes · AWS/GCP · Terraform · Zero-Trust Security</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-DevSecOps-2EA043?style=flat-square" />
  <img src="https://img.shields.io/badge/Kubernetes-Istio%20%7C%20Argo%20CD-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloud-AWS%20%7C%20GCP-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/IaC-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Chennai%2C%20India-open%20to%20relocate-informational?style=flat-square" />
</p>

---

I build and secure cloud infrastructure end to end: provisioning it as code, running
workloads on Kubernetes, wiring up delivery pipelines, and hardening the whole path
against real attackers. I care about **least privilege, defence in depth, and proving a
control works by trying to break it** — not just deploying it.

Currently going deep on **DevSecOps and platform/SRE** work: admission control,
supply-chain signing, service-mesh zero-trust, and hands-on penetration testing.

---

### 🛠️ Technical Stack

| Category | Skills |
| :--- | :--- |
| **Containers & Orchestration** | Kubernetes, Istio (mTLS, AuthorizationPolicy), Argo CD, Docker, Docker Compose |
| **Cloud** | **AWS** (EKS, EC2, VPC, S3, RDS, IAM, CloudWatch) · **GCP** (Compute, IAM, Firewall) |
| **Infrastructure as Code** | Terraform (modules, state management, providers) |
| **CI/CD & Supply Chain** | GitHub Actions, Jenkins, Cosign (keyless), SBOM / SLSA, Trivy, Semgrep, Gitleaks |
| **Security & Policy** | Pod Security Standards, Kyverno, Sealed Secrets, NetworkPolicy, RBAC, CVSS, OWASP Top 10 |
| **Observability** | Prometheus, Grafana |
| **Automation & OS** | Python (Boto3), Bash, Linux (RHEL/Ubuntu), system hardening |

---

### 🚀 Featured Projects

#### 🔐 [Dodo Payments — DevSecOps Assessment](https://github.com/JubethSB/dodo-payments-devsecops-assessment)
Hardening a **PCI-scoped payments microservice end to end**, every control verified at runtime.
* **Workload:** non-root + read-only rootfs + dropped capabilities, PSS `restricted` + Kyverno admission, Sealed Secrets, least-privilege RBAC
* **Supply chain:** GitHub Actions gating (Trivy · Semgrep · Gitleaks) → **cosign keyless signing + SBOM attestation** → pull-based GitOps with Argo CD
* **Zero-trust:** Istio **mTLS STRICT**, default-deny **AuthorizationPolicy on SPIFFE identity** (200 vs 403), NetworkPolicy defence-in-depth
* **Offensive:** passive OSINT + a **pen-test** (RCE 9.8, SSRF 8.6, PAN exposure, weak tokenization) with each finding **mapped back to the control that stops it**

#### ☸️ [AWS Enterprise EKS Platform](https://github.com/JubethSB/aws-eks-enterprise-platform)
Production-ready Kubernetes on AWS via Terraform — custom networking, automated node provisioning.

#### 🔁 [Automated GitOps Platform (K8s & Argo CD)](https://github.com/JubethSB/k8s-platform)
Self-healing application with automated sync policies — "zero-touch" delivery.

#### 🧰 [End-to-End DevSecOps Pipeline](https://github.com/JubethSB/local-devops-project)
Full CI/CD with automated builds, security scanning, and real-time observability.

---

### 📈 GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=JubethSB&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JubethSB&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

### 📫 Connect

* **LinkedIn:** [linkedin.com/in/jubeth-cloud-devops](https://www.linkedin.com/in/jubeth-cloud-devops/)
* **Email:** sjubeth3@gmail.com

<sub>Open to Cloud / DevOps / SRE / DevSecOps roles — remote or relocation.</sub>
