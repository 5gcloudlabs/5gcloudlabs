# 5G Cloud Labs

**An open-source cloud-based telecom laboratory for experimenting with AI and automation use cases.**

---

## Overview

5G Cloud Labs is an open-source initiative focused on creating practical telecom laboratory environments that can be used to explore automation and AI-assisted operational workflows.

The project combines Infrastructure as Code, Kubernetes, GitOps practices, and open-source telecom software to create reproducible environments suitable for experimentation, learning, and prototyping.

The goal is not simply to deploy telecom workloads, but to provide a foundation where automation and AI ideas can be developed, tested, and evaluated against realistic network environments.

---

## Why 5G Cloud Labs?

Access to telecom laboratory environments can be expensive, complex, and difficult to reproduce.

5G Cloud Labs aims to lower that barrier by providing automated deployment workflows that make it easier to create telecom environments on public cloud infrastructure.

These environments can then be used to experiment with topics such as:

- Deployment automation
- AI-assisted operations
- Network validation
- Observability workflows
- Subscriber lifecycle management
- Configuration management
- Multi-cloud deployment approaches

---

## Current Focus

The current implementation automates the deployment of a Kubernetes-based 5G environment on AWS using:

- OpenTofu
- Amazon EKS
- Argo CD
- Free5GC
- UERANSIM

This environment serves as the foundation for ongoing AI and automation experiments.

---

## Repositories

### Platform Implementations

| Repository | Description |
|------------|-------------|
| `5g-platform-aws` | AWS-based telecom laboratory platform |
| `5g-platform-gcp` | GCP-based telecom laboratory platform *(planned)* |
| `5g-platform-azure` | Azure-based telecom laboratory platform *(planned)* |

### Experiments

| Repository | Description |
|------------|-------------|
| `telco-deployment-assistant` | AI-assisted deployment workflows and operational automation |

---

## Project Philosophy

5G Cloud Labs is intentionally practical.

The objective is not to predict the future of telecom operations, but to provide an environment where ideas can be tested, measured, and improved.

Experiments should be reproducible, transparent, and grounded in real operational challenges.

---

## Getting Started

If you're new to the project, start with:

➡ **5g-platform-aws**

This repository contains the current reference implementation and deployment workflow.

---

## Contributing

Contributions, ideas, and discussions are welcome.

Whether your interests are in telecom, cloud infrastructure, automation, Kubernetes, or AI, there is room to experiment and learn together.

---

## Links

Website: 5gcloudlabs.ai

Contact: info@5gcloudlabs.ai
