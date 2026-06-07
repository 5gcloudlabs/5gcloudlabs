# 5G Cloud Labs

**An open-source cloud-based telecom laboratory for experimenting with AI and automation use cases.**

---

## Overview

5G Cloud Labs is an open-source initiative focused on creating practical telecom laboratory environments for experimenting with automation and AI-assisted operational workflows.

The project combines Infrastructure as Code, Kubernetes, GitOps practices, and open-source telecom software to create reproducible environments suitable for experimentation, learning, and prototyping.

The goal is not simply to deploy telecom workloads, but to provide a foundation where automation and AI ideas can be developed, tested, and evaluated against realistic network environments.

---

## Why 5G Cloud Labs?

5G Cloud Labs provides a reproducible telecom environment that can be deployed on demand and used to evaluate automation and AI use cases against realistic network workloads.

The platform is intended to reduce the effort required to create a functional telecom test environment, allowing engineers to focus on experimentation rather than infrastructure setup.

Current capabilities enable users to:

- Deploy a complete telecom laboratory environment in minutes
- Evaluate automation workflows against realistic network functions
- Test AI-assisted operational tooling
- Validate deployment procedures and runbooks
- Experiment with subscriber provisioning workflows
- Simulate radio access and user equipment behaviour
- Recreate environments consistently for testing and learning

The objective is to provide a practical foundation for experimentation, iteration, and learning.

---

## The Laboratory Today

The project currently provides an AWS-based telecom laboratory environment that can be deployed on demand and used for experimentation.

The environment combines:

- Infrastructure provisioning with OpenTofu
- Kubernetes orchestration
- GitOps workflows with Argo CD
- Free5GC
- UERANSIM
- Web-based operational tooling

The first experiment built on top of this environment is the Telco Deployment Assistant, which explores how AI-assisted tooling can simplify the deployment and operation of telecom platforms.

This is an ongoing project and an open invitation to experiment, learn, and contribute. Future work may expand existing capabilities, introduce new automation workflows, or explore entirely new AI use cases.

AWS currently serves as the primary laboratory environment. Additional cloud platforms may be introduced over time where they help broaden experimentation and learning opportunities.

---

## Repositories

### Platform Environments

| Repository | Description |
|------------|-------------|
| `5g-platform-aws` | AWS-based telecom laboratory environment |
| `5g-platform-gcp` | GCP-based telecom laboratory environment *(future)* |

### Experiments

| Repository | Description |
|------------|-------------|
| `telco-deployment-assistant` | AI-assisted deployment and operational workflows |

---

## Project Philosophy

5G Cloud Labs is intentionally experimental.

The project does not aim to prescribe how telecom automation or AI-assisted operations should be implemented.

Instead, it provides an environment where ideas can be explored, tested, and evaluated against realistic telecom workloads.

Contributions, alternative approaches, and new experiments are encouraged.

---

## Getting Started

If you're new to the project, start with:

➡ **5g-platform-aws**

This repository contains the current AWS-based laboratory environment and deployment workflow.

---

## Contributing

Contributions, ideas, discussions, and experiments are welcome.

Whether your interests are in:

- Telecommunications
- Cloud Infrastructure
- Kubernetes
- Infrastructure as Code
- GitOps
- Automation
- Artificial Intelligence

there is room to experiment, learn, and contribute.

---

## Links

🌐 Website: https://5gcloudlabs.ai

📧 Contact: info@5gcloudlabs.ai
