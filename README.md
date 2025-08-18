# 🚀 DevOps Portfolio Hub

Welcome to my **DevOps Portfolio Hub**!  
This repository serves as the central index of all my hands-on DevOps projects.
Each project lives in its own GitHub repository, but this hub organizes them by **domain, technology, and DevOps concepts**.
Projects tackled go from simple real-world DevOps tasks to fully automated end-to-end CI/CD pipelines.

---

## 🌐 Cloud & Infrastructure
### ☁️ [Cloud-Server Setup](https://github.com/username/cloud-digitalocean-server)
- **Stack:** DigitalOcean, Linux, Java, Gradle  
- **DevOps Concepts:** Cloud provisioning, user management, app deployment  
- **Highlights:**  
  - Configured a secure Linux server on DigitalOcean  
  - Deployed Java Gradle application  

### 📦 [Artifact Hub with Nexus](https://github.com/username/nexus-artifact-hub)
- **Stack:** Nexus, Linux, Java, Gradle, Maven  
- **DevOps Concepts:** Artifact repository management, CI artifact publishing  
- **Highlights:**  
  - Deployed and configured Nexus  
  - Published artifacts from Maven & Gradle builds  

---

## 🐳 Containers & Docker
### 🔹 [Dockerized Dev Env](https://github.com/username/dockerized-dev-env)
- **Stack:** Docker, Node.js, MongoDB, MongoExpress  
- **DevOps Concepts:** Containerization, container networking  
- **Highlights:**  
  - Created Dockerfile for Node.js app  
  - Connected app with MongoDB and MongoExpress  

### 🔹 [ComposeStack](https://github.com/username/docker-compose-stack)
- **Stack:** Docker Compose, MongoDB, MongoExpress  
- **DevOps Concepts:** Multi-container orchestration  
- **Highlights:**  
  - Defined services in `docker-compose.yml`  
  - Managed containers with volumes & persistence  

### 🔹 [Nexus in Docker](https://github.com/username/nexus-dockerized)
- **Stack:** Docker, Nexus, DigitalOcean  
- **DevOps Concepts:** Service containerization  
- **Highlights:**  
  - Ran Nexus inside a container  
  - Configured hosted Docker repo  

---

## 🔄 CI/CD with Jenkins
### ⚙️ [CI Pipeline Basics](https://github.com/username/jenkins-ci-pipeline)
- **Stack:** Jenkins, Docker, Git, Maven  
- **DevOps Concepts:** CI automation, Jenkinsfiles, Git integration  
- **Highlights:**  
  - Built Maven JAR → Docker image → pushed to private registry  
  - Implemented Freestyle, Pipeline, and Multibranch jobs  

### ⚙️ [Smart CI/CD](https://github.com/username/jenkins-dynamic-pipeline)
- **Stack:** Jenkins, GitLab, Docker, Maven  
- **DevOps Concepts:** Webhooks, dynamic versioning  
- **Highlights:**  
  - Auto-trigger pipelines on GitLab pushes  
  - Incremented versions dynamically inside pipelines  

---

## ☁️ AWS Deployments
### 🟢 [Manual EC2 Deploy](https://github.com/username/aws-ec2-manual)
- **Stack:** AWS EC2, Docker  
- **DevOps Concepts:** Manual provisioning & container deployment  
- **Highlights:**  
  - Installed Docker on EC2  
  - Deployed app from private Docker registry  

### 🟢 [CI/CD → EC2](https://github.com/username/jenkins-aws-deploy)
- **Stack:** Jenkins, AWS EC2, Docker, Docker Compose  
- **DevOps Concepts:** Continuous Deployment, automation  
- **Highlights:**  
  - Extended CI pipeline with CD step  
  - Automated EC2 deployments with Docker Compose  

---

## ☸️ Kubernetes & Helm
### 🌀 [K8s Local Stack](https://github.com/username/k8s-minikube-stack)
- **Stack:** Kubernetes, Minikube, MongoDB, MongoExpress  
- **DevOps Concepts:** Container orchestration, ConfigMaps, Secrets  
- **Highlights:**  
  - Deployed stateful MongoDB service  
  - Secured credentials via Secrets  

