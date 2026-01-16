# CERT-In Compliance Mapping – Arcserve Portfolio

## Reference Authority
CERT-In (Indian Computer Emergency Response Team)

---

## 1. Incident Readiness & Mandatory Reporting

| CERT-In Expectation | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve Cyber Resilient Storage |
|---------------------|-------------|--------------|-----------------|----------------------------------|
| Ability to recover from cyber incidents | Yes | Partial | Yes | Yes |
| Support rapid restoration after attack | Yes | Yes | Limited | Yes |
| Preserve evidence for investigation | Limited | No | Yes | Yes |
| Support incident timelines (6-hour reporting) | Indirect | Indirect | Indirect | Strong support |

**Notes:**  
- CERT-In mandates rapid incident response and reporting.  
- CRS enables clean recovery even when primary backups are compromised.

---

## 2. Ransomware & Data Integrity Protection

| CERT-In Expectation | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve CRS |
|---------------------|-------------|--------------|-----------------|--------------|
| Protection against ransomware | Medium | Low | Low | Very High |
| Immutable backups | Optional | No | No | Native |
| Tamper-proof data retention | Medium | Low | Low | Very High |
| Detect abnormal data modification | Basic | No | No | Advanced |

**Key Insight:**  
Replication solutions **replicate ransomware too**. CERT-In guidance assumes breach—CRS directly addresses this.

---

## 3. Business Continuity & Availability

| CERT-In Expectation | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve CRS |
|---------------------|-------------|--------------|-----------------|--------------|
| Minimise service downtime | Yes | Yes (best) | Limited | Indirect |
| Meet critical RTO/RPO | Yes | Yes (near-zero) | Limited | Yes (post-incident) |
| Automated recovery mechanisms | Yes | Yes | No | No |
| Protection of critical infrastructure | Yes | Yes | Yes | Yes |

---

## 4. Data Retention, Logs & Evidence Preservation

| CERT-In Expectation | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve CRS |
|---------------------|-------------|--------------|-----------------|--------------|
| Retain logs and backups securely | Yes | Limited | Yes | Yes |
| Prevent alteration of retained data | Medium | Low | Low | Very High |
| Support forensic investigations | Limited | No | Yes | Yes |
| Long-term retention compliance | Yes | Yes | Yes | Yes |

---

## 5. Assume-Breach & Cyber Resilience Posture

| CERT-In Principle | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve CRS |
|-------------------|-------------|--------------|-----------------|--------------|
| Assume systems may be compromised | Partial | No | No | Yes |
| Isolate recovery environment | Limited | No | No | Yes |
| Enable clean-room recovery | Limited | No | No | Yes |
| Last line of defence strategy | No | No | No | Yes |

---

## Compliance Alignment Summary

| CERT-In Domain | Best-Fit Arcserve Product |
|---------------|--------------------------|
| Backup & Recovery | Arcserve UDP / Backup |
| High Availability | Arcserve Replication & HA |
| Ransomware Recovery | Arcserve Cyber Resilient Storage |
| Evidence Preservation | Arcserve Backup + CRS |
| Assume-Breach Resilience | Arcserve Cyber Resilient Storage |

---

## Executive Compliance Statement

> **CERT-In compliant recovery strategies must assume cyber compromise, not clean failures.**  
> Arcserve Cyber Resilient Storage provides the immutable, isolated recovery layer required to meet this mandate, while UDP and RHA address operational continuity.

