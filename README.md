# devops-capstone

# DevOps Capstone Project

A production-style DevOps platform built with **Terraform (AWS)**, **EKS (Kubernetes)**, **Helm**, and **GitHub Actions**.

## Features
- Multi-AZ VPC, EKS cluster, and ECR repo (Terraform IaC)
- Containerized sample app (Python/Flask)
- CI/CD pipeline (GitHub Actions): build → test → deploy
- Monitoring stack (Prometheus + Grafana)
- SLOs, runbooks, and architecture docs

## Repo Structure
- `infra/` → Terraform modules for AWS infra
- `platform/` → Helm charts (app + monitoring)
- `ci/` → GitHub Actions workflows
- `app/` → Sample containerized service
- `docs/` → Architecture, diagrams, SLOs, runbooks

## How to Use
1. Provision infra with Terraform
2. Deploy app via Helm to EKS
3. Monitor metrics with Grafana
4. Trigger CI/CD pipeline via PR/merge

---

