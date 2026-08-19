# Cybersecurity Checklist for Auditee (v3.2)

**Regulatory baseline reviewed as of 16 August 2026.**

Version 3.2 is an **operational-hardening release** of the v3.1 supervisory engine. It deliberately keeps the **133 active-control catalogue** stable and improves how the controls are scoped, evidenced, monitored, and followed through during real audit/supervisory fieldwork.

## Start here — Latest Checklist

To avoid confusion, use these as the **current stable checklist files**:

- **[Download the latest Excel checklist — Cybersecurity_Checklist_Auditee_v3_2.xlsx](checklist/Cybersecurity_Checklist_Auditee_v3_2.xlsx)** — authoritative audit / supervisory working paper.
- **[Open the latest GitHub-readable checklist — Cybersecurity_Checklist_Auditee_v3_2.md](checklist/Cybersecurity_Checklist_Auditee_v3_2.md)** — readable control index for browsing on GitHub.
- **[Current regulatory & framework references](docs/REFERENCES.md)** — OJK, BI, NIST, CIS, MITRE ATT&CK, and other mapped references.

> **If you only need one file, start with the Excel workbook above.** Older versions are retained only for historical comparison.

## v3.2 principle: deepen, do not duplicate

The v3.1 duplication review remains valid. No new generic control was added merely to increase coverage. Instead, existing controls are operationalized through dedicated registers and stronger current-framework mappings.

The 133 controls remain distributed as:
- Govern: 22
- Identify: 19
- Protect: 40
- Detect: 20
- Respond: 19
- Recover: 13

## New v3.2 operational registers

The QA-generated v3.2 Excel working paper adds:

- **Regulatory Calendar** — recurring and event-driven OJK/BI obligations, validated deadlines, owners, due dates, status, and submission evidence.
- **Critical Services Map** — service-centric BIA/resilience mapping across applications, data, identity, network, third parties, cloud, recovery arrangements, tests, and open gaps.
- **Security Exceptions** — approval, compensating controls, residual risk, finite expiry, aging, validation, and finding/risk linkage.
- **Technology Lifecycle** — vendor/version inventory, EOS/EOL exposure, exceptions, replacement platform, migration milestone, and validation.
- **Crypto & PQC Inventory** — protocols, algorithms, keys/certificates, quantum-vulnerable dependencies, crypto-agility readiness, PQC migration priority and roadmap.
- **Software Supply Chain** — SBOM/SCA coverage, trusted registries, signing, provenance/attestation, build isolation, secrets scanning, dependency controls and exceptions.

The Dashboard adds hardening KPIs for overdue regulatory obligations, expired/expiring exceptions, EOS/EOL technology, untested critical services, urgent PQC migration items, and software-supply-chain gaps.

## Existing controls strengthened in v3.2

No duplicate controls were created. Existing controls were enhanced instead:

- `GV-13 Issue Governance` → Security Exceptions register and expiry governance.
- `ID-04 Business Service Mapping`, `ID-05 Business Impact Analysis`, `RC-02 DR Site Resilience`, `RC-03 Recovery Performance` → Critical Services Map.
- `ID-13 Technology Lifecycle` → dedicated EOS/EOL and migration tracker.
- `ID-18 Emerging & PQC Risk` and `PR-21 Cryptographic Key Management` → crypto inventory, crypto-agility and PQC transition readiness.
- `PR-05 Multi-Factor Authentication` → current NIST SP 800-63B-4 benchmark mapping.
- `PR-26 Secure SDLC` and `PR-28 Software Supply Chain` → NIST SSDF v1.1 plus explicit SBOM, signing, provenance and build-pipeline tracking.

## Key regulatory calendar coverage

The workbook includes exact deadlines only where directly validated against official sources, including:

- OJK initial cyber-incident notification: **within 24 hours** after the Bank becomes aware.
- Complete OJK cyber-incident report: **within 5 working days** after the Bank becomes aware.
- Scenario-based cyber-test report: **within 10 working days** after testing is completed.
- Anti-Fraud Strategy implementation report for bank umum: **semiannual**, due no later than the **31st of the following month**.
- Significant Fraud event report for bank umum: **within 3 working days** after the event becomes known.
- Change to Anti-Fraud Strategy: **within 7 working days** from the change.
- Correction/update to Anti-Fraud reports: **within 15 working days** after the error/change becomes known.
- BI-FAST cyber incident: conditional **1-hour notification** to the Operator under the applicable BI-FAST provision.

Deadlines that depend on changing technical reporting instructions are explicitly marked for revalidation rather than presented as false precision.

## Repository files

- `checklist/Cybersecurity_Checklist_Auditee_v3_2.xlsx` — **latest authoritative v3.2 Excel working paper**.
- `checklist/Cybersecurity_Checklist_Auditee_v3_2.md` — **latest GitHub-readable v3.2 control index**.
- `checklist/Cybersecurity_Checklist_Auditee_v3_2.xlsx.sha256` — integrity metadata for the v3.2 workbook.
- `docs/WORKBOOK_v3_2.md` — v3.2 workbook structure and usage.
- `docs/CHANGELOG_v3_2.md` — v3.1 → v3.2 hardening changes and non-duplication decision.
- `docs/REFERENCES.md` — current Indonesian regulatory and international framework reference map.
- `archive/` — historical checklist versions and artifacts.

## Recommended workflow

1. Open the **latest Excel checklist** from the link at the top of this README.
2. Complete the **Scoping Wizard**.
3. Map **critical business services** and dependencies before detailed control testing.
4. Filter to applicable controls and register evidence.
5. Perform testing/sampling and assess design + operating effectiveness.
6. Use the regulatory calendar for submission/deadline tracking.
7. Use Security Exceptions and Technology Lifecycle to challenge temporary risk acceptance and unsupported technology.
8. Use Crypto & PQC Inventory and Software Supply Chain for forward-looking technical risk.
9. Raise findings only after validating exact applicable legal/supervisory criteria.
10. Track remediation and independent closure validation.

## Important legal / regulatory note

This repository is an audit and supervisory aid, not a substitute for the official regulation text or entity-specific legal interpretation. Section-level/control mappings must not be quoted as exact legal clauses without revalidation. Always verify effective dates, scope, amendments, transition rules, exemptions, holidays affecting working-day calculations, and current reporting channels before formal sign-off.
