# Kacper Przybyła

**Junior DevOps Engineer** | Wrocław, Poland | Open to remote & hybrid

Building production-grade CI/CD systems, infrastructure automation, and container orchestration.
2.5 years managing Linux infrastructure for 300+ IoT devices, now focused on cloud-native DevOps.

📹 **[Watch 3-minute pipeline demo video](https://www.youtube.com/watch?v=lYxCKmWBe1E)** — code change → automated deployment → live in production

---

## 🚀 Portfolio Projects

*The same task-manager application is deployed two fundamentally different ways across these repos: automated CI/CD to a single EC2 instance (Terraform + Ansible), and container orchestration on Kubernetes (raw manifests + Helm).*

### [task-manager-app](https://github.com/kacper-przybyla/task-manager-app)
**Full-Stack CI/CD System**

Automated deployment pipeline: Docker → GitHub Actions → GHCR → AWS EC2

**Stack:** Docker · GitHub Actions · FastAPI · React · nginx · PostgreSQL  
**Key features:** OIDC authentication · Semantic versioning · 4-5 min deployment  
🌐 **[Deployed app](http://18.159.85.126/)** 

---

### [task-manager-deployment](https://github.com/kacper-przybyla/task-manager-deployment)
**Infrastructure & Automation**

AWS infrastructure provisioning with Terraform, application deployment with Ansible

**Stack:** Terraform · Ansible · AWS · Python  
**Key features:** Modular Terraform design · Dynamic EC2 inventory · Secrets management · [Python CLI tool](https://github.com/kacper-przybyla/task-manager-deployment/blob/main/tools/deploy-manager.py) for deploy/rollback/status

---

### [task-manager-k8s](https://github.com/kacper-przybyla/task-manager-k8s)
**Kubernetes Deployment — Raw Manifests + Helm Chart**

Same application deployed to Kubernetes two ways: hand-written manifests, then a parameterized Helm chart with per-environment overlays.

**Stack:** Kubernetes · Helm · nginx Ingress · cert-manager · minikube  
**Key features:** StatefulSet + headless Service for Postgres · Helm pre-upgrade & test hooks · dev/prod values overlays · externally-managed Secrets

---

### [legacy-ecommerce](https://github.com/kacper-przybyla/legacy-ecommerce)
**Legacy App Dockerization**

Containerized 2019-era Ruby/Sinatra monolith with 8 services

**Stack:** Docker · docker-compose · Ruby · PostgreSQL · Redis · RabbitMQ · nginx  
**Key features:** Multi-stage builds · Environment separation · Real troubleshooting documented

---

## 🛠️ Tech Stack

**Containerization & Orchestration**  
Docker · docker-compose · Kubernetes · Helm · nginx Ingress · cert-manager

**CI/CD**  
GitHub Actions · GHCR

**Infrastructure as Code**  
Terraform · Ansible

**Cloud**  
AWS (EC2 · VPC · IAM · S3 · OIDC)

**Programming**  
Python · Bash · Ruby

**Operating Systems**  
Linux · Windows

**Networking**  
WireGuard · nginx (reverse proxy) · VPN tunneling · routing

**Databases**  
PostgreSQL · Redis

**Version Control**  
Git · semantic versioning

---

🔭 **Currently exploring:** Kubernetes observability (Prometheus, Grafana, Loki)

---

## 📫 Contact

**LinkedIn:** [linkedin.com/in/kacperprzybyla](https://linkedin.com/in/kacperprzybyla)  
**Email:** kacper.przybyla.praca@gmail.com
