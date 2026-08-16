# Cybersecurity Checklist for Auditee (v3.1)

**Regulatory baseline reviewed as of 16 August 2026.**

Version 3.1 evolves the v3 audit working paper into a more complete **cybersecurity supervisory assessment engine** for commercial-bank cybersecurity, technology-risk, fraud, resilience, and conditional payment-system reviews.

## What changed in v3.1

- **133 active controls** across NIST CSF 2.0 functions: Govern (22), Identify (19), Protect (40), Detect (20), Respond (19), and Recover (13).
- Added **POJK No. 12 Tahun 2024 — Penerapan Strategi Anti Fraud bagi LJK** and direct fraud-governance/detection/reporting mappings.
- Updated the **BI-FAST regulatory chain** to PADG 17/2023 as amended by PADG 1/2025, PADG 14/2025, and PADG 3/2026.
- Added conditional **PBI No. 6 Tahun 2026 — Pelindungan Konsumen Bank Indonesia** coverage where the reviewed product/service falls within the BI consumer-protection perimeter.
- Added a conditional **AI / GenAI module** using OJK Indonesian Banking AI Governance and NIST AI RMF / GenAI Profile as guidance/benchmarks.
- Added a **Scoping Wizard** that resolves conditional controls to `Applicable`, `N/A`, or `Review Scope`.
- Expanded regulatory traceability with **Legal Criteria / Clause**, **Criteria Summary**, **Criteria Type**, and **Reference Precision**.
- Added separate **Design Effectiveness** and **Operating Effectiveness** conclusions.
- Added internal **Current Capability / Target Capability / Gap** scoring. This internal 1–4 scale is **not** represented as an official NIST CSF Implementation Tier.
- Added **CISA KEV / exposure / asset-criticality vulnerability prioritization**.
- Added **MITRE ATT&CK v19.1 detection coverage** and testing support.
- Added **Evidence Register, Sampling Log, Findings Register, and Remediation Tracker**.
- Added configurable **Parameters** so vulnerability-priority thresholds and weights are transparent rather than embedded as unexplained constants.

## Duplication / consolidation review

A second overlap review was completed after the v3.1 additions.

- `RC-13 Recovery Metrics` from v3 was **retired and consolidated into `RC-03 Recovery Performance, RTO/RPO & Metrics`**.
- No other material duplicate was identified.
- Similar controls that remain are intentionally separated by control objective, for example:
  - `DE-04 Detection Use Cases` vs `DE-18 Detection Testing` — design/coverage vs validation.
  - `ID-17 Fraud-Cyber Scenarios` vs `DE-09 Digital Fraud Monitoring` — risk identification vs continuous detection.
  - `DE-19 BI-FAST Fraud Detection & Operational Monitoring` vs `DE-09` — BI-FAST-specific mandatory overlay vs enterprise monitoring.
  - `RS-16 BI KKS Incident Handling` vs `RS-18 BI-FAST Cyber Incident Notification – 1 Hour` — general BI cyber obligations vs BI-FAST-specific notification timeline.
  - AI controls are separated into governance, inventory/risk classification, protection, monitoring, and incident response.

## Files

- `checklist/Cybersecurity_Checklist_Auditee_v3_1.xlsx` — **authoritative v3.1 working paper**.
- `checklist/Cybersecurity_Checklist_Auditee_v3_1.md` — GitHub-readable v3.1 control index.
- `checklist/Cybersecurity_Checklist_Auditee_v3.xlsx` — prior v3 release retained for comparison.
- `docs/REFERENCES.md` — current regulatory/framework map.
- `docs/CHANGELOG_v3_1.md` — v3 → v3.1 changes and consolidation decisions.
- `archive/v2/` — historical v2 artifacts.

## Recommended workflow

1. Complete the **Scoping Wizard** and retain evidence supporting the regulatory/applicability determination.
2. Filter the checklist to applicable controls.
3. Obtain and register evidence.
4. Perform the specified testing and record sampling where relevant.
5. Assess **design** and **operating effectiveness** separately.
6. Record the control result and capability gap.
7. Raise findings only after validating the applicable legal/supervisory criteria.
8. Track remediation and independent closure validation.
9. Use the Vulnerability Prioritization and ATT&CK sheets for threat-led technical testing.

## Important legal / regulatory note

This repository is an audit and supervisory aid, not a substitute for the official regulation text or entity-specific legal interpretation. A `Section-level / control mapping` in the workbook must not be quoted as an exact legal clause without revalidation. Always verify effective dates, scope, amendments, transition rules, exemptions, and current reporting channels before formal sign-off.
