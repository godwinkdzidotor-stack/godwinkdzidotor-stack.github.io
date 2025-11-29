---
layout: default
title: Projects
permalink: /projects
---


<!-- ============================= -->
<!--    PROJECTS PAGE — PRO MAX   -->
<!-- ============================= -->

<div align="center" style="background:#0d1117;padding:24px 16px;border-radius:16px;margin-bottom:24px;">
  <h2 style="color:#e6edf3;margin:0;">🔐 Security Engineering Projects</h2>
  <p style="color:#9ca3af;margin:8px 0 0;">
    Real-world style labs that showcase how I design, secure, and automate systems.
  </p>
</div>

<!-- Navigation -->
<p align="center" style="font-size:0.95rem;">
  <a href="index.md" style="margin:0 12px;">Home</a> •
  <a href="projects.md" style="margin:0 12px;font-weight:bold;">Projects</a> •
  <a href="skills.md" style="margin:0 12px;">Skills</a> •
  <a href="about.md" style="margin:0 12px;">About</a> •
  <a href="contact.md" style="margin:0 12px;">Contact</a>
</p>

---

## ☁️ Cloud & Infrastructure Security

### 1. Secure AWS VPC with Terraform

A production-inspired AWS VPC build that focuses on **segmentation, least privilege, and guardrails**.

**Highlights**

- Public & private subnets with controlled ingress
- Internet/NAT gateway separation and routing
- Security group and NACL rules hardened around least privilege
- Baseline network segmentation for future workloads and services

**Tech Stack**

- Terraform • AWS VPC • IAM • Security Groups / NACLs

**Repo**

🔗 <https://github.com/godwinkdzidotor-stack/aws-secure-vpc-terraform>

---

### 2. Linux Security Hardening with Ansible

An opinionated baseline for **server hardening**, designed as a reusable Ansible role/playbook.

**What it hardens**

- SSH configuration (no root login, stronger auth posture)
- Firewall rules (ingress/egress filtering)
- Password policy + PAM controls
- Service, package, and logging baseline

**Why it matters**

- Shows how I convert **checklists** (CIS / STIG-style controls) into **idempotent automation**.
- Easy to plug into CI/CD or golden image workflows.

**Tech Stack**

- Ansible • Linux • CIS-inspired controls

**Repo**

🔗 <https://github.com/godwinkdzidotor-stack/ansible-security-hardening>

---

## 🤖 Security Automation & DevSecOps

### 3. Python Network Security Automation

A small but powerful toolkit for **rapid posture checks** and training.

**Tools**

- **`firewall_audit.py`**  
  - Reads firewall CSVs and flags:
    - `src = any`, `dst = any`
    - `0.0.0.0/0` or similarly wide allows
  - Great for catching “allow-the-world” misconfigurations.

- **`subnet_scan.py`**  
  - ICMP reachability scan across a CIDR
  - One ping per host, simple output for quick triage

**Used for**

- Teaching basic security automation
- Quick network and firewall sanity checks
- Building intuition around what “too permissive” looks like

**Tech Stack**

- Python • Networking • CSV parsing

**Repo**

🔗 <https://github.com/godwinkdzidotor-stack/python-network-automation>

---

### 4. DevSecOps Python CI/CD Pipeline

A **full DevSecOps workflow** that ties everything together in CI:

**Pipeline stages**

1. ✅ Syntax check — `python -m py_compile`  
2. ✅ Bandit SAST scan (recursive, with artifact report)  
3. ✅ Unit tests with pytest + coverage  
4. ✅ Docker image build (containerization check)  
5. ✅ Artifacts — Bandit report uploaded for review  

**What this demonstrates**

- How I integrate **security tools directly into CI**  
- How to keep pipelines **developer-friendly** with clear logs and artifacts  
- Reproducible builds via Docker

**Tech Stack**

- GitHub Actions • Bandit • Docker • Pytest

**Repo**

🔗 <https://github.com/godwinkdzidotor-stack/devsecops-python-ci-cd>

---

## 🧪 Future Lab Ideas

I plan to expand this portfolio with:

- Container image scanning (Trivy/Snyk) integrated into CI/CD
- Dependency-level risk checks for Python and container builds
- Additional AWS security patterns (WAF, GuardDuty baselines, logging pipelines)

Stay tuned — and feel free to reach out if you’d like to see a particular kind of lab.
