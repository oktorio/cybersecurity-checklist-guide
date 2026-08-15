# Regulatory & Content Changelog — v3

**Baseline review date: 15 August 2026**

## Major regulatory changes incorporated

### 1. PADK OJK No. 1 Tahun 2026 added as the current detailed IT baseline
- Effective **1 March 2026** for all commercial banks.
- Covers IT governance, roles and responsibilities, IT architecture and strategy, IT-risk management, information/network security, IT service providers, overseas processing, data management and personal-data protection, internal control/audit, and reporting.
- **SEOJK 21/SEOJK.03/2017 is treated as repealed/legacy**, not as a current primary requirement.
- v3 adds deeper audit tests around privileged access, dual custody/break-glass administration, patch management, PPJTI, data governance, consent, DPIA, data exchange, DR and IT audit.

### 2. SEOJK 29/SEOJK.03/2022 incident-reporting logic corrected
The v2 question referring to **“3 days initial / 10 days final”** was removed.
- Initial cyber-incident notification to OJK: **no later than 24 hours after the incident becomes known**.
- Complete cyber-incident report: **no later than 5 working days after the incident becomes known**.
- Scenario-based cyber-security testing report to OJK: **no later than 10 working days after the test is considered complete**; v3 separates this from ordinary incident-reporting requirements.

### 3. Digital maturity added
**SEOJK 24/SEOJK.03/2023** is added to governance and maturity controls. v3 covers the annual digital-maturity assessment across IT governance, architecture, IT risk, cyber resilience/security, technology, data, collaboration and consumer protection.

### 4. Broader OJK governance/digital/customer overlays added
- **POJK No. 17 Tahun 2023** — governance for commercial banks.
- **POJK No. 21 Tahun 2023** — digital services by commercial banks.
- **POJK No. 22 Tahun 2023** — consumer and public protection in financial services.

### 5. Privacy controls strengthened
**UU No. 27 Tahun 2022 (PDP)** is mapped together with the more detailed data/privacy control expectations in PADK OJK No. 1 Tahun 2026. v3 includes lawful basis/consent, data-subject rights, processor oversight, retention/deletion, high-risk processing/DPIA, data exchange and breach-response controls. Applicable Constitutional Court decisions should also be checked during legal validation.

### 6. Conditional Bank Indonesia / payment-system overlay added
Controls marked conditional may reference:
- **PBI No. 2 Tahun 2024** and **PADG No. 24 Tahun 2024** for information-system security and cyber resilience.
- **PBI No. 10 Tahun 2025** and **PADG No. 32 Tahun 2025**, effective **31 March 2026**, for payment-system industry requirements.
- **PADG No. 3 Tahun 2026**, effective **31 March 2026**, for relevant BI-FAST participation/security requirements.

These controls are not automatically applicable to every bank; confirm the auditee's BI regulatory perimeter and activities.

## International framework changes

### NIST
- Migrated the primary taxonomy from **NIST CSF v1.1 to NIST CSF 2.0**.
- v3 uses all six CSF 2.0 functions: **Govern, Identify, Protect, Detect, Respond, Recover**.

### CIS
- Updated technical-control reference to **CIS Critical Security Controls v8.1**.

### API security
- Added/currentized **NIST SP 800-228 Update 1**, including API risk categories and controls across the API lifecycle.

### FFIEC CAT
- Reclassified as **legacy/supplementary** because FFIEC sunset the Cybersecurity Assessment Tool on **31 August 2025** and no longer updates it.

## Working-paper design changes

v2 mainly provided:
- Domain
- Question EN/ID
- Reference

v3 adds:
- Unique Control ID
- NIST CSF 2.0 Function
- Domain / Subdomain
- Expected Evidence
- Audit / Test Procedure
- Primary Regulatory Reference
- Framework Mapping
- Applicability
- Default Risk
- Result
- Auditor Notes
- Finding Reference
- Dashboard and reference map in the Excel version

## Control-count summary

| Function | Controls |
|---|---:|
| GV — Govern | 20 |
| ID — Identify | 18 |
| PR — Protect | 39 |
| DE — Detect | 18 |
| RS — Respond | 16 |
| RC — Recover | 14 |
| **Total** | **125** |

## Legal-validation caution

This repository is a practical control and audit-testing aid. It does not provide a legal opinion. A formal finding should cite the exact operative provision and confirm scope, effective date, transitional provisions and official reporting instructions applicable to the auditee.
