<h1 align="center">Security, Compliance &amp; Cloud Platform Engineering</h1>
<h3 align="center">Wilberto Maldonado</h3>

<p align="center">
  <em>CISSP · AWS Certified · Replacing manual GRC work with code-defined workflows, and building the secure cloud platforms underneath it</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/FedRAMP-Authorization%20%26%20ConMon-1B4F72" />
  <img src="https://img.shields.io/badge/Compliance-as--Code-2E7D32" />
  <img src="https://img.shields.io/badge/Python-Automation-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-Cloud%20Architecture-orange?logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-IaC-7B42BC?logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Packer-Image%20Factory-02A8EF?logo=packer&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-CI/CD-2088FF?logo=github-actions&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CISSP-Certified-003087?logo=isc2&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-Security%20Specialty-FF9900?logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-Solutions%20Architect%20Associate-FF9900?logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/CompTIA-CASP%2B%20%2F%20SecurityX-E31837?logo=comptia&logoColor=white" />
</p>

<p align="center">
  <strong>Open to Security Compliance Engineering, GRC Automation, Security Risk Engineering, Cloud Security, and Platform Engineering roles</strong><br/>
  <a href="https://www.linkedin.com/in/wilbertomaldonado/">LinkedIn</a> · Georgia, USA
</p>

---

### Currently

Building container and EKS deployment for CCIP, and extending FedRAMP CR26 coverage tooling.

<sub><em>Updated monthly.</em></sub>

---

### Overview

I work at the seam between **security, compliance, and engineering**: I evaluate control implementations, cloud architectures, and integration patterns for risk, then build the automation that validates them instead of documenting them by hand.

Twenty-four years across federal and commercial cloud security and Army cyber operations. Day to day that means **FedRAMP authorization and continuous monitoring**, security assessments, and the Python automation that makes both repeatable.

Two focus areas:

- **Compliance and risk as code** — automated evidence collection, control validation, and compliance reporting, so that "is this control actually working?" is a question a pipeline answers rather than a person asserts
- **Secure cloud platforms** — the AWS foundations, image pipelines, and IaC guardrails that make those controls true in the first place

Frameworks I work in daily: FedRAMP, NIST 800-53 Rev. 5, SOC 2, NIST CSF, NIST 800-171, CMMC.

---

### Public Engineering Work

| Focus | Repository | What It Demonstrates |
|------|-----------|----------------------|
| **AWS Image Factory** | [`aws-golden-image-factory`](https://github.com/eljefe3-maldonado/aws-golden-image-factory) | Immutable, hardened AMI pipeline using Packer and Ansible, with CI validation, OIDC authentication, and versioned outputs — no static credentials |
| **Cloud Infrastructure as Code** | [`infrastructure`](https://github.com/eljefe3-maldonado/infrastructure) | Terraform for secure AWS foundations: multi-account governance patterns, least-privilege IAM, guardrails, and repeatable deployment |

Repositories are structured the way I'd want to inherit them: clean layouts, documented architecture decisions, repeatable automation, and security embedded rather than appended.

---

### In Progress

| Focus | Repository | Status |
|------|-----------|--------|
| **Kubernetes & Cloud-Native** | [`kubernetes-training`](https://github.com/eljefe3-maldonado/kubernetes-training) | Building out container and EKS work — pods, deployments, RBAC, network policy, and admission control — as the deployment path for CCIP |

---

### Selected Private Work

**CCIP — Continuous Compliance Intelligence Platform** · Founder & Lead Architect

An evidence-driven continuous-compliance platform in Python (FastAPI) that validates NIST 800-53 technical requirements through automated cloud evidence collection, content-addressed evidence packages, and deterministic control validation. Includes a spec-first CLI verifier returning a four-state verdict (pass / fail / indeterminate / malformed), enabling independent, offline-reproducible assessment rather than self-attested screenshots. Also includes FedRAMP CR26 ruleset analysis with coverage tooling that maps requirements to machine-checkable assertions — policy-as-code applied to an evolving standard.

*Private repository — walkthrough available on request.*

---

### Toolchain

| Category | Tools & Concepts |
|--------|------------------|
| **Compliance & GRC Engineering** | FedRAMP authorization & continuous monitoring, automated control testing, evidence collection & validation, policy-as-code, OSCAL, POA&M management, security assessments & audits |
| **Risk & Control Frameworks** | FedRAMP, NIST 800-53 Rev. 5, SOC 2, NIST CSF, NIST 800-171, NIST RMF, CMMC Level 2 |
| **Automation & Engineering** | Python, FastAPI, agentic coding tooling (Claude Code, Cursor), REST API integrations, BI dashboards & reporting |
| **Cloud Platform** | AWS (IAM, Organizations, Control Tower, SCPs, Config, GuardDuty, Security Hub, CloudTrail, KMS), Azure incl. Azure Government, GCP |
| **Infrastructure as Code** | Terraform, CloudFormation, Ansible, Packer |
| **CI/CD & DevSecOps** | GitHub Actions, OIDC authentication, pipeline validation, security gates, policy-as-code, Checkov, tfsec |
| **Security Tooling** | Tenable/Nessus, Splunk, ELK, ServiceNow, CSPM platforms, STIG/SCAP |
| **Scripting & Ops** | Python, Bash, PowerShell |

---

### How I Work

- **Architecture before implementation** — design decisions documented, not improvised
- **Automation over assertion** — a control that can't be validated automatically isn't really evidenced
- **If it runs twice, it should be a pipeline**
- **Secure defaults without slowing delivery** — DevSecOps as a practice, not a checkpoint
- **AI as engineering discipline** — I set the architecture and guardrails, the model does the typing, and I review what comes back
- **Operational clarity** — infrastructure others can understand, maintain, and extend

---

### Certifications

| Certification | Issuer |
|---|---|
| **CISSP** — Certified Information Systems Security Professional | ISC² |
| **AWS Certified Security – Specialty** | Amazon Web Services |
| **AWS Certified Solutions Architect – Associate** | Amazon Web Services |
| **CASP+ / SecurityX** | CompTIA |
| **CEH** — Certified Ethical Hacker | EC-Council |
| **Security+** | CompTIA |
