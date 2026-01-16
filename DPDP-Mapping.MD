# DPDP Act (India) Compliance Mapping – Arcserve Portfolio

## Reference
Digital Personal Data Protection (DPDP) Act, India

Scope: Protection, processing, retention, breach response, and recovery of personal data.

---

## 1. Data Protection & Integrity

| DPDP Requirement | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve Cyber Resilient Storage |
|------------------|-------------|--------------|-----------------|----------------------------------|
| Protect personal data from loss or corruption | Yes | Yes | Yes | Yes |
| Ensure data integrity during storage | Yes | Partial | Yes | Yes |
| Prevent unauthorised alteration of stored data | Medium | Low | Low | Very High |
| Secure backup copies of personal data | Yes | No | Yes | Yes |

**Insight:**  
The DPDP Act requires *reasonable security safeguards*. Immutability and tamper resistance significantly strengthen compliance posture.

---

## 2. Breach Response & Recovery

| DPDP Requirement | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve CRS |
|------------------|-------------|--------------|-----------------|--------------|
| Ability to restore data after breach | Yes | Partial | Yes | Yes |
| Recover from ransomware incidents | Medium | Low | Low | Very High |
| Isolate compromised systems during recovery | Limited | No | No | Yes |
| Support clean recovery after attack | Limited | No | No | Yes |

**Key Point:**  
Replication alone does **not** meet DPDP breach recovery expectations—it replicates compromised data as well.

---

## 3. Storage Limitation & Retention Control

| DPDP Requirement | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve CRS |
|------------------|-------------|--------------|-----------------|--------------|
| Enforce defined retention policies | Yes | No | Yes | Yes |
| Support data lifecycle management | Yes | No | Yes | Yes |
| Prevent over-retention of personal data | Yes | No | Yes | Yes |
| Secure deletion after retention expiry | Yes | No | Yes | Policy-driven |

---

## 4. Accountability & Auditability

| DPDP Requirement | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve CRS |
|------------------|-------------|--------------|-----------------|--------------|
| Demonstrate reasonable security safeguards | Yes | Partial | Yes | Strong |
| Maintain audit trails for data handling | Yes | Limited | Yes | Yes |
| Preserve evidence after incidents | Limited | No | Yes | Yes |
| Support regulatory inquiries | Yes | Limited | Yes | Strong |

---

## 5. Risk-Based Safeguards (Section 8 Alignment)

| DPDP Principle | Arcserve UDP | Arcserve RHA | Arcserve Backup | Arcserve CRS |
|---------------|-------------|--------------|-----------------|--------------|
| Risk-based security controls | Yes | Partial | Yes | Yes |
| Protection against evolving threats | Medium | Low | Low | High |
| Assume breach scenarios | Partial | No | No | Yes |
| Defence-in-depth approach | Yes | No | Yes | Yes |

---

## Compliance Coverage Summary

| DPDP Domain | Recommended Arcserve Coverage |
|------------|------------------------------|
| Backup & Restore | Arcserve UDP / Backup |
| Business Continuity | Arcserve Replication & HA |
| Breach Recovery | Arcserve Cyber Resilient Storage |
| Data Integrity & Immutability | Arcserve Cyber Resilient Storage |
| Audit & Accountability | Backup + CRS |

---

## Executive Compliance Statement

> **DPDP compliance is not only about protecting personal data during normal operations,  
> but about ensuring clean, verifiable recovery after a breach.**

A layered Arcserve architecture—combining **UDP or Backup for operational recovery**, **Replication for availability**, and **Cyber Resilient Storage for immutable recovery**—provides strong alignment with DPDP Act obligations.