### 🌀 [K8s Microservices](https://github.com/username/k8s-microservices-prod)
- **Stack:** Kubernetes, Redis, Linode LKE  
- **DevOps Concepts:** Microservices deployment, production best practices  
- **Highlights:**  
  - Built manifests for online shop microservices  
  - Applied security best practices  

### 🌀 [Helm & Helmfile](https://github.com/username/helm-microservices)
- **Stack:** Helm, Helmfile, Kubernetes  
- **DevOps Concepts:** Helm charting, reusable configs  
- **Highlights:**  
  - Created shared Helm charts  
  - Deployed with Helmfile for better management  

### 🌀 [EKS CI/CD](https://github.com/username/eks-cicd-pipeline)
- **Stack:** AWS EKS, Jenkins, DockerHub/ECR  
- **DevOps Concepts:** CI/CD pipelines with Kubernetes  
- **Highlights:**  
  - Provisioned EKS cluster  
  - Integrated deployment into Jenkins pipeline  

---

## 🔧 Infrastructure as Code (Terraform)
### 🌍 [Terraform Infra](https://github.com/username/terraform-infra)
- **Stack:** Terraform, AWS  
- **DevOps Concepts:** Infrastructure as Code (IaC)  
- **Highlights:**  
  - Automated provisioning of VPC, EC2, Security Groups  
  - Modularized Terraform configs  

### 🌍 [CI/CD with Terraform](https://github.com/username/terraform-cicd)
- **Stack:** Jenkins, Terraform, AWS, Docker  
- **DevOps Concepts:** IaC integrated with CI/CD  
- **Highlights:**  
  - Pipeline provisions infra + deploys app automatically  

---

## 🐍 Python Automation
### 🐍 [Infra Health Checks](https://github.com/username/python-ec2-health)
- **Stack:** Python, Boto3, AWS, Terraform  
- **DevOps Concepts:** Infra monitoring & automation  
- **Highlights:**  
  - Monitored EC2 health  
  - Automated backup/restore  

### 🐍 [Website Monitor](https://github.com/username/python-site-monitor)
- **Stack:** Python, Docker, Linode  
- **DevOps Concepts:** Monitoring, auto-recovery  
- **Highlights:**  
  - Checked website availability  
  - Restarted service automatically if down  

---

## ⚙️ Configuration Management (Ansible)
### 📝 [Node.js App Deployment](https://github.com/username/ansible-node-deploy)
- **Stack:** Ansible, Node.js, DigitalOcean  
- **DevOps Concepts:** Config management, provisioning  
- **Highlights:**  
  - Automated server provisioning + app deployment  

### 📝 [Ansible + Terraform](https://github.com/username/ansible-terraform)
- **Stack:** Ansible, Terraform, AWS, Docker  
- **DevOps Concepts:** IaC + Config Mgmt integration  
- **Highlights:**  
  - Terraform provisions infra  
  - Ansible configures it automatically  

---

## 📊 Monitoring & Observability
### 📡 [K8s Monitoring Stack](https://github.com/username/k8s-monitoring)
- **Stack:** Prometheus, Grafana, Kubernetes, Helm  
- **DevOps Concepts:** Observability, alerting, dashboards  
- **Highlights:**  
  - Installed Prometheus Operator in EKS  
  - Configured alert rules & Grafana dashboards  

### 📡 [App Metrics Export](https://github.com/username/nodejs-metrics)
- **Stack:** Node.js, Prometheus, Grafana, Docker  
- **DevOps Concepts:** App observability  
- **Highlights:**  
  - Exposed app metrics endpoint  
  - Integrated metrics into Grafana dashboards  

---

## 📖 About Me
I am an **aspiring MLOps Engineer** with strong DevOps foundations:  
- 🐳 Containerization (Docker, K8s, Helm)  
- ⚙️ CI/CD automation (Jenkins, GitHub Actions)  
- ☁️ Cloud (AWS, DigitalOcean, Linode)  
- 🌍 IaC (Terraform, Ansible)  
- 📊 Monitoring (Prometheus, Grafana)  
- 🐍 Python automation  

This portfolio showcases my practical experience building **end-to-end DevOps pipelines**.

---

