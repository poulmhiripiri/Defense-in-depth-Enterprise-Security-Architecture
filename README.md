# Defense-in-Depth Enterprise Security Architecture

## Portfolio project by Poul Mhiripiri

This GitHub submission demonstrates how I would design, operate, and govern a **defense-in-depth security architecture** for a medium-to-large enterprise such as a bank, ISP, charity, or multi-branch organisation.

The project is written from the perspective of an **AVP / IT Networks and Infrastructure Support Manager** with hands-on experience across enterprise networking, perimeter security, internal segmentation, identity, endpoint protection, vulnerability management, monitoring, backup, and incident response.

> **Purpose:** Give recruiters and hiring managers evidence that I can translate infrastructure and security experience into a structured, risk-based architecture and operational model.

---

## What this project demonstrates

- Enterprise security architecture thinking, not just isolated technical tasks
- Defense-in-depth across network, endpoint, identity, data, cloud, monitoring, and recovery layers
- Practical controls that map to recognised frameworks such as **NIST CSF 2.0** and **CIS Controls v8**
- Experience delivering infrastructure and security projects in regulated and high-availability environments
- Ability to document executive rationale, technical design, operational controls, risk, and incident response

---

## Scenario

A growing organisation has multiple branches, two data centres, remote users, cloud workloads, Microsoft 365 services, third-party integrations, and sensitive customer data. The organisation requires a layered security model to reduce the likelihood and impact of compromise.

This project proposes a target architecture where no single security control is relied upon alone. Every layer assumes that another layer may fail.

---

## Architecture layers

| Layer | Control focus | Example technologies / capabilities |
|---|---|---|
| Governance | Policies, risk ownership, audit tracking, change control | Risk register, security committee reporting, exception management |
| Perimeter | Internet edge protection | Next-generation firewall, IPS, geo/IP filtering, VPN, DMZ |
| Network | Internal segmentation and secure routing | VLANs, VRFs, ACLs, firewall zones, secure routing, HA design |
| Identity | Least privilege and access control | MFA, RBAC, conditional access, privileged access review |
| Endpoint | Malware and hardening controls | EDR/AV, patching, device control, secure build baselines |
| Email/Web | User-facing threat prevention | Email security gateway, anti-phishing, web filtering, sandboxing |
| Vulnerability | Exposure management | Authenticated scanning, patch prioritisation, remediation tracking |
| Monitoring | Detection and response | SIEM, central logging, correlation rules, alert triage |
| Data | Confidentiality and integrity | Encryption, hashing/tokenisation, backup encryption, DLP principles |
| Recovery | Resilience after compromise | Immutable/offline backup, restore testing, DR exercises |

---

## Repository structure

```text
defense-in-depth-enterprise-security-architecture/
├── README.md
├── docs/
│   ├── 01-executive-summary.md
│   ├── 02-high-level-architecture.md
│   ├── 03-defense-in-depth-layers.md
│   ├── 04-project-evidence-and-achievements.md
│   ├── 05-control-mapping-nist-csf-cis.md
│   ├── 06-incident-response-playbook.md
│   ├── 07-risk-register.md
│   ├── 08-implementation-roadmap.md
│   └── 09-recruiter-talk-track.md
├── diagrams/
│   └── defense-in-depth-architecture.mmd
├── configs/
│   ├── firewall-policy-sample.csv
│   ├── network-hardening-baseline.md
│   ├── siem-detection-use-cases.md
│   └── backup-and-recovery-runbook.md
└── .github/workflows/
    └── markdown-quality-check.yml
```

---

## Key achievements represented in this project

The examples below are anonymised and written as portfolio evidence rather than confidential employer documentation.

- Supported secure infrastructure for a multi-branch financial services environment with high availability expectations
- Worked with enterprise firewall platforms including Check Point, Cisco ASA/Firepower/FTD, and FortiGate
- Supported internal segmentation, VPN connectivity, DMZ design, and secure third-party integrations
- Participated in vulnerability management, audit issue closure, endpoint protection, SIEM/logging, and security hardening
- Delivered ISP/core networking projects involving BGP, MPLS, upstream providers, peering, CDN optimisation, and availability improvements
- Built cloud/security labs using AWS, Wazuh, Qualys/Nessus concepts, endpoint controls, and GitHub documentation

---

## How to use this repository in interviews

A recruiter or hiring manager can review this project to understand:

1. How I structure security architecture from governance to recovery
2. How I think about practical risk reduction, not only tool deployment
3. How my infrastructure background supports cybersecurity engineering and network security roles
4. How I would communicate security posture to technical and non-technical stakeholders

Recommended interview explanation:

> “This repository shows how I approach enterprise defense-in-depth. It combines my network and infrastructure management background with cybersecurity controls such as segmentation, endpoint protection, vulnerability management, SIEM detection, identity controls, and recovery planning. I created it to show how I can take real operational experience and express it as a structured security architecture recruiters can review.”

---

## Framework references

- NIST Cybersecurity Framework 2.0: Govern, Identify, Protect, Detect, Respond, Recover
- CIS Critical Security Controls v8: prioritised safeguards and Implementation Groups

---

## Disclaimer

This repository is a portfolio project. It does not contain confidential employer information, production firewall rules, real IP addresses, customer data, secrets, or proprietary diagrams.
