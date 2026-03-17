# Ariel De Los Angeles — Cloud & Security Engineer

> Building enterprise-grade cloud infrastructure from a homelab.
> DLA Group Inc | 

---

## About Me

I'm a Cloud & Security Engineer focused on AWS, Azure, and DevSecOps. I build and operate a
multi-cloud homelab that mirrors real enterprise environments — hybrid identity, CI/CD pipelines,
IaC automation, and security tooling running 24/7 on bare metal.

My lab isn't for tutorials. It's for building the same patterns I'd deploy in production:
IAM Roles Anywhere instead of static keys, Entra ID Connect sync instead of manual provisioning,
Terraform modules instead of console clicks.

---

## Certifications

| Cert | Status |
|---|---|
| AWS Solutions Architect Associate (SAA-C03) | Passed Jan 2026 |
| ISC2 Certified in Cybersecurity (CC) | Passed |
| CompTIA Security+ | Passed |
| SC-300 (Microsoft Identity & Access Admin) | In Progress |
| AZ-104 (Azure Administrator) | In Progress |
| AWS SCS-C03 (Security Specialty) | Planned |
| AWS AIP-C01 (AI Practitioner) | Planned |

---

## Homelab Infrastructure

**Compute:** Proxmox 

| Component | Details |
|---|---|
| Hypervisor | Proxmox VE |
| Windows Server | Windows DataCenter— AD DS, DLAGROUP.local, Azure Arc onboarded |
| Docker VM | Jenkins, Gitea, MinIO, Nginx Proxy Manager, Uptime Kuma |
| Network | pfSense, VLANs, Site-to-Site VPN (Terraform-managed) |
| PKI | Self-managed CA |

**AWS:**
- Multi-VPC architecture with isolated network segments
- IAM Roles Anywhere — keyless auth from on-prem Jenkins
- GuardDuty, Security Hub, CloudTrail enabled
- Terraform state in S3, modular repo structure

**Azure (Pay-as-you-go):**
- M365 E5 + Governance
- Hybrid identity via Entra Connect delta sync
- Azure Arc — DC onboarded
- Custom domains managed via Route53

---

## Featured Repos

| Repo | What It Does |
|---|---|
| [jenkins-iam-roles-anywhere](https://github.com/arieldla/jenkins-iam-roles-anywhere) | Keyless AWS auth from on-prem Jenkins using X.509 certs — no static IAM keys |
| [jenkins-terraform-pipeline](https://github.com/arieldla/jenkins-terraform-pipeline) | Jenkins CI/CD pipeline driving Terraform against AWS with S3 backend |
| [jenkins-labs](https://github.com/arieldla/jenkins-labs) | 12-lab progressive Jenkins series: params, remote state, shared libs, GitOps |
| [cicd-golden-pipeline](https://github.com/arieldla/cicd-golden-pipeline) | Reusable golden pipeline template with security scanning baked in |
| [jenkins-shared-library](https://github.com/arieldla/jenkins-shared-library) | Shared Groovy library for consistent pipeline steps across all Jenkins jobs |

---

## Current Focus

Working through a 103-day multi-cloud certification lab plan:

- **SC-300** — Tenant hardening, Conditional Access, PIM, Identity Governance
- **AZ-104** — Azure administration, RBAC, networking, monitoring
- **AWS SCS-C03** — Security specialty, GuardDuty, Security Hub, KMS, IAM deep dive
- **AWS AIP-C01** — AI/ML on AWS, SageMaker, Bedrock

---

## Tech Stack

\`\`\`
Cloud:     AWS  |  Azure
IaC:       Terraform  |  Ansible (learning)
CI/CD:     Jenkins  |  GitHub Actions
Security:  IAM Roles Anywhere  |  Entra ID  |  GuardDuty  |  Trivy
OS:        Ubuntu  |  Windows Server  |  Kali
Network:   pfSense  |  VLANs  |  Site-to-Site VPN  |  Tailscale
Storage:   MinIO (S3-compatible)  |  AWS S3
Auth:      Entra ID P2  |  Azure Arc  |  Self-managed PKI
\`\`\`

---

## Connect

- LinkedIn: [linkedin.com/in/ariel-de-los-angeles-7a386b347](https://linkedin.com/in/ariel-de-los-angeles-7a386b347)
- GitHub: [github.com/arieldla](https://github.com/arieldla)
