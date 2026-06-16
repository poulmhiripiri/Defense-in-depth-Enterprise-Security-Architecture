# Cybersecurity Architecture for SMEs

## Purpose

This document adds an SME-focused lens to the broader enterprise defense-in-depth design. It recognises that smaller and medium-sized organisations need layered security too, even if their budgets and teams are more constrained.

## Core SME security domains

### External access and internet exposure

- Secure remote access using VPN
- Protection of internet-facing services
- Segregation of partner/vendor access
- Monitoring of inbound and outbound traffic

### Perimeter controls

- Next-generation firewall or equivalent perimeter firewall
- Network IDS / IPS capability
- Web application or internet edge filtering where appropriate
- Anti-malware protection at the boundary

### Server and application infrastructure

- Internal firewalls and segmentation
- Host IDS on critical servers
- Separation of application and database services
- Logging for system, security, and application events

### End-user protection

- Managed endpoint protection
- Disk encryption
- Secure desktop configuration
- Privilege control and patching
- Security awareness for users

### Supporting controls

- NAC or equivalent access control
- Wireless security controls
- Traffic visibility such as NetFlow or comparable telemetry
- Backup and restore validation

## Why it matters

SMEs are often attractive targets because attackers assume controls may be weaker. A practical architecture helps SMEs implement proportionate security that protects the business without creating unrealistic operational burden.

## Link to the author’s experience

The SME architecture is supported by experience across banking, ISP/core networking, and hands-on cybersecurity projects, including firewalls, VPNs, segmentation, endpoint hardening, logging, vulnerability management, and resilience planning.
