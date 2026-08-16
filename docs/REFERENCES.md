# Regulatory & Framework References — Cybersecurity Checklist v3.2

**Reviewed as of 16 August 2026.**

The hierarchy is: **applicable Indonesian law/regulation and official OJK/BI provisions first**, then recognized frameworks/guidance used to strengthen testing and benchmarking.

| Status | Regulation / Framework | Scope / Use | Key v3.2 treatment | Official / Primary Source |
|---|---|---|---|---|
| CURRENT / PRIMARY | PADK OJK No. 1 Tahun 2026 — Penyelenggaraan Teknologi Informasi oleh Bank Umum | Commercial-bank IT governance, architecture/strategy, operations, IT risk/security, PPJTI, overseas processing, data/PDP, internal audit, reporting | Primary detailed IT-control baseline; effective 1 Mar 2026; SEOJK 21/2017 treated as legacy | https://ojk.go.id/id/regulasi/Pages/PADK-1-Tahun-2026-Penyelenggaraan-Teknologi-Informasi-oleh-Bank-Umum.aspx |
| CURRENT / PRIMARY | POJK No. 11/POJK.03/2022 — Penyelenggaraan Teknologi Informasi oleh Bank Umum | Principal bank-IT regulation | Used with PADK OJK 1/2026 | https://ojk.go.id/id/regulasi/Pages/Penyelenggaraan-Teknologi-Informasi-Oleh-Bank-Umum.aspx |
| CURRENT / PRIMARY | SEOJK No. 29/SEOJK.03/2022 — Ketahanan dan Keamanan Siber Bagi Bank Umum | Cyber inherent risk, maturity, controls, testing, incident response/reporting | Exact OJK incident/test deadlines are included in the v3.2 Regulatory Calendar where validated | https://www.ojk.go.id/id/regulasi/Pages/Ketahanan-dan-Keamanan-Siber-Bagi-Bank-Umum.aspx |
| CURRENT / PRIMARY | SEOJK No. 24/SEOJK.03/2023 — Penilaian Tingkat Maturitas Digital Bank Umum | Digital-maturity assessment | Used for maturity/scoping and improvement planning; current reporting timetable should be revalidated before each cycle | https://ojk.go.id/id/regulasi/Pages/Penilaian-Tingkat-Maturitas-Digital-Bank-Umum.aspx |
| CURRENT / PRIMARY | POJK No. 12 Tahun 2024 — Penerapan Strategi Anti Fraud bagi LJK | Anti-fraud governance, prevention, detection, investigation/reporting/sanctions, monitoring/follow-up | v3.2 Regulatory Calendar includes validated bank-umum reporting/change/correction timelines | https://www.ojk.go.id/en/regulasi/Pages/12-Tahun-2024-Penerapan-Strategi-Anti-Fraud-bagi-Lembaga-Jasa-Keuangan.aspx |
| CURRENT / PRIMARY | POJK No. 17 Tahun 2023 — Penerapan Tata Kelola Bagi Bank Umum | Governance, oversight, internal control and audit | Governance/accountability overlay | https://ojk.go.id/id/regulasi/Pages/Penerapan-Tata-Kelola-Bagi-Bank-Umum.aspx |
| CURRENT / PRIMARY | POJK No. 21 Tahun 2023 — Layanan Digital oleh Bank Umum | Digital-service governance/security/authentication/partners | Conditional on relevant digital services | https://ojk.go.id/id/regulasi/Pages/Layanan-Digital-oleh-Bank-Umum.aspx |
| CURRENT / PRIMARY | POJK No. 22 Tahun 2023 — Pelindungan Konsumen dan Masyarakat di Sektor Jasa Keuangan | Consumer protection and communication | Customer-impact overlay | https://ojk.go.id/id/regulasi/Pages/Pelindungan-Konsumen-dan-Masyarakat-di-Sektor-Jasa-Keuangan.aspx |
| CURRENT / PRIMARY | UU No. 27 Tahun 2022 — Pelindungan Data Pribadi | Personal-data governance and breach response | Privacy/data controls | https://peraturan.bpk.go.id/Details/229798/uu-no-27-tahun-2022 |
| CURRENT / GUIDANCE | OJK — Tata Kelola Kecerdasan Artifisial Perbankan Indonesia (2025) | Banking AI governance/model-risk guidance | Conditional AI module; guidance/benchmark, not labeled as a universal statutory requirement | https://www.ojk.go.id/id/berita-dan-kegiatan/siaran-pers/ |
| CONDITIONAL — BI | PBI No. 2 Tahun 2024 & PADG No. 24 Tahun 2024 — Keamanan Sistem Informasi dan Ketahanan Siber | BI cyber-security/resilience perimeter | Apply only after confirming BI regulatory classification; changing reporting timetable remains a revalidation item | https://www.bi.go.id/id/publikasi/peraturan/Pages/PBI_022024.aspx |
| CONDITIONAL — BI / PAYMENT SYSTEM | PBI No. 10 Tahun 2025 & PADG No. 32 Tahun 2025 | Payment-system industry controls | Apply to relevant payment-system activities; effective 31 Mar 2026 | https://www.bi.go.id/id/publikasi/peraturan/Pages/PBI_102025.aspx |
| CONDITIONAL — BI-FAST | PADG No. 17 Tahun 2023, as amended by PADG 1/2025, PADG 14/2025, and PADG 3/2026 | BI-FAST FDS, security, operations, incident response and participation | v3.2 Regulatory Calendar includes the conditional ≤1-hour cyber-incident notification to the Operator | https://www.bi.go.id/id/publikasi/peraturan/Pages/PADG_142025.aspx |
| CONDITIONAL — BI CONSUMER | PBI No. 6 Tahun 2026 — Pelindungan Konsumen Bank Indonesia | BI consumer-protection perimeter | Apply based on the actual BI-regulated product/service perimeter | https://jdih.bi.go.id/Web/DaftarPeraturan |
| CURRENT / FRAMEWORK | NIST Cybersecurity Framework 2.0 | Primary taxonomy and Profiles | Current/Target capability fields support gap analysis, but per-control 1–4 score is an internal method, not a NIST Tier | https://www.nist.gov/cyberframework |
| CURRENT / FRAMEWORK | CIS Critical Security Controls v8.1 | Technical safeguards | Cross-mapping / testing benchmark | https://www.cisecurity.org/controls/v8-1 |
| CURRENT / FRAMEWORK | MITRE ATT&CK Enterprise v19.1 | Threat/detection coverage | Detection coverage and testing sheet | https://attack.mitre.org/resources/updates/ |
| CURRENT / FRAMEWORK | CISA Known Exploited Vulnerabilities Catalog | Exploited-in-the-wild vulnerability prioritization | KEV is a direct priority input in the vulnerability sheet | https://www.cisa.gov/known-exploited-vulnerabilities-catalog |
| CURRENT / FRAMEWORK | NIST SP 800-63B-4 — Authentication and Authenticator Management | Authentication/authenticator benchmark; final July 2025 | Strengthens `PR-05` MFA/authenticator testing | https://csrc.nist.gov/pubs/sp/800/63/b/4/final |
| CURRENT / FRAMEWORK | NIST SP 800-218 — Secure Software Development Framework (SSDF) v1.1 | Secure software-development practices and software acquisition/supplier communication | Strengthens `PR-26` and `PR-28` | https://csrc.nist.gov/pubs/sp/800/218/final |
| CURRENT / FRAMEWORK | NIST CSWP 39 Update 1 — Considerations for Achieving Crypto Agility | Crypto-agility strategies/practices; update finalized June 2026 | Strengthens `ID-18`, `PR-21`, Crypto & PQC Inventory | https://csrc.nist.gov/pubs/cswp/39/upd1/considerations-for-achieving-crypto-agility/final |
| CURRENT / FRAMEWORK | NIST NCCoE — Migration to Post-Quantum Cryptography | Cryptographic visibility/inventory, risk management and PQC transition support | Used for the Crypto & PQC Inventory and migration planning | https://pages.nist.gov/nccoe-migration-post-quantum-cryptography/ |
| CURRENT / FRAMEWORK | NIST AI RMF 1.0 & NIST AI 600-1 GenAI Profile | AI/GenAI risk management | Conditional AI governance/security benchmark | https://www.nist.gov/itl/ai-risk-management-framework |
| CURRENT / FRAMEWORK | NIST SP 800-228 Update 1 | API protection | API lifecycle/runtime benchmark | https://csrc.nist.gov/pubs/sp/800/228/upd1/final |
| CURRENT / FRAMEWORK | NIST SP 800-161 Rev.1 | Cybersecurity supply-chain risk | Third-party/supply-chain benchmark | https://csrc.nist.gov/pubs/sp/800/161/r1/final |
| CURRENT / FRAMEWORK | ISO/IEC 27001:2022 / 27002:2022; ISO 22301:2019 | ISMS/security controls and continuity | Supplementary international standards | https://www.iso.org/standard/27001 |
| CURRENT / FRAMEWORK | Basel Principles for Operational Resilience (2021) | Operational resilience | Supervisory benchmark and Critical Services Map reference | https://www.bis.org/bcbs/publ/d516.htm |
| LEGACY | SEOJK No. 21/SEOJK.03/2017 | Historical IT-risk guidance | Repealed when PADK OJK 1/2026 became effective | https://ojk.go.id/id/regulasi/Pages/SEOJK-tentang-Penerapan-Manajemen-Risiko-dalam-Penggunaan-Teknologi-Informasi-Oleh-Bank-Umum.aspx |
| LEGACY / SUPPLEMENTARY | FFIEC Cybersecurity Assessment Tool | Historical benchmark | Sunset by FFIEC in 2025; not a primary current framework | https://www.ffiec.gov/cyberassessmenttool.htm |

## Reference-precision rule

The Excel working paper distinguishes:
- `Validated exact timeline` / `Validated exact statutory clause` — specific clause or deadline directly checked for the release.
- `Section-level / control mapping` — useful supervisory mapping, but exact operative text must be rechecked before formal breach citation.
- `Guidance / benchmark` — non-statutory/international guidance used to strengthen design/testing.

The **Regulatory Calendar** applies the same rule. Deadlines are only stated as exact when directly validated; changing technical/reporting schedules are explicitly marked for revalidation.

## Maintenance rule

Before each formal review, check OJK/BI/JDIH sources for new regulations, amendments, FAQs, reporting instructions, transition rules, holidays affecting working-day deadlines, and supervisory directions that may change scope, deadlines, submission channels, or legal criteria.
