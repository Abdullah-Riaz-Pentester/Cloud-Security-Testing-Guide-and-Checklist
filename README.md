## ☁️ Cloud Security Testing Guide (CSTG)

A practitioner-focused cloud security testing guide structured across 12 phases,
covering the complete attack lifecycle from passive reconnaissance through to
advanced identity attacks, container escapes, and compliance verification.

Built for use by penetration testers, cloud security engineers, and red teamers
conducting Cloud VAPT engagements across AWS, Microsoft Azure, Google Cloud Platform,
Kubernetes, Docker, and Serverless environments.

---

### 📋 What's Covered

| Phase | Topic |
|-------|-------|
| Phase 1  | Cloud Reconnaissance & External Enumeration |
| Phase 2  | Cloud IAM Enumeration & Privilege Escalation |
| Phase 3  | Compute, Container & Network Security Testing |
| Phase 4  | Cloud Storage Security (S3, Blob, GCS) |
| Phase 5  | SSRF & Metadata Service Credential Theft |
| Phase 6  | AWS / Azure / GCP Platform-Specific Attacks |
| Phase 7  | Advanced Identity Attacks (Golden SAML, MitC, OIDC) |
| Phase 8  | Serverless & Lambda Security Testing |
| Phase 9  | Logging, Monitoring & Detection Verification |
| Phase 10 | Compliance, Hardening & Encryption Verification |
| Phase 11 | Network Security & VPC Assessment |
| Phase 12 | Cloud Incident Response & Evidence Preservation |

---

### 🛠️ Tools Referenced

**Reconnaissance:** TruffleHog · GitLeaks · subfinder · amass · nuclei · Shodan · S3Scanner  
**IAM & Identity:** AWS CLI · PMapper · Pacu · AzureGraph · ROADtools · ADFSpoof  
**Compute & Containers:** kubectl · kube-hunter · kube-bench · docker CLI · Trivy · Falco  
**Multi-Cloud Assessment:** Prowler · ScoutSuite · GCP Scanner  
**Exploitation:** Burp Suite · Metasploit · AWS CLI · gcloud CLI · Azure CLI  
**Serverless:** pip-audit · npm audit · Snyk · Trivy  

---

### 📐 Format

Each activity in the guide follows a consistent structure:

- **Test ID** — Unique reference identifier (e.g., CSEC-IAM-002)
- **Objective** — What the test proves
- **Pre-conditions** — What access or setup is required before testing
- **Time-Saving Analysis** — What to do immediately if the vulnerability is confirmed
- **Method** — Step-by-step numbered commands with full flag explanations
- **Successful Response** — What output confirms a vulnerability
- **Unsuccessful Response** — What output confirms a secure configuration

---

### 🎯 Who This Is For

- Penetration testers performing Cloud VAPT engagements
- Cloud security engineers conducting internal security assessments
- Red teams targeting AWS, Azure, and GCP environments
- CEH v13 candidates studying Module 19: Cloud Computing
- Security architects validating cloud hardening controls

---

### ⚠️ Disclaimer

This guide is intended for authorised security testing only. All techniques
described must only be used against environments you own or have explicit
written permission to test. Unauthorised use against any cloud environment
is illegal and unethical.

---

### 📎 Companion File

Use this guide alongside the **Cloud Security Testing Checklist** (.xlsx) for
structured tracking of test progress, findings, and pass/fail status across
all phases of your engagement.
