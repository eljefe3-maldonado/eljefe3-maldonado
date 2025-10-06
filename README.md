<h1 align="center">☁️ Cloud Security Portfolio</h1>
<h3 align="center">Wilberto Maldonado</h3>
<p align="center">
  <strong>AWS Multi-Account • Terraform • Ansible • Compliance Automation</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-Multi--Account-orange?logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-1.9%2B-7B42BC?logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-Automation-EE0000?logo=ansible&logoColor=white" />
  <img src="https://img.shields.io/badge/NIST-800--171%20%7C%20800--53%20%7C%20CMMC-1E3A8A" />
</p>

---

### 👋 Overview
This portfolio showcases real-world **AWS Cloud Security Engineering** using:
- **Terraform** for Infrastructure as Code  
- **Ansible** for Cloud-native configuration via AWS Systems Manager (SSM)  
- **GitHub Actions** with OIDC for CI/CD (no static keys)  
- **NIST 800-171 / CMMC / NIST 800-53** frameworks for compliance automation  

Each project emphasizes security, automation, and scalability—structured so others can learn step-by-step.

---

### 🧩 Featured Projects
| Area | Repository | Description |
|------|-------------|-------------|
| 🌐 **Platform Foundation** | [tf-platform-foundation](https://github.com/eljefe3-maldonado/tf-platform-foundation) | AWS Organizations, OUs, SCPs, and Control Tower bootstrap for multi-account governance |
| 🛡️ **Policies** | [policies-scp](https://github.com/eljefe3-maldonado/policies-scp) | Baseline JSON Service Control Policies (Deny Root, Allowed Regions, Require Tags) |
| ⚙️ **Automation** | [ansible-cloud](https://github.com/eljefe3-maldonado/ansible-cloud) | Cloud-aware Ansible playbooks using AWS SSM for patching and hardening (no bastions) |

---

### 🚀 Roadmap
| Phase | Focus | Description | Status | Repository |
|:--:|:--|:--|:--:|:--|
| **0** | 🖥️ Developer Environment Setup | Install Terraform, Ansible, AWS CLI, Git, and VS Code; configure AWS SSO & keys | ✅ **Complete** | Internal Setup |
| **1** | 🌐 Platform Foundation | Establish AWS Organizations, OUs, SCPs, Tag Policies, and OIDC for CI/CD | 🧩 **In Progress** | [tf-platform-foundation](https://github.com/eljefe3-maldonado/tf-platform-foundation) |
| **2** | 🛡️ Shared Security & Compliance | Centralize CloudTrail, AWS Config, GuardDuty, Security Hub, and KMS | ⏳ **Planned** | *tf-shared-services* |
| **3** | 🌐 Networking | Build hub-and-spoke VPCs, Transit Gateway, and VPC Endpoints (SSM, STS, ECR) | ⏳ **Planned** | *tf-networking* |
| **4** | ⚙️ Workloads | Deploy secure workloads (ECR, ECS/EKS, IAM Roles, Secrets Manager, WAF) | ⏳ **Planned** | *tf-workloads* |
| **5** | 🧱 Module Library | Create reusable Terraform modules (S3 Logs, KMS, GuardDuty, Security Hub, VPC) | ⏳ **Planned** | *tf-modules* |
| **6** | 🧮 Compliance Mapping | Automate NIST 800-171 / 800-53 mappings with AWS Config rules & Conformance Packs | ⏳ **Planned** | *compliance-mappings* |
| **7** | 📘 Labs & Documentation | Publish step-by-step labs, diagrams, and deployment tutorials | ⏳ **Planned** | *labs-cloud-security* |

**Legend:** ✅ Complete · 🧩 In Progress · ⏳ Planned

---

### 🛠️ Tools & Technologies
| Category | Tools / Services |
|-----------|------------------|
| **Cloud Platform** | AWS (Organizations, Control Tower, IAM, KMS, GuardDuty, Security Hub, Config) |
| **IaC & Automation** | Terraform 1.9+, Ansible 9.x, GitHub Actions (OIDC Auth), pre-commit |
| **Security Scanning** | tfsec, checkov, TFLint, Conftest (OPA) |
| **Compliance** | NIST 800-171 / 800-53 / CMMC mapping, AWS Config Conformance Packs |
| **Dev Environment** | Ubuntu (WSL), VS Code, AWS CLI v2, Python3 + boto3, Git |

---

### 🧠 About Me
I’m a **Cloud Security Engineer** passionate about building secure, automated, and compliant AWS environments.  
This portfolio reflects the **same practices used in enterprise and federal projects**—with an emphasis on governance, automation, and continuous compliance.

📍 Based in Georgia, USA  
📧 Contact: [LinkedIn](https://www.linkedin.com/in/wilbertomaldonado/) · [GitHub](https://github.com/eljefe3-maldonado)

---

<p align="center">
<sub>Built with ☁️ to demonstrate production-grade AWS Security & Compliance automation.</sub>
</p>
