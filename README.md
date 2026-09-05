<h1 align="center">Security Risk Engineering &amp; Cloud Platform Architecture</h1>
<h3 align="center">Wilberto Maldonado</h3>

<p align="center">
  <em>CISSP · AWS Certified · Replacing manual GRC work with code-defined workflows, and building the secure cloud platforms underneath it</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Automation-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Compliance-as--Code-2E7D32" />
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
  <strong>Open to Security Risk Engineering, GRC Automation, Cloud Security, and Platform Engineering roles</strong><br/>
  <a href="https://www.linkedin.com/in/wilbertomaldonado/">LinkedIn</a> · Georgia, USA
</p>

---

### Overview

I work at the seam between **security risk management and engineering**: I evaluate control implementations, cloud architectures, and third-party integration patterns for risk, then build the automation that validates them instead of documenting them by hand.

Twenty-four years across cloud security and Army cyber operations, currently focused on two things:

- **Compliance and risk as code** — Python automation for evidence collection, control validation, and risk reporting, so that "is this control actually working?" is a question a pipeline answers rather than a person asserts
- **Secure cloud platforms** — the AWS foundations, image pipelines, and IaC guardrails that make those controls true in the first place

Frameworks I work in daily: NIST CSF, NIST 800-53 Rev. 5, SOC 2, NIST 800-171, FedRAMP.

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

An evidence-driven continuous-compliance platform in Python (FastAPI) that validates NIST 800-53 technical requirements through automated cloud evidence collection, content-addressed evidence packages, and deterministic control validation. Includes a spec-first CLI verifier returning a four-state verdict (pass / fail / indeterminate / malformed), enabling independent, offline-reproducible assessment rather than self-attested screenshots. Also includes FedRAMP CR26 ruleset analysis with coverage tooling that maps requirements to machine-checkable assertions.

*Private repository — walkthrough available on request.*

---

### Toolchain

| Category | Tools & Concepts |
|--------|------------------|
| **Automation & GRC Engineering** | Python, FastAPI, agentic coding tooling (Claude Code, Cursor), REST API integrations, BI dashboards & reporting, evidence collection, control validation |
| **Risk & Control Frameworks** | NIST CSF, NIST 800-53 Rev. 5, SOC 2, NIST 800-171, NIST RMF, FedRAMP, OSCAL, CMMC Level 2 |
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
