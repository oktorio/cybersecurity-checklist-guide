# Cybersecurity Checklist v3.2 — Workbook Design

The v3.2 Excel workbook is the authoritative operational working paper. It retains the v3.1 **133-control** architecture and adds service-centric, time-bound and lifecycle-oriented fieldwork tools.

## Core sheets retained

- Scoping Wizard
- Checklist v3.1 — retained as the stable 133-control catalogue inside the workbook
- Dashboard
- Evidence Register
- Sampling Log
- Findings Register
- Remediation Tracker
- Parameters
- Vulnerability Prioritization
- ATT&CK Detection Coverage
- Reference Map
- Instructions

## New v3.2 sheets

### Regulatory Calendar
Tracks both recurring and event-driven regulatory obligations. Fields include regulator, scope, obligation, trigger/frequency, exact deadline rule, legal criteria, trigger timestamp, due timestamp, remaining time, owner, status, evidence/submission reference and official source.

The design intentionally distinguishes **validated exact deadlines** from obligations whose current submission timetable/channel must be revalidated.

### Critical Services Map
Creates an end-to-end view of critical business services/operations and their dependencies. It connects BIA/resilience assumptions to applications, databases, identity, network/security, data classification, third parties/cloud, region/location, recovery arrangements, scenario/DR tests, actual recovery experience and open gaps.

### Security Exceptions
Operationalizes `GV-13 Issue Governance`. It records deviations, justification, accountable risk owner, compensating controls, approval authority, start/expiry dates, days to expiry, residual risk, validation and finding/risk references. The Dashboard separately identifies expired and near-expiry exceptions.

### Technology Lifecycle
Operationalizes `ID-13 Technology Lifecycle`. It records vendor/version, criticality, environment, end-of-support, end-of-life, support status, security constraints, exceptions, replacement target, migration owner/date/progress and validation.

### Crypto & PQC Inventory
Operationalizes `ID-18 Emerging & PQC Risk` and `PR-21 Cryptographic Key Management`. It records cryptographic use cases, protocol/mechanism, algorithm, parameters, key/certificate ownership and expiry, public-key use, quantum vulnerability, sensitive-data lifetime, crypto-agility readiness, target migration approach, priority and vendor/dependency constraints.

### Software Supply Chain
Operationalizes `PR-26 Secure SDLC` and `PR-28 Software Supply Chain`. It records source/build platforms, SBOM availability/version, SCA recency, dependency issues, approved registries, signing, provenance/attestation, build isolation, secrets scanning, dependency pinning/lockfiles, third-party exceptions and assessment status.

## Dashboard additions

The v3.2 Dashboard adds operational-hardening KPIs for:

- Regulatory Obligations Overdue
- Active Exceptions Expired
- Exceptions Expiring ≤30 Days
- EOS/EOL Technology Items
- Critical Services Without Test Date
- Urgent PQC Migration Items
- Software Supply Chain Gaps

## Methodology safeguards

- The control count remains 133; registers are evidence/testing mechanisms rather than additional controls.
- The internal 1–4 capability scale remains an audit/supervisory aid, not a NIST Implementation Tier.
- Framework references strengthen testing but do not replace Indonesian law/regulation.
- Working-day formulas may require adjustment for Indonesian public holidays; formal deadline conclusions must be checked against the official provision and applicable calendar.
- Do not store cryptographic secret/key material in the Crypto & PQC Inventory.
