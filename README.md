# Hey, I'm mourasoft 👋

**DevOps & Platform Engineer · Fès, Morocco**

> I build production-grade platforms on Kubernetes — from CI/CD pipelines
> to AI/LLM serving infrastructure. Hands-on with the full DevSecOps stack.

---

### 🏅 Certifications

![CKA](https://img.shields.io/badge/CKA-Certified-326CE5?logo=kubernetes&logoColor=white)
![CKAD](https://img.shields.io/badge/CKAD-Certified-326CE5?logo=kubernetes&logoColor=white)
![AWS SAA](https://img.shields.io/badge/AWS_SAA-Certified-FF9900?logo=amazonaws&logoColor=white)

---

### 🔧 Stack

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-FF9900?logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?logo=ansible&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

**Containers & Orchestration**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?logo=helm&logoColor=white)
![KEDA](https://img.shields.io/badge/KEDA-Autoscaling-0078D4)

**GitOps & CI/CD**

![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?logo=argo&logoColor=white)
![Tekton](https://img.shields.io/badge/Tekton-FD495C?logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-Log_Aggregation-F46800)

**DevSecOps**

![OPA](https://img.shields.io/badge/OPA-Gatekeeper-7D3C98)
![Falco](https://img.shields.io/badge/Falco-Runtime_Security-00AEC7)
![Trivy](https://img.shields.io/badge/Trivy-Image_Scanning-1904DA)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?logo=sonarqube&logoColor=white)

---

### 🚀 Featured project

**[🤖 LLM Platform on Kubernetes](https://github.com/mourasoft/llm-platform-k8s)**

> Production-grade AI serving platform built from scratch.
> Multi-tenant · GitOps · Zero-trust security · Automated MLOps pipeline.

| Layer | Technology |
|-------|------------|
| LLM serving | Ollama · TinyLlama · KServe |
| Autoscaling | KEDA · Prometheus · HPA |
| GitOps | ArgoCD · app-of-apps · selfHeal |
| Observability | Prometheus · Grafana · AlertManager · SLOs |
| Security | OPA Gatekeeper · Falco · Trivy · NetworkPolicy |
| MLOps | Tekton Pipelines · ArgoCD Rollouts · MinIO |

**What it demonstrates:**
- ✅ Multi-tenant isolation — ResourceQuota + NetworkPolicy across 4 namespaces
- ✅ Queue-based autoscaling — KEDA scales on `ollama_active_requests` metric
- ✅ GitOps self-healing — manual changes reverted by ArgoCD in
