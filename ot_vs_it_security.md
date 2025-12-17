# OT vs IT Security: Why Traditional Assumptions Do Not Apply

This document explains the fundamental differences between Information Technology (IT) and Operational Technology (OT) security. Understanding these differences is critical for accurate risk assessment, realistic monitoring expectations, and effective governance in industrial environments.

Applying IT security assumptions directly to OT systems often leads to ineffective controls, operational risk, or safety concerns.

---

## 1. Different Primary Objectives

The core objectives of IT and OT systems differ significantly:

- **IT systems** prioritize confidentiality, integrity, and availability (CIA), often in that order.
- **OT systems** prioritize safety and availability above all else, with integrity and confidentiality as secondary considerations.

Security controls that impact availability or deterministic behavior may be acceptable in IT environments but unacceptable in OT environments.

---

## 2. Change Management Constraints

IT environments typically allow:
- Frequent patching
- System reboots
- Rapid configuration changes

OT environments often face:
- Infrequent maintenance windows
- Strict change control processes
- High risk associated with unplanned downtime
- Systems that must run continuously for years

These constraints limit the applicability of many IT security practices.

---

## 3. Technology and Protocol Differences

OT environments commonly use:
- Legacy operating systems
- Proprietary hardware and software
- Industrial protocols not designed with security in mind
- Devices with limited compute and memory resources

Many of these systems cannot support modern endpoint agents or frequent updates.

---

## 4. Visibility and Monitoring Challenges

Unlike IT environments, OT systems:
- Often lack native logging capabilities
- Cannot tolerate active scanning or intrusive monitoring
- May rely on passive visibility methods

As a result, security monitoring in OT is often partial and delayed, requiring careful interpretation.

---

## 5. Incident Response Constraints

In IT environments, incident response may involve:
- Isolating systems
- Blocking traffic
- Reimaging or restoring endpoints

In OT environments, these actions may:
- Disrupt physical processes
- Introduce safety hazards
- Cause production losses

Response actions must be coordinated with operations and safety teams.

---

## 6. Risk Ownership and Accountability

OT cyber risk is often shared across:
- Engineering teams
- Operations teams
- Safety functions
- IT security and GRC teams
- Executive leadership

Clear governance is required to ensure accountability and avoid assumptions that “security owns the risk.”

---

## 7. Governance Implications

From a governance perspective:
- OT cyber risk cannot be treated as purely technical
- Risk acceptance decisions must consider safety and operational impact
- Monitoring limitations should be explicitly documented
- Leadership must be aware of constraints and tradeoffs

Effective OT security governance acknowledges these realities rather than attempting to force IT-centric models onto industrial systems.

---
