# v3.1 Change Log and Consolidation Review

**Baseline date: 16 August 2026**

## Summary

v3.1 keeps the NIST CSF 2.0 architecture introduced in v3 but expands the toolkit from **125 to 133 active controls** after a deliberate duplication/consolidation review.

Function distribution:
- Govern: 22
- Identify: 19
- Protect: 40
- Detect: 20
- Respond: 19
- Recover: 13

## New controls

- `GV-21` Anti-Fraud Strategy Governance
- `GV-22` AI Governance & Approved Use Cases
- `ID-19` AI Inventory & Risk Classification
- `PR-40` AI/GenAI Security & Data Protection
- `DE-19` BI-FAST Fraud Detection & Operational Monitoring
- `DE-20` AI Monitoring & Model/Output Risk
- `RS-17` Significant Fraud Reporting – OJK 3 Working Days
- `RS-18` BI-FAST Cyber Incident Notification – 1 Hour
- `RS-19` AI Incident & Model Disablement

## Enhanced existing controls

- `ID-17` now explicitly links fraud/cyber scenarios to the Anti-Fraud Strategy.
- `DE-09` now includes the POJK 12/2024 fraud-detection/FDS context.
- `PR-18` adds threat-led vulnerability prioritization using KEV, external exposure, asset criticality, exploitability and validated compensating controls.
- `DE-04` and `DE-18` add MITRE ATT&CK v19.1 coverage/testing support.
- `RS-09` adds conditional BI consumer-protection mapping where applicable.
- `RS-11` explicitly maps to fraud investigation/reporting context.
- `RC-11` expands post-incident lessons learned to include fraud corrective-action feedback.
- `PR-25` is clarified as **Cross-Channel Malware & Ransomware Prevention**.

## Consolidated / retired control

`RC-13 Recovery Metrics` (v3) was retired because it materially overlapped `RC-03 RTO/RPO Achievement`.

The surviving control is now:

`RC-03 Recovery Performance, RTO/RPO & Metrics`

It covers:
- planned vs actual RTO/RPO,
- service recovery performance,
- restoration metrics,
- recovery-test outcomes,
- trend analysis and management follow-up.

## Duplicate review outcome

A text-similarity and control-objective review was performed across all 133 active controls. No additional material duplicate was identified.

High-similarity pairs retained intentionally:
- Governance vs response for BI KKS.
- AI governance vs AI inventory vs AI protection vs AI monitoring vs AI incident response.
- Detection use-case design vs detection validation/testing.
- Fraud scenario identification vs enterprise fraud monitoring vs BI-FAST-specific FDS monitoring.
- General BI cyber incident handling vs BI-FAST-specific one-hour notification.
- Business impact analysis vs recovery-performance measurement.
- Vulnerability inventory/scanning/remediation are retained as separate lifecycle objectives.

## New workbook capabilities

- Scoping Wizard / regulatory-perimeter logic.
- Applicability formulas.
- Legal Criteria / Clause and Criteria Summary.
- Criteria Type and Reference Precision.
- Design Effectiveness and Operating Effectiveness.
- Internal Current/Target Capability and gap.
- Evidence Register.
- Sampling Log.
- Findings Register.
- Remediation Tracker.
- Parameterized vulnerability prioritization.
- CISA KEV and exposure-based prioritization.
- MITRE ATT&CK v19.1 detection-coverage sheet.
- Dashboard for scope, assessment result, function distribution, and capability gaps.

## Methodology caution

The internal 1–4 capability scale is an audit/supervisory aid and must not be represented as a NIST CSF Implementation Tier. Formal legal conclusions must rely on the exact applicable Indonesian legal/regulatory text, not on a framework benchmark or section-level mapping alone.
