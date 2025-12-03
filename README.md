# End-to-End CI/CD Pipeline for Java Application

---
<img width="1903" height="888" alt="CD" src="https://github.com/user-attachments/assets/be404540-7df3-45b3-a2b5-71cc6395904e" />
<img width="1902" height="657" alt="jenkins_pipeline" src="https://github.com/user-attachments/assets/9ff3bf80-e570-4179-b2c7-018bd1b208c4" />

## Project Overview
Designed and implemented a fully automated CI/CD pipeline for a Java application, integrating modern DevOps tools to ensure **efficient, scalable, and reliable deployment** to Kubernetes clusters.

---

## Workflow

### 1. Continuous Integration (CI)
- **Jenkins pipeline** triggered by webhooks on Git commits/pull requests.
- Build Java application using **Maven**.
- Perform **static code analysis** using SonarQube.
- Build **Docker image** and push to **Docker Hub**.

### 2. Continuous Delivery (CD)
- **Kubernetes manifests** stored in a separate Git repository.
- **Argo CD operator** continuously monitors manifests repository.
- **Argo Image Updater** updates manifests with new container image versions.
- Automatic deployment to **Kubernetes cluster**.

### 3. End-to-End Flow
Code commits → Jenkins CI → Docker image pushed → Argo CD detects changes → Application deployed to Kubernetes.

---

## Tools & Technologies
`Jenkins | Maven | SonarQube | Docker | Kubernetes | Argo CD | Argo Image Updater | Git/GitHub | `

---

## Outcome 
- Fully automated CI/CD pipeline from code commit to production.
- Reliable, faster releases with version-controlled deployments.
- Strong demonstration of **modern DevOps practices and GitOps workflow**.



---


