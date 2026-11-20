# SolidaryTech

**Cloud-Native Platform | Architecture, DevSecOps & Platform Engineering**

## Overview

SolidaryTech is a nonprofit-oriented platform designed to connect non-governmental organizations (NGOs), donors, and volunteers.

The platform originated as a Hackathon project developed during the FIAP Postgraduate Program in DevOps & Cloud Architecture.

This repository represents a **ground-up reconstruction** of the original solution, focusing on hands-on engineering, architectural improvements, security, automation, operational reliability, and industry best practices.

## Project Objectives

The reconstruction aims to:

- Design and evolve a maintainable, cloud-native microservices platform.
- Apply Infrastructure as Code (IaC) and declarative configuration management.
- Establish secure, reproducible CI/CD workflows.
- Adopt DevSecOps, GitOps, and automated quality controls where appropriate.
- Implement observability, reliability, and operational practices.
- Incorporate cost awareness, security, and disaster recovery considerations.
- Maintain architecture decisions, technical documentation, and validation evidence under version control.

## Functional Scope

The original platform consists of three core microservices:

| Service | Responsibility |
|---|---|
| `ngo-service` | NGO registration and management |
| `donation-service` | Donation processing and related transactions |
| `volunteer-service` | Volunteer registration and engagement |

These services provide the functional reference for the reconstruction. Their internal implementations and integrations may evolve as architectural decisions are reviewed.

## Engineering Principles

The project follows these principles:

- **Git as the source of truth:** version-controlled source code, declarative configurations, and technical documentation.
- **Documentation as Code:** documentation evolves alongside implementation through commits and pull requests.
- **Security by Design:** least privilege, secure authentication, secrets management, and security validation.
- **Automation with Purpose:** automation should improve reliability and reproducibility without introducing unnecessary complexity.
- **Infrastructure as Code:** infrastructure changes should be declarative, reviewable, and traceable.
- **Evidence-Based Validation:** implemented configurations are not considered validated until their behavior has been verified.
- **Incremental Delivery:** prioritize small, meaningful changes that can be reviewed and tested independently.

## Project Status

**Current phase:** Foundation and repository organization.

The original FIAP Hackathon implementation serves as a historical reference, not as proof of the current reconstruction's operational state.

Architecture decisions, infrastructure, application components, and delivery workflows will be documented as they are designed, implemented, and validated.

## Repository Organization

This repository is being organized incrementally.

Application code, Infrastructure as Code, platform configurations, architecture documentation, and GitHub workflows will be introduced as their responsibilities and