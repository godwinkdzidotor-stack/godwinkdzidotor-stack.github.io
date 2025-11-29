---
layout: default
title: Home
---

<!-- =============================== -->
<!--   GODWIN K. DZIDOTOR, PhD — V3   -->
<!--        PORTFOLIO PRO EDIT       -->
<!-- =============================== -->

<div align="center" style="
  background: linear-gradient(135deg, #0d1117, #161b22);
  padding: 36px 18px;
  border-radius: 18px;
  margin-bottom: 28px;
  color: white;
">

  <h1 style="margin-bottom: 0.5rem; font-size: 2.7rem;">
    Godwin K. Dzidotor, PhD
  </h1>

  <h3 style="color:#58a6ff; margin-top: 0;">
    Cybersecurity Engineer • DevSecOps • Cloud Security • Network Security
  </h3>

  <p style="max-width: 680px; margin: 0 auto 18px; font-size: 1rem; color:#c9d1d9;">
    Building secure, automated, and resilient systems at the intersection of
    cybersecurity, cloud, and infrastructure engineering.
  </p>

  <!-- Badges -->
  <p>
    <img src="https://github.com/godwinkdzidotor-stack/devsecops-python-ci-cd/actions/workflows/devsecops.yml/badge.svg" alt="CI Badge" />
    <img src="https://img.shields.io/badge/Bandit-SAST%20Scan-green?logo=python&logoColor=white" alt="Bandit SAST" />
    <img src="https://img.shields.io/badge/Docker-Builds%20Clean-blue?logo=docker&logoColor=white" alt="Docker Build Clean" />
  </p>

  <!-- Navigation -->
  <p style="font-size: 1.1rem; margin-top: 10px;">
    <a href="index.md" style="color:#58a6ff; margin: 0 12px;">Home</a>
    <a href="projects.md" style="color:#58a6ff; margin: 0 12px;">Projects</a>
    <a href="skills.md" style="color:#58a6ff; margin: 0 12px;">Skills</a>
    <a href="about.md" style="color:#58a6ff; margin: 0 12px;">About</a>
    <a href="contact.md" style="color:#58a6ff; margin: 0 12px;">Contact</a>
  </p>

</div>


  <h1 style="color:#e6edf3;font-size:2.4rem;margin-bottom:0.3rem;">🔐 Godwin K. Dzidotor, PhD</h1>
  <h3 style="color:#c9d1d9;margin-top:0;">Cybersecurity Engineer • DevSecOps • Cloud Security • Network Security</h3>

  <p style="color:#8b949e;max-width:640px;margin:0 auto 16px;">
    Building secure, automated, and resilient systems at the intersection of cybersecurity, cloud, and infrastructure engineering.
  </p>

  <!-- Badges row -->
  <p>
    <img src="https://github.com/godwinkdzidotor-stack/devsecops-python-ci-cd/actions/workflows/devsecops.yml/badge.svg" alt="DevSecOps CI/CD" />
    <img src="https://img.shields.io/badge/Bandit-SAST%20Scan-green?logo=python&logoColor=white" alt="Bandit SAST" />
    <img src="https://img.shields.io/badge/Docker-Builds%20Clean-blue?logo=docker&logoColor=white" alt="Docker builds clean" />
  </p>

<!-- Quick nav -->
<p align="center">
  <a href="index.md"><b>Home</b></a> •
  <a href="projects.md">Projects</a> •
  <a href="skills.md">Skills</a> •
  <a href="about.md">About</a> •
  <a href="contact.md">Contact</a>
</p>

</div>

---

# 🔐 Portfolio Overview

This portfolio showcases **hands-on security engineering work** across:

- **Cloud Security (AWS)**
- **DevSecOps & CI/CD automation**
- **Static Application Security Testing (SAST) with Bandit**
- **Infrastructure-as-Code security (Terraform, Ansible)**
- **Python security tooling & network automation**

Each project includes **real code**, **pipelines**, **security outputs**, and **documentation**—demonstrating how I think about **secure design, implementation, and operations**.

---

# 🚀 Featured Security Projects

> ⚠️ All projects are built for **lab, education, and portfolio use** only — not for unauthorized testing.

<br>

## 🧩 Cloud & Infrastructure Security

<table>
  <tr>
    <td width="50%" valign="top">

### 🟠 Secure AWS VPC with Terraform

A production-style AWS VPC with:
- Public & private subnets
- NAT gateway & route tables
- Security group and NACL hardening
- Baseline network segmentation

**Stack:** Terraform • AWS • VPC Security  

🔗 **Repo:**  
https://github.com/godwinkdzidotor-stack/aws-secure-vpc-terraform

  </td>
  <td width="50%" valign="top">

### 🟠 Linux Security Hardening with Ansible

Automated OS-level hardening:
- SSH lockdown (no root login, key-based access)
- Firewall baseline rules
- Password policy + PAM controls
- Service & package tightening

**Stack:** Ansible • Linux • CIS-inspired controls  

🔗 **Repo:**  
https://github.com/godwinkdzidotor-stack/ansible-security-hardening

  </td>
  </tr>
</table>

---

## 🧪 Security Automation & DevSecOps

<table>
  <tr>
    <td width="50%" valign="top">

### 🟢 Python Network Security Automation

Two core tools:
- **Firewall auditor:** flags `src=any`, `dst=any`, `0.0.0.0/0`, and overly broad rules  
- **Subnet scanner:** ICMP reachability scan across a CIDR

Useful for:
- Quick posture checks
- Lab environments
- Teaching basic network security automation

**Stack:** Python • Networking • CSV parsing  

🔗 **Repo:**  
https://github.com/godwinkdzidotor-stack/python-network-automation

  </td>
  <td width="50%" valign="top">

### 🟢 DevSecOps Python CI/CD Pipeline

A full CI/CD pipeline that runs on every push:

1. ✅ **Syntax check** — `python -m py_compile`
2. 🛡 **Bandit SAST scan** — recursive, with report artifact
3. 🐳 **Docker build** — validates containerization
4. 📎 **Artifacts** — Bandit report uploaded for review

Includes:
- Status badges
- Pipeline screenshots
- Clear README documentation

**Stack:** GitHub Actions • Bandit • Docker  

🔗 **Repo:**  
https://github.com/godwinkdzidotor-stack/devsecops-python-ci-cd

  </td>
  </tr>
</table>

---

# 🧰 Skills & Technologies

### 🛡 Security Engineering
- DevSecOps pipelines & automation  
- Static analysis (Bandit)  
- Network security & segmentation  
- Firewall rule review & auditing  
- IAM, least privilege, and Zero Trust-aligned thinking  
- OS & infrastructure hardening  

### ☁️ Cloud, Infra & Automation
- AWS (VPC, IAM, networking)  
- Terraform (IaC)  
- Ansible (configuration management & hardening)  
- Docker & container security basics  
- GitHub Actions (CI/CD)  
- Linux administration  

### 🧑‍💻 Programming & Scripting
- Python (security tooling, automation)  
- Bash  
- YAML (CI/CD pipelines, configs)  
- Git / GitHub workflows  

---

# 👨‍💼 About Me

I am a **Cybersecurity Engineer** with a background that blends:

- **Cloud & infrastructure engineering**
- **DevSecOps & automation**
- **Network defense & secure design**
- **Research, mentoring, and leadership**

I enjoy:
- Turning security principles into **repeatable automation**
- Designing **secure-by-default** environments
- Explaining complex systems in a way that’s clear and practical
- Working on teams that care about both **mission** and **resilience**

If you’re looking for someone who can **design, build, and secure systems**—and explain the *why* behind the decisions—I’d love to connect.

---

# 📫 Contact

- 📧 **Email:** godwink.dzidotor@gmail.com  
- 🔗 **LinkedIn:** https://www.linkedin.com/in/godwink-dzidotor-phd  
- 🌐 **GitHub:** https://github.com/godwinkdzidotor-stack  

---

<div align="center" style="margin-top:24px;color:#8b949e;">
  <em>🚀 This site is automatically deployed using GitHub Pages.</em>
</div>
