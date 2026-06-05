# LnT DevOps Training Projects

[![Training](https://img.shields.io/badge/Program-LnT%20DevOps%20Training-orange?style=flat)](https://github.com/BurhanuddinLokhandwala10/LnT_Mini_Project)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat)](LICENSE)

A consolidated repository containing all hands-on projects built during the **LnT DevOps Training Program**. Each project is a self-contained, production-oriented implementation covering a core area of modern DevOps — from CI/CD pipelines and containerization to infrastructure automation and Kubernetes orchestration.

---

## Table of Contents

- [Projects Overview](#projects-overview)
- [Technology Stack](#technology-stack)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)

---

## Projects Overview

### 1. **CI/CD Pipeline — Day 3**
A complete CI/CD pipeline implementation using **GitHub Actions** built around a Python Calculator application. Demonstrates automated testing (pytest) and static code analysis (pylint) on every commit.

**Location:** `LNT_ALL_PROJECTS/CICD_PIPELINE_DAY3/`

### 2. **Dockerised To-Do API**
A production-ready, containerized REST API for to-do management built with Python Flask, multi-stage Docker builds, and Gunicorn as the WSGI server.

**Location:** `LNT_ALL_PROJECTS/Dockerised-TO-DO/`

### 3. **Git Workflow Simulator**
A documentation-first project that models a professional GitHub collaboration workflow for a 3-person engineering team, with branching strategies and pull request standards.

**Location:** `LNT_ALL_PROJECTS/Git_Worflow_Simulator/`

### 4. **Infrastructure as Code Pipeline**
A production-ready Terraform + GitHub Actions CI/CD pipeline for deploying AWS infrastructure with fully automated linting, planning, and applying stages.

**Location:** `LNT_ALL_PROJECTS/IAC_Pipeline/`

### 5. **Kubernetes Autoscaling — Day 4**
A complete Kubernetes autoscaling setup demonstrating Horizontal Pod Autoscaler (HPA) with Metrics Server integration using Nginx containerized application.

**Location:** `LNT_ALL_PROJECTS/LnT_Day_4/`

---

## Technology Stack

| Category | Technologies |
|----------|-------------|
| **Containerization** | Docker, Docker Compose, Multi-stage builds, Gunicorn |
| **Orchestration** | Kubernetes, HPA, Metrics Server |
| **CI/CD** | GitHub Actions, Automated testing, Pipeline stages |
| **Infrastructure as Code** | Terraform, AWS EC2, Security Groups |
| **Version Control** | Git, Branch strategies, CODEOWNERS, PR templates |
| **Application** | Python 3.13, Flask 3.0, pytest, pylint |
| **Cloud** | AWS (EC2, IAM, Security Groups) |

---

## Repository Structure

```
LnT_Mini_Project/
├── README.md                          # This file
└── LNT_ALL_PROJECTS/                  # Main training workspace
    ├── CICD_PIPELINE_DAY3/            # GitHub Actions CI/CD pipeline
    ├── Dockerised-TO-DO/              # Production Docker REST API
    ├── Git_Worflow_Simulator/         # Git collaboration workflow model
    ├── IAC_Pipeline/                  # Terraform + GitHub Actions IaC
    ├── LnT_Day_4/                     # Kubernetes HPA deployment
    └── ... (additional projects)
```

---

## Getting Started

### Prerequisites
- Git
- Docker (for containerization projects)
- Kubernetes cluster (for K8s projects)
- Terraform (for IAC projects)
- Python 3.10+ (for application projects)

### Cloning the Repository

```bash
git clone https://github.com/BurhanuddinLokhandwala10/LnT_Mini_Project.git
cd LnT_Mini_Project
```

### Navigating to Projects

Each project directory contains its own `README.md` with setup instructions:

```bash
# Example: Navigate to CI/CD project
cd LNT_ALL_PROJECTS/CICD_PIPELINE_DAY3

# Follow the project-specific README
cat README.md
```

---

## Training Curriculum

**LnT DevOps Training Program** - Progressive learning path covering modern DevOps practices:

- **Day 3:** CI/CD Pipelines with GitHub Actions
- **Day 4:** Kubernetes Orchestration and Autoscaling
- **Supplementary:** Docker, Git workflows, Infrastructure as Code

---

## License

This project is licensed under the **MIT License** - see the LICENSE file for details.

---

## About

This repository showcases hands-on DevOps solutions and learning milestones from the LnT Mini Project training program. Each project folder is self-contained and ready for review, testing, or deployment.

*Last Updated: June 2026*
