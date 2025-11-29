---
layout: default
title: ""
permalink: /
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
    <a href="/" style="color:#58a6ff; margin: 0 12px;">Home</a>
    <a href="/projects" style="color:#58a6ff; margin: 0 12px;">Projects</a>
    <a href="/skills" style="color:#58a6ff; margin: 0 12px;">Skills</a>
    <a href="/about" style="color:#58a6ff; margin: 0 12px;">About</a>
    <a href="/contact" style="color:#58a6ff; margin: 0 12px;">Contact</a>
  </p>

  <!-- LinkedIn (glow pill) -->
  <a href="https://www.linkedin.com/in/godwin-k-dzidotor-phd-36096a234/" 
     target="_blank" 
     rel="noopener noreferrer"
     class="glow-btn glow-linkedin"
     style="margin-top:10px;">
     Connect on LinkedIn
  </a>

  <!-- 🔗 Portfolio microsites (glow pills) -->
  <div style="margin-top: 18px;">

    <a href="https://godwinkdzidotor-stack.github.io/Network-Engineering-Projects/"
       target="_blank" rel="noopener noreferrer"
       class="glow-btn glow-blue"
       style="margin:6px;">
       🌐 Network Engineering Projects
    </a>

    <a href="https://godwinkdzidotor-stack.github.io/Risk-Management-Framework-Portfolio/"
       target="_blank" rel="noopener noreferrer"
       class="glow-btn glow-gray"
       style="margin:6px;">
       🛡️ RMF Portfolio
    </a>

  </div>

  <!-- Additional repo microsites (glow pills) -->
  <div style="margin-top: 8px;">

    <a href="https://godwinkdzidotor-stack.github.io/devsecops-python-ci-cd/"
       target="_blank" rel="noopener noreferrer"
       class="glow-btn glow-purple"
       style="margin:6px;">
       ⚙️ DevSecOps Python CI/CD
    </a>

    <a href="https://godwinkdzidotor-stack.github.io/python-network-automation/"
       target="_blank" rel="noopener noreferrer"
       class="glow-btn glow-indigo"
       style="margin:6px;">
       🧪 Python Network Automation
    </a>

    <a href="https://godwinkdzidotor-stack.github.io/ansible-security-hardening/"
       target="_blank" rel="noopener noreferrer"
       class="glow-btn glow-orange"
       style="margin:6px;">
       🛠️ Ansible Security Hardening
    </a>

    <a href="https://godwinkdzidotor-stack.github.io/aws-secure-vpc-terraform/"
       target="_blank" rel="noopener noreferrer"
       class="glow-btn glow-green"
       style="margin:6px;">
       ☁️ AWS Secure VPC (Terraform)
    </a>

  </div>

</div>



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

<h3>🟠 Secure AWS VPC with Terraform</h3>

<p>
A production-style AWS VPC with:
<ul>
  <li>Public & private subnets</li>
  <li>NAT gateway & route tables</li>
  <li>Security group and NACL hardening</li>
  <li>Baseline network segmentation</li>
</ul>

<strong>Stack:</strong> Terraform • AWS • VPC Security<br>
<strong>Repo:</strong>
<a href="https://github.com/godwinkdzidotor-stack/aws-secure-vpc-terraform"
   target="_blank" 
   rel="noopener noreferrer">
   github.com/godwinkdzidotor-stack/aws-secure-vpc-terraform
</a>
</p>

    </td>
    <td width="50%" valign="top">

<h3>🟠 Linux Security Hardening with Ansible</h3>

<p>
Automated OS-level hardening:
<ul>
  <li>SSH lockdown (no root login, key-based access)</li>
  <li>Firewall baseline rules</li>
  <li>Password policy + PAM controls</li>
  <li>Service & package tightening</li>
</ul>

<strong>Stack:</strong> Ansible • Linux • CIS-inspired controls<br>
<strong>Repo:</strong>
<a href="https://github.com/godwinkdzidotor-stack/ansible-security-hardening" 
   target="_blank" 
   rel="noopener noreferrer">
   github.com/godwinkdzidotor-stack/ansible-security-hardening
</a>
</p>

    </td>
  </tr>
</table>

---

## 🧪 Security Automation & DevSecOps

<table>
  <tr>
    <td width="50%" valign="top">

<h3>🟢 Python Network Security Automation</h3>

<p>
Two core tools:
<ul>
  <li><strong>Firewall auditor:</strong> flags <code>src=any</code>, <code>dst=any</code>, <code>0.0.0.0/0</code>, overly broad rules</li>
  <li><strong>Subnet scanner:</strong> ICMP reachability scan across a CIDR</li>
</ul>

Useful for:
<ul>
  <li>Quick posture checks</li>
  <li>Lab environments</li>
  <li>Teaching basic network security automation</li>
</ul>

<strong>Stack:</strong> Python • Networking • CSV parsing<br>
<strong>Repo:</strong>
<a href="https://github.com/godwinkdzidotor-stack/python-network-automation"
   target="_blank" 
   rel="noopener noreferrer">
   github.com/godwinkdzidotor-stack/python-network-automation
</a>
</p>

    </td>
    <td width="50%" valign="top">

<h3>🟢 DevSecOps Python CI/CD Pipeline</h3>

<p>
A full CI/CD pipeline runs on every push:
<ol>
  <li><strong>Syntax check</strong> — <code>python -m py_compile</code></li>
  <li><strong>Bandit SAST scan</strong> — recursive, with artifact</li>
  <li><strong>Docker build</strong> — validates containerization</li>
  <li><strong>Artifacts</strong> — Bandit HTML report uploaded</li>
</ol>

Includes:
<ul>
  <li>Status badges</li>
  <li>Pipeline screenshots</li>
  <li>Clear documentation</li>
</ul>

<strong>Stack:</strong> GitHub Actions • Bandit • Docker<br>
<strong>Repo:</strong>
<a href="https://github.com/godwinkdzidotor-stack/devsecops-python-ci-cd"
   target="_blank" 
   rel="noopener noreferrer">
   github.com/godwinkdzidotor-stack/devsecops-python-ci-cd
</a>
</p>

    </td>
  </tr>
</table>
