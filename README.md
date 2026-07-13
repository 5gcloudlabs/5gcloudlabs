# 5G Cloud Labs

**An open-source R&D platform for developing, integrating, and evaluating network automation and AI use cases using reproducible cloud-based 5G network environments.**

---

## Overview

5G Cloud Labs brings together Infrastructure as Code, Kubernetes, GitOps, and open-source 5G software to create reproducible platform environments for experimentation and integration.

Rather than focusing on a single solution, the project provides a common environment where automation and AI use cases can be developed independently, integrated into a platform environment, and evaluated against realistic 5G network scenarios.

The long-term goal is to make it easier to build, test, compare, and evolve new approaches to operating cloud-native mobile networks.

---

# Project Architecture

```text
                              5G Cloud Labs
                                     │
        ┌────────────────────────────┴────────────────────────────┐
        │                                                         │
        ▼                                                         ▼
 Platform Environments                                  Use Case Repositories
        │                                                         │
        │                                                         │
 ┌──────┴─────────┐                                  ┌────────────┴────────────┐
 │                │                                  │                         │
 ▼                ▼                                  ▼                         ▼
5g-platform-aws 5g-platform-gcp            network-deployment-agent      Future Use Cases
      │                │                              │                         │
      └────────────────┴──────────────┬───────────────┘
                                      │
                                      ▼
                     Platform Integration & Validation
                                      │
                                      ▼
                 Reproducible 5G Network Environment
                                      │
                                      ▼
          Automation • AI • Experimentation • End-to-End Evaluation
```

The project separates reusable platform environments from individual automation and AI use cases.

Platform environments provide the cloud infrastructure, Kubernetes platform, networking, observability, and deployable 5G network environment required for integration and evaluation.

Use cases are developed independently and integrated into a platform environment when they are ready for end-to-end evaluation.

This model allows contributors to work independently while keeping platform environments stable and reusable.

---

# Repository Roles

## Platform Environments

Platform repositories provide reproducible cloud environments used for integration and evaluation.

| Repository | Description |
|------------|-------------|
| **5g-platform-aws** | AWS platform environment built on OpenTofu, Amazon EKS, GitOps, and a reproducible 5G network environment. |
| **5g-platform-gcp** *(planned)* | Future Google Cloud platform environment following the same architecture. |

---

## Use Case Repositories

Use case repositories contain automation and AI capabilities that are developed independently before being integrated into a platform environment.

Current examples include:

| Repository | Description |
|------------|-------------|
| **network-deployment-agent** | AI-assisted operational interface for deploying and provisioning network components through natural language. |

Future use cases may include additional automation, observability, orchestration, optimization, testing, or AI capabilities.

---

# Development Model

Most contributors do **not** need to deploy an entire platform environment.

Typical development follows this workflow:

```text
Idea
   │
   ▼
Local Development
   │
   ▼
Use Case Repository
   │
   ▼
Platform Integration
   │
   ▼
End-to-End Evaluation
```

Most development can therefore be performed locally before integrating changes into a deployed platform environment for validation.

---

# Current Platform

Today, AWS serves as the primary integration laboratory.

The AWS platform provides:

- Cloud infrastructure provisioning with OpenTofu
- Amazon EKS
- GitOps platform bootstrap
- Multi-network Kubernetes support
- Observability
- Deployable Free5GC network environment
- AI-assisted deployment and provisioning through the Network Deployment Agent

Future platform environments will follow the same integration model across additional cloud providers.

---

# Contributing

Contributions are welcome across both platform environments and use case repositories.

Typical contributions include:

- Platform infrastructure
- Kubernetes platform services
- Network automation
- AI use cases
- Deployment workflows
- Observability
- Documentation

If you're unsure where a contribution belongs, open an issue in the appropriate repository and we'll be happy to discuss it.

---

# Getting Started

| Goal | Repository |
|------|------------|
| Learn how the AWS laboratory works | **5g-platform-aws** |
| Develop an AI or automation capability | Relevant use case repository |
| Understand the overall project | This organization profile |

---

# Vision

5G Cloud Labs is designed as a long-term experimentation platform rather than a fixed solution.

As additional platform environments become available, the same development model can be applied across multiple cloud providers, allowing automation and AI use cases to be evaluated consistently using comparable cloud-native 5G network environments.

---

## Links

🌐 Website: **https://5gcloudlabs.ai**

📧 Contact: **info@5gcloudlabs.ai**
