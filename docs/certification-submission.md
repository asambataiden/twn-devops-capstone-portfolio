# TWN Certified DevOps Practitioner — Submission Guide

**Portfolio landing page:** [TWN DevOps Capstone Portfolio](../README.md)

**Credential status:** The repository owner has shared their awarded **Certified DevOps Practitioner** credential from TechWorld with Nana (November 2026). [Credly profile](https://www.credly.com/users/tamajong-asamba-aiden) provided by the credential holder; direct individual-badge URL not yet recorded. This page preserves the original project submission guidance and historical evidence boundaries.

## Six required projects

1. [Capstone 01 — Jenkins, ECR and EKS](https://github.com/asambataiden/twn-capstone-01-jenkins-ecr-eks-cicd/blob/main/docs/certification-submission.md)
2. [Capstone 02 — Terraform, Ansible and EKS](https://github.com/asambataiden/twn-capstone-02-terraform-ansible-eks/blob/main/docs/certification-submission.md)
3. [Capstone 03 — Complete CI/CD](https://github.com/asambataiden/twn-capstone-03-complete-cicd-terraform/tree/main/docs)
4. [Capstone 04 — Kubernetes Microservices](https://github.com/asambataiden/twn-capstone-04-kubernetes-microservices/blob/main/docs/certification-submission.md)
5. [Capstone 05 — Ansible and Jenkins](https://github.com/asambataiden/twn-capstone-05-ansible-jenkins/blob/main/docs/certification-submission.md)
6. [Capstone 06 — Website Recovery](https://github.com/asambataiden/twn-capstone-06-website-recovery/blob/main/docs/certification-submission.md)

**Shared component:** [Jenkins Shared Library](https://github.com/asambataiden/twn-devops-bootcamp-jenkins-shared-library)

## Reviewer workflow

- Open each project on its **main** branch and read its README.
- Follow project-specific architecture, implementation, validation and learning sections.
- Distinguish historical test evidence from currently running infrastructure.
- Use each project's limitations and improvement notes to understand what was not implemented or not proven.

## Security and exposure review

- Six capstone repositories: Gitleaks Git history scans reported no detected leaks (255 commits across those scans).
- Jenkins Shared Library: Gitleaks Git history scan reported no detected leaks (77 commits).
- Public repositories may still contain operational metadata or other details not caught by automated scanning.
- Private module exercises and the original learning catalogue are intentionally separate from this capstone portfolio.

## Submission checklist

- [x] Create a dedicated public capstone landing page with links to all six projects.
- [x] Make the six capstone repositories and shared Jenkins library accessible publicly.
- [x] Perform automated secret-history scanning of these seven repositories.
- [x] Complete the official TWN validation and receive the Certified DevOps Practitioner credential (shown by the holder).
- [ ] Check main-branch documentation links and diagrams before submission.
- [x] Submit the certification application (credential subsequently awarded; exact submission details not reproduced here).
- [ ] Save the submission date and confirmation.
- [x] Add the credential holder's Credly profile URL to this portfolio.
- [ ] Add the direct individual badge-verification URL, if available.

## Evidence boundaries

- Capstone 02: AWS infrastructure was decommissioned after validation.
- Capstone 03: best-effort rollback was mock-tested; live failure injection was not established.
- Capstone 04: documented platform-specific constraints and partial course-scenario parity.

> This repository is an independent student portfolio and does not represent official TWN certification endorsement.
