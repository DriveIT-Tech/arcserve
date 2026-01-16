# Combined CERT-In + DPDP Act Compliance Mapping – Arcserve Portfolio

## Regulatory Scope
- CERT-In Directions (Incident reporting, resilience, evidence, recovery)
- Digital Personal Data Protection (DPDP) Act, India (Security safeguards, breach response, accountability)

---

## 1. Cyber Incident Preparedness & Recovery

| Regulatory Requirement (CERT-In + DPDP) | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve Cyber Resilient Storage |
|----------------------------------------|-------------|--------------|-----------------|----------------------------------|
| Ability to recover after cyber incidents | Yes | Partial | Yes | Yes |
| Support rapid service restoration | Yes | Yes | Limited | Yes |
| Clean recovery after ransomware | Medium | Low | Low | Very High |
| Isolation of compromised environments | Limited | No | No | Yes |
| Assume-breach recovery design | Partial | No | No | Yes |

**Regulatory Intent:**  
Both CERT-In and DPDP expect recovery plans to work **after compromise**, not just system failure.

---

## 2. Ransomware Protection & Data Integrity

| Regulatory Requirement | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve CRS |
|------------------------|-------------|--------------|-----------------|--------------|
| Protection against data tampering | Medium | Low | Low | Very High |
| Immutable retention of backups | Optional | No | No | Native |
| Prevent unauthorised data alteration | Medium | Low | Low | Very High |
| Detect abnormal data modification | Basic | No | No | Advanced |
| Last line of defence against ransomware | No | No | No | Yes |

**Key Insight:**  
Replication technologies **replicate corruption and ransomware** — immutability is mandatory for regulatory resilience.

---

## 3. Business Continuity & Availability

| Regulatory Requirement | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve CRS |
|------------------------|-------------|--------------|-----------------|--------------|
| Minimise downtime of critical services | Yes | Yes (best) | Limited | Indirect |
| Meet aggressive RTO / RPO targets | Yes | Yes (near-zero) | Limited | Yes (post-incident) |
| Automated failover | Limited | Yes | No | No |
| Protection of critical infrastructure | Yes | Yes | Yes | Yes |

**Clarification:**  
Availability ≠ recoverability. CERT-In explicitly differentiates the two.

---

## 4. Evidence Preservation, Logs & Forensics

| Regulatory Requirement | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve CRS |
|------------------------|-------------|--------------|-----------------|--------------|
| Preserve data for investigation | Limited | No | Yes | Yes |
| Prevent post-incident data tampering | Medium | Low | Low | Very High |
| Support forensic analysis | Limited | No | Yes | Yes |
| Retain evidence securely for mandated duration | Yes | Limited | Yes | Yes |

**Why this matters:**  
CERT-In investigations and DPDP inquiries both require **unaltered evidence**.

---

## 5. Retention, Storage Limitation & Deletion

| Regulatory Requirement | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve CRS |
|------------------------|-------------|--------------|-----------------|--------------|
| Policy-driven retention control | Yes | No | Yes | Yes |
| Enforce storage limitation (DPDP) | Yes | No | Yes | Yes |
| Prevent over-retention of personal data | Yes | No | Yes | Yes |
| Secure deletion after retention expiry | Yes | No | Yes | Policy-driven |

---

## 6. Accountability & Audit Readiness

| Regulatory Requirement | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve CRS |
|------------------------|-------------|--------------|-----------------|--------------|
| Demonstrate reasonable security safeguards | Yes | Partial | Yes | Strong |
| Maintain audit trails | Yes | Limited | Yes | Yes |
| Support regulatory reporting timelines | Indirect | Indirect | Indirect | Strong support |
| Enable compliance verification | Yes | Limited | Yes | Strong |

---

## Unified Compliance Coverage Summary

| Compliance Domain | Best-Fit Arcserve Coverage |
|------------------|---------------------------|
| Operational Backup & Restore | Arcserve UDP / Backup |
| High Availability | Arcserve Replication & HA |
| Cyber Incident Recovery | Arcserve Cyber Resilient Storage |
| Ransomware & Immutability | Arcserve Cyber Resilient Storage |
| Evidence Preservation | Backup + CRS |
| Assume-Breach Compliance | Cyber Resilient Storage |

---

## Executive Compliance Statement

> **CERT-In and DPDP compliance converge on one principle:**  
> *Organisations must assume cyber compromise and ensure clean, verifiable recovery.*

A layered Arcserve architecture:
- **UDP / Backup** for operational recovery  
- **Replication & HA** for uptime  
- **Cyber Resilient Storage** for immutable, post-breach recovery  

provides strong alignment with **both CERT-In directions and DPDP Act obligations**.

