# Hi there 👋 I'm Armin

Platform Engineer | DevOps/SRE | Infrastructure Architect

My career started in datacenters and network engineering long before the cloud era.  
That background still shapes how I design modern infrastructure platforms today.

I approach **Infrastructure as Code not as automation, but as architecture expressed in code**.

This repository documents the **engineering philosophy and design principles** behind how I design infrastructure platforms.

---

## What this repository contains

This repository is a collection of short essays about platform engineering and Infrastructure as Code.

Topics include:

- [Infrastructure Code as Architecture](docs/infrastructure-as-architecture.md)
- [Simplicity vs Complexity in Infrastructure Design](docs/simplicity-vs-complexity.md)
- [Architecture Should Be Understandable](docs/architecture-understandable.md)
- [Standardization Without Dogma](docs/standardization-without-dogma.md)
- [Infrastructure as a Platform Product](docs/platform-as-product.md)
- [Repository Architecture for Infrastructure](docs/repository-architecture.md)
- [GitOps as an Operating Model](docs/gitops-thinking.md)
- [Designing Infrastructure for the Next Engineer](docs/designing-for-next-engineer.md)

---

## Sample repository: centralized modules and org standards

For a **concrete layout** that matches how I think about IaC as architecture—especially **central Terraform module references**, **shared global configuration**, and **guardrails that encode org policy**—see **[companyx-cloud](https://github.com/armin-x86/companyx-cloud/tree/main)** on GitHub. It is a demo AWS stack (Terraform + Ansible) with wrapper-style modules, environment config modules, Terraform assertions (for example VPC/subnet validation), VPC endpoints, SSM-driven operations, and repo tooling (pre-commit, Trivy, detect-secrets) to keep changes consistent and reviewable.

---

## Core idea

Infrastructure as Code is often treated as automation.

I see it differently.

> Infrastructure code is architecture.  
> And when designed well, it becomes the **operating system of the platform**.

The documents in this repository explore that idea in depth.

## Principles I Use When Designing Platforms
1. Simplicity before flexibility
2. Infrastructure should be readable
3. Prefer composition over abstraction
4. Standardization reduces cognitive load
5. Infrastructure should be operable by others
6. Platforms should empower teams, not gate them