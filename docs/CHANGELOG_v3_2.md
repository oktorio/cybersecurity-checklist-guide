# v3.2 Operational Hardening Change Log

**Baseline date: 16 August 2026**

## Design decision

v3.2 deliberately retains the **133 active controls** from v3.1. The review found that the remaining improvement opportunity was operational depth rather than additional generic questions. Existing controls were therefore enhanced and linked to new fieldwork registers instead of creating duplicative controls.

## New workbook sheets

1. **Regulatory Calendar** — recurring/event-driven OJK and BI obligations, deadline rules, legal criteria, trigger/due timestamps, owner, status, evidence and official source.
2. **Critical Services Map** — critical-service ownership, business impact, MTD/impact tolerance, RTO/RPO, application/data/identity/network/vendor dependencies, recovery arrangements and test/recovery evidence.
3. **Security Exceptions** — control deviation, justification, risk owner, compensating controls, approval, expiry, residual risk, validation and finding/risk linkage.
4. **Technology Lifecycle** — vendor/version, EOS/EOL, support status, constraints, exception, target replacement and migration milestones.
5. **Crypto & PQC Inventory** — cryptographic use cases, protocols/algorithms, key/certificate ownership and expiry, quantum vulnerability, crypto-agility readiness and PQC migration planning.
6. **Software Supply Chain** — repository/build platform, SBOM/SCA coverage, package registry, signing, provenance/attestation, build isolation, secrets scanning, dependency controls and exceptions.

## Existing controls enhanced — no duplicate added

- `GV-13 Issue Governance`: links risk acceptance/control exceptions to the Security Exceptions register and explicit expiry review.
- `ID-04 Business Service Mapping`, `ID-05 Business Impact Analysis`, `RC-02 DR Site Resilience`, `RC-03 Recovery Performance`: linked to the Critical Services Map for service-centric resilience testing.
- `ID-13 Technology Lifecycle`: linked to the EOS/EOL register and replacement milestones.
- `ID-18 Emerging & PQC Risk` and `PR-21 Cryptographic Key Management`: strengthened with cryptographic inventory and crypto-agility/PQC transition considerations.
- `PR-05 Multi-Factor Authentication`: mapped to NIST SP 800-63B-4.
- `PR-26 Secure SDLC`: mapped to NIST SP 800-218 SSDF v1.1.
- `PR-28 Software Supply Chain`: strengthened with explicit SBOM/SCA, trusted registry, signing, provenance/attestation and build-isolation tracking.

## Regulatory Calendar — exact validated deadlines

The workbook hard-codes exact deadlines only where directly validated against official provisions. These include:

- SEOJK 29/2022 cyber inherent-risk assessment result: no later than **15 working days after year-end**.
- Initial OJK cyber-incident notification: no later than **24 hours after the Bank becomes aware**.
- Complete OJK cyber-incident report: no later than **5 working days after the Bank becomes aware**.
- Scenario-based cyber-test result: no later than **10 working days after testing is completed**.
- POJK 12/2024 Anti-Fraud Strategy implementation report for bank umum: **semiannual** for end-June/end-December, no later than the **31st of the following month**.
- Significant Fraud event report for bank umum: no later than **3 working days after becoming known**.
- Change to Anti-Fraud Strategy: no later than **7 working days from the change**.
- Correction/update of Anti-Fraud reports: no later than **15 working days after the error/change becomes known**.
- Conditional BI-FAST cyber incident: **1-hour notification to the Operator** under the applicable BI-FAST provision.

Where a submission timetable depends on changing technical/reporting instructions, v3.2 explicitly marks the obligation for revalidation instead of inventing a fixed due date.

## Framework updates

- NIST SP 800-63B-4, final July 2025 — authentication/authenticator benchmark.
- NIST SP 800-218 SSDF v1.1 — secure software development and software-supply-chain benchmark.
- NIST CSWP 39 Update 1, updated June 2026 — crypto-agility benchmark.
- NIST NCCoE Migration to Post-Quantum Cryptography — cryptographic visibility/inventory and PQC migration support.

## Dashboard hardening KPIs

Added counts for:
- overdue regulatory obligations;
- active expired exceptions;
- exceptions expiring within 30 days;
- EOS/EOL technology items;
- critical services without a recorded test date;
- urgent PQC migration items; and
- software-supply-chain gaps.

## Duplication review result

No additional material duplicate was identified. The previous `RC-13` → `RC-03` consolidation remains the only retired/merged control. v3.2 does not increase the active-control count.
