# v3.1 Workbook Design

The v3.1 workbook was generated and QA-checked from the same 133-control catalogue used by the repository control index.

## Sheets

- **Scoping Wizard** — regulatory/perimeter questions that drive applicability.
- **Checklist v3.1** — 133 controls with bilingual questions, expected evidence, test procedures, legal criteria, criteria type, ATT&CK mapping, applicability, risk, design/operating effectiveness, internal current/target capability, evidence IDs, notes and finding references.
- **Dashboard** — control counts, scope status, results, function distribution and capability gaps.
- **Evidence Register** — evidence traceability by control.
- **Sampling Log** — population, sample method/size, exceptions and conclusion.
- **Findings Register** — criteria, condition, root cause, risk, owner, status and evidence linkage.
- **Remediation Tracker** — remediation actions and independent validation.
- **Parameters** — transparent vulnerability-priority weights and thresholds.
- **Vulnerability Prioritization** — CISA KEV, internet exposure, asset criticality, exploitability, compensating controls, due dates and priority scoring.
- **ATT&CK Detection Coverage** — MITRE ATT&CK v19.1 tactic coverage/testing.
- **Reference Map** — current/conditional/legacy regulatory and framework references.
- **Instructions** — assessment method and legal-reference cautions.

## Assessment method

Design Effectiveness and Operating Effectiveness are assessed separately. Current/Target Capability uses an internal 1–4 scale for gap analysis and is explicitly **not** represented as an official NIST CSF Implementation Tier.

## QA

The generated workbook was scanned for formula errors and the dashboard totals were validated against the 133-control source catalogue. Binary integrity metadata is recorded in `checklist/Cybersecurity_Checklist_Auditee_v3_1.xlsx.sha1`.
