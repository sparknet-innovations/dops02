# AuraBeauty – Dynamic DevOps Project

## 🌐 Overview

**AuraBeauty** is a modern, cloud-native **eCommerce web application** designed and deployed using an **end-to-end DevOps pipeline**.
The project demonstrates the complete lifecycle — from code to cloud — integrating **frontend (React)**, **backend (Node.js & Express)**, **database (MongoDB Atlas)**, and **containerized deployments** on cloud platforms.

This project reflects industry-level DevOps workflows with strong emphasis on automation, scalability, and observability.

---

## 🚀 Key Objectives

* Implement an end-to-end **DevOps pipeline** showcasing CI/CD best practices.
* Deploy microservice-based web apps in a **containerized** environment.
* Demonstrate **cross-cloud capability** — developed on **Azure**, challenge adaptable to **AWS**.
* Ensure high code quality, environment consistency, and secure delivery pipelines.
* Enable hands-on learning through intentionally crafted debugging and optimization challenges.

---

## 🧩 Architecture Highlights

* **Frontend:** ReactJS (user-friendly shopping interface)
* **Backend:** Node.js + Express (REST API for orders and users)
* **Database:** MongoDB Atlas (cloud-based NoSQL)
* **Containerization:** Docker with multi-stage builds for optimized images
* **Deployment:** Azure Container Apps (ACA)
* **Version Control:** Git & GitHub
* **Infrastructure:** Infrastructure-as-Code using Terraform
* **Monitoring & Security:** Integrated directories for observability, vulnerability scanning, and policy compliance

---

## ⚙️ DevOps Implementation

* **CI/CD Pipeline:** Automated build, test, and deployment workflows.
* **Containerization:** Independent Dockerfiles for frontend and backend with clean `.dockerignore` policies.
* **IaC (Infrastructure-as-Code):** Terraform used for provisioning and environment setup.
* **Environment Management:** `.env`-driven configurations for isolated and secure deployments.
* **Cloud Integration:** Fully operational on Azure’s free-tier resources, replicable on AWS.
* **Security Controls:** Dedicated `security/` directory for future enhancements and policy enforcement.

---

## 🧠 Learning & Challenge Scope

The project is structured to simulate **real-world DevOps scenarios** with hands-on debugging opportunities.
Participants are encouraged to:

* Analyze pipeline behavior and resolve build/deployment issues.
* Optimize Docker images and environment configurations.
* Scale, monitor, and secure workloads using cloud services.
* Migrate and adapt the same setup to **AWS** for cross-cloud experience.

---

## 📂 Repository Structure

```
/app
 ├── frontend       # React UI
 └── backend        # Node.js API

/docker             # Dockerfiles and container configs
/scripts            # Automation & setup scripts
/terraform          # IaC provisioning files
/security           # Security & compliance modules
/monitoring         # Observability & health monitoring setup
```

---

## 🧾 Features Summary

* Dynamic order placement system connected to MongoDB Atlas.
* Responsive UI built with Chakra-UI.
* API routes secured and validated.
* Scalable microservice-based architecture.
* Integrated CI/CD for continuous delivery to cloud.
* Complete DevOps structure following enterprise best practices.

---

## 🏁 Outcome

AuraBeauty stands as a **professional-grade DevOps project** demonstrating:

* Full CI/CD workflow automation
* Cross-cloud deployability
* Modular and maintainable architecture
* Strong alignment with **real-world DevOps engineering standards**

