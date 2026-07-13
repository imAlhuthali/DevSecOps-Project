
# DevSecOps Project

This project implements DevSecOps using a full CI/CD pipeline that integrates security scanning, containerization, orchestration, and monitoring into every stage of the software delivery lifecycle — from code commit to production deployment.

The application itself is a Netflix clone (React + TypeScript, powered by the TMDB API), used here as a sample workload to demonstrate the pipeline end-to-end.

## Tech Stack

- **Source Control:** GitHub
- **CI/CD Orchestration:** Jenkins
- **Containerization:** Docker
- **Code Quality & Security Analysis:** SonarQube
- **Vulnerability Scanning (Images & Filesystem):** Trivy
- **Dependency Vulnerability Scanning:** OWASP Dependency-Check
- **Container Orchestration:** Kubernetes
- **Package Management (K8s):** Helm
- **GitOps Continuous Deployment:** ArgoCD
- **Metrics Collection:** Prometheus + Node Exporter
- **Dashboards & Visualization:** Grafana
- **Infrastructure:** AWS EC2
