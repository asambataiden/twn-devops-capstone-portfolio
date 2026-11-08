# TechWorld with Nana — DevOps Capstone Engineering Portfolio

**Six capstone projects · Cloud & Platform Engineering · CI/CD · DevSecOps · Reliability Automation**

This repository is the public entry point to six hands-on capstone implementations from the **TechWorld with Nana AI-Enhanced DevOps Bootcamp**. Each project repository contains its implementation, README, supporting documentation, validation evidence and clearly stated limitations.

> **Status:** Awarded the **Certified DevOps Practitioner** credential by TechWorld with Nana (Credly badge shown by the credential holder in November 2026). [Verify individual Credly badge](https://www.credly.com/badges/95f47332-84a4-4ee1-82c5-60a1abafdf58/public_url). The project evidence below describes historical test results, not necessarily running infrastructure today.

## For recruiters and engineering managers

**Senior Software Engineer | Cloud & Platform Engineering | DevOps & DevSecOps | AI-assisted automation**

I bring 9+ years of enterprise software engineering experience, beginning at Deutsche Post DHL IT Services in March 2017, with a background in Java, Spring Boot, APIs and distributed systems. I have developed practical DevOps skills throughout my career and used the TechWorld with Nana program to consolidate them into connected, end-to-end delivery workflows. This portfolio is **hands-on training and independent project evidence**, not a claim that every cloud tool has been used in production employment.

### Start here — three engineering case studies

| If you are assessing… | Start with | Evidence to look for |
|---|---|---|
| Software delivery, CI/CD and Kubernetes | [Capstone 01 — Jenkins → ECR → EKS](https://github.com/asambataiden/twn-capstone-01-jenkins-ecr-eks-cicd) | Maven verification, immutable image digest, deployment approval, RBAC and rollout verification |
| Infrastructure, secure deployment and release reliability | [Capstone 03 — Terraform + Jenkins + SSM](https://github.com/asambataiden/twn-capstone-03-complete-cicd-terraform) | Separated IAM roles, pinned Shared Library, container health verification and mocked rollback regression tests |
| Cloud-native operations and microservices | [Capstone 04 — Kubernetes Online Boutique](https://github.com/asambataiden/twn-capstone-04-kubernetes-microservices) | Workload rollout evidence, service connectivity, manual shopping-flow tests and explicit environment limitations |

**Additional work:** [Capstone 02 — Terraform & Ansible](https://github.com/asambataiden/twn-capstone-02-terraform-ansible-eks) · [Capstone 05 — Jenkins & Ansible](https://github.com/asambataiden/twn-capstone-05-ansible-jenkins) · [Capstone 06 — Python website recovery](https://github.com/asambataiden/twn-capstone-06-website-recovery).

**Engineering standards:** reproducibility, least privilege, explicit release gates, idempotency, validated outcomes, accurate evidence and clear technical documentation. Refer to each project for the exact scope, implementation status, third-party starter components and remaining risks.

**AI positioning:** The bootcamp included AI-enhanced learning. I use AI-assisted engineering as a professional development area; the capstones below are primarily evidence of **cloud, platform and DevOps engineering**, not proof of a production AI/ML or MLOps platform.

[LinkedIn profile](https://www.linkedin.com/in/tamajong-asamba-aiden-115b42105/) · [GitHub profile](https://github.com/asambataiden)

## Selected engineering outcomes

- **Capstone 01:** Jenkins verified a Maven build, ECR image publication and digest-identified EKS rollout (27 Oct 2026).
- **Capstone 02:** Provisioned a dedicated Terraform-managed EKS environment, deployed Nginx with Ansible, verified idempotency and removed 58 managed resources (28 Oct 2026).
- **Capstone 03:** Validated Jenkins-to-ECR-to-EC2 delivery via SSM, with independently checked container health and five mocked rollback tests (1 Nov 2026).
- **Capstone 04:** Validated an 11-service Online Boutique deployment and browser shopping flow on a three-node LKE environment (25 Oct 2026).
- **Capstone 05:** Verified Jenkins–Ansible configuration reconciliation on two EC2 hosts with HTTP 200 responses and zero reported changes (25 Oct 2026).
- **Capstone 06:** Passed 35 Python tests and documented controlled Linode outage detection, Telegram alerting and recovery exercises (25 Oct 2026).

## Credential

**Certified DevOps Practitioner — TechWorld with Nana**  
[Verify my individual badge on Credly](https://www.credly.com/badges/95f47332-84a4-4ee1-82c5-60a1abafdf58/public_url) · [Credly profile](https://www.credly.com/users/tamajong-asamba-aiden)

The individual badge URL was provided by the credential holder.

## Capstone projects

| Capstone | Engineering focus | Core technologies | Documentation |
|---|---|---|---|
| **01** | Jenkins CI/CD to Kubernetes | Jenkins, Java/Maven, Docker, AWS ECR/EKS | [Source](https://github.com/asambataiden/twn-capstone-01-jenkins-ecr-eks-cicd) · [Review summary](https://github.com/asambataiden/twn-capstone-01-jenkins-ecr-eks-cicd/blob/main/docs/certification-submission.md) |
| **02** | Infrastructure provisioning and configuration | Terraform, Ansible, EKS, Nginx | [Source](https://github.com/asambataiden/twn-capstone-02-terraform-ansible-eks) · [Review summary](https://github.com/asambataiden/twn-capstone-02-terraform-ansible-eks/blob/main/docs/certification-submission.md) |
| **03** | Complete CI/CD delivery workflow | Jenkins Shared Library, Docker, AWS ECR, SSM, EC2, Terraform | [Source](https://github.com/asambataiden/twn-capstone-03-complete-cicd-terraform) · [Engineering documentation](https://github.com/asambataiden/twn-capstone-03-complete-cicd-terraform/tree/main/docs) |
| **04** | Kubernetes microservice deployment | Linode Kubernetes Engine, Google Online Boutique | [Source](https://github.com/asambataiden/twn-capstone-04-kubernetes-microservices) · [Review summary](https://github.com/asambataiden/twn-capstone-04-kubernetes-microservices/blob/main/docs/certification-submission.md) |
| **05** | Jenkins-driven Ansible automation | Jenkins, Ansible, AWS EC2, Docker Compose | [Source](https://github.com/asambataiden/twn-capstone-05-ansible-jenkins) · [Review summary](https://github.com/asambataiden/twn-capstone-05-ansible-jenkins/blob/main/docs/certification-submission.md) |
| **06** | Automated website monitoring and recovery | Python, HTTP checks, Telegram, Docker, Linode | [Source](https://github.com/asambataiden/twn-capstone-06-website-recovery) · [Review summary](https://github.com/asambataiden/twn-capstone-06-website-recovery/blob/main/docs/certification-submission.md) |

### Shared pipeline code

[**TWN Jenkins Shared Library**](https://github.com/asambataiden/twn-devops-bootcamp-jenkins-shared-library) — reusable Jenkins pipeline steps and delivery orchestration used across the bootcamp capstone work.

## For certification reviewers

Start with the [**Certification Submission Guide**](docs/certification-submission.md), then follow the main-branch links above. Project-specific READMEs distinguish verified implementation from proposed enhancements and unresolved limitations.

## Engineering practices

- **CI/CD:** source control, build and container validation, immutable image references, release verification and guarded deployment steps.
- **Infrastructure automation:** Terraform provisioning, Ansible playbooks, repeatability and idempotency checks.
- **Cloud native:** Kubernetes workload configuration, networking and service validation.
- **Security:** scoped cloud credentials, separation of secrets and source code, Git history scanning and clear evidence boundaries.
- **Reliability:** service health checks, alerting, recovery workflows and tested rollback logic.

## Scope and integrity

The projects document personal hands-on work performed during the bootcamp. Training examples, starter applications and third-party components remain attributed in the underlying project repositories. Course materials belong to **TechWorld with Nana**.

Selected limitations: Capstone 02 resources were decommissioned after testing; Capstone 03 does not claim a live failure-injected rollback; Capstone 04 documents partial parity with the original course architecture. Individual project validation is evidence of implemented engineering work, not a claim of production readiness.

The older module and learning portfolio is maintained separately and is not part of this public certification landing page.
