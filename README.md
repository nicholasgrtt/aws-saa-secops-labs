# AWS SAA-C03 + Cloud SecOps Labs (Portfolio)

Hands-on labs and incident-style writeups focused on **AWS Solutions Architect Associate (SAA-C03)** fundamentals and **Cloud SecOps** skills (IAM, VPC, CloudTrail, CloudWatch, S3 security).  
---

## What you'll find here

- **Real labs** (built in AWS) with **cleanup steps** to avoid unexpected costs
- **Incident-style writeups**: problem → evidence → hypothesis → tests → root cause → fix → prevention
- **Security-first mindset**: least privilege, logging, guardrails, secure defaults
- Notes aligned with the **SAA-C03** exam domains

---

## Repo structure

- `00-account-setup/` — MFA, budgets, IAM baseline, CLI setup
- `01-networking-foundations/` — DNS/HTTP basics, troubleshooting checklists
- `02-linux-troubleshooting/` — SSH, services, logs, network tools
- `03-aws-core/` — IAM, EC2, EBS, S3, core services
- `04-vpc-and-security/` — VPC, subnets, routing, SG vs NACL, access patterns
- `05-logging-investigation/` — CloudTrail/CloudWatch investigations + timelines
- `06-s3-kms-data-protection/` — S3 security, encryption, KMS basics
- `07-projects/` — end-to-end mini-projects and runbooks

---

## Case writeup standard

Each case follows this template:

1. **Scenario / Problem**
2. **Impact**
3. **Evidence collected** (logs, screenshots, CLI output — no secrets)
4. **Hypotheses**
5. **Tests performed**
6. **Root cause**
7. **Fix**
8. **Prevention / Guardrails**
9. **Cleanup checklist** (resources terminated to avoid charges)

---

## Tools used

- AWS Console + AWS CLI
- Git + GitHub
- macOS terminal
- Basic Linux troubleshooting commands (ssh, curl, dig, journalctl, systemctl, ip, ss)

---

## Safety / privacy notes

Never commit:
- Access keys / secret keys
- Full account identifiers (mask if needed)
- Private IP ranges tied to real infrastructure
- Any customer data


---

## Current focus (first milestones)

- ✅ Account hardening (root MFA, IAM user + MFA, budgets/alerts)
- ✅ Networking fundamentals (DNS/HTTP + troubleshooting)
- ✅ Linux basics (logs, services, permissions)
- ✅ AWS core (IAM, VPC, EC2, S3)

---

## Index of cases

> I keep an updated list of completed cases here.

- `00-account-setup/`
  - `case-00-account-hardening.md`
- `04-vpc-and-security/`
  - `case-01-ec2-ssh-troubleshooting.md`

---

## Contact

If you'd like to discuss any lab or troubleshooting approach, open an issue in this repo.
