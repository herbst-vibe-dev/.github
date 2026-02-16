# Herbst Group Enterprise

**Clarify. Empower. Elevate.**

Welcome to the Herbst Group GitHub Enterprise. This is our central development environment for all consulting infrastructure, client platforms, and internal tools.

---

## Organisation

| Role | Name |
| --- | --- |
| **CEO** | Dieter Herbst |
| **CTO** | Wimpie du Toit |
| **COO** | Zelna Symms |
| **CAO** | Tiaan Keyser |
| **Head of Data** | Wayne Gray |
| **BI Developer** | Prishen Swaminathan Pillay |
| **Finance** | Malan Munnik |
| **Fractional Admin** | Chantal Davies |

## Repositories

| Repository | Purpose |
| --- | --- |
| `herbstgroup.io` | Primary platform — website, APIs, CKW, Her-Zone, training portal, email, audio |
| `herbst-hub` | Project Chrysalis — Herbst Intelligence Hub |
| `governance-rules` | 37 Claude Code governance rule files, ISO 27001 aligned |
| `herbst-clients` | Client Knowledge Warehouse data files |
| `auto-d` | Conductor v2.0 — Digital avatar and voice interface |
| `dpworld` | DP World commercial transformation engagement |
| `xprocure` | Pharmaceutical order and regret tracking (data-isolated) |
| `herbst-secure-insights` | Secure analytical insights platform |
| `herbst-internal-app` | Internal tooling and utilities |
| `project-poncho` | Multi-tenant SFE and commercial excellence framework |

---

## Formal Policy Register

### ISMS Policies — ISO 27001

| ID | Policy | Version | Status |
| --- | --- | --- | --- |
| `POL-ISMS-001` | Information Security Policy Statement | 1.0 | Draft |
| `POL-ISMS-002` | ISMS Scope | 1.0 | Draft |
| `POL-ISMS-003` | Risk Assessment Methodology | 1.0 | Draft |
| `POL-ISMS-004` | Statement of Applicability | 1.0 | Draft |
| `POL-ISMS-005` | Access Control Policy | 1.0 | Draft |
| `POL-ISMS-006` | Information Security Policy (Acceptable Use) | 2.0 | **Signed** |
| `POL-ISMS-007` | Change Management Policy | 1.0 | Draft |
| `POL-ISMS-008` | Human Resource Security Policy | 1.0 | **Signed** |
| `POL-ISMS-009` | Backup Policy | 1.0 | Draft |
| `POL-ISMS-010` | Employee Code of Conduct | 2.0 | Final |

### ESG Policies — EcoVadis and Sustainability

| ID | Policy | Version | Status |
| --- | --- | --- | --- |
| `POL-ESG-001` | Environmental Policy | 1.1 | **Signed and Distributed** |
| `POL-ESG-002` | Code of Ethics and Anti-Corruption Policy | 1.2 | **Signed and Distributed** |
| `POL-ESG-003` | Health, Safety and Wellbeing Policy | 1.0 | **Signed and Distributed** |
| `POL-ESG-004` | Diversity, Equity, Inclusion and Equal Opportunity Policy | 1.0 | **Signed and Distributed** |
| `POL-ESG-005` | Sustainable Procurement Policy | 1.0 | **Signed and Distributed** |
| `POL-ESG-006` | Corporate Social Responsibility and Sustainability Commitment | 1.0 | **Signed and Distributed** |
| `POL-ESG-007` | Data Privacy and Information Protection Policy | 3.0 | **Signed and Distributed** |
| `POL-ESG-008` | Human Rights Policy | 2.0 | **Signed and Distributed** |
| `POL-ESG-009` | Working Conditions and Employee Welfare Policy | 2.0 | **Signed and Distributed** |
| `POL-ESG-010` | Career Management, Training and Development Policy | 1.0 | **Signed and Distributed** |

### Operational and Security Policies

| ID | Policy | Version | Status |
| --- | --- | --- | --- |
| `POL-AI-VENDOR-001` | AI Vendor Management Policy | 1.0 | Draft |
| `POL-AI-CODE-REVIEW-001` | AI Code Review Policy | 1.0 | Draft |
| `POL-SEC-SECRETS-001` | Secrets Management Policy | 1.0 | Draft |
| `POL-SEC-ENVFILES-001` | Environment File Security Policy | 1.0 | Draft |
| `POL-ENDPOINT-001` | Endpoint Security Policy | 1.0 | Draft |
| `POL-OPS-001` | Meeting Architecture and Productive Work Policy | 1.0 | Draft |

### Other Governance Documents

| Document | Status |
| --- | --- |
| Supplier Code of Conduct (`HG-SUPP-COC-001`) | In Review |

> [!NOTE]
> All policies are signed electronically via DocuSign. Signed PDFs are archived in OneDrive Policy Master and uploaded to Vanta for ISO 27001 evidence.

---

## Security and Compliance

- **ISO 27001:2022** — Pursuing certification. Vanta continuous monitoring active.
- **POPIA** — Compliant. Information Officer registered (No. 2026-001668).
- **EcoVadis** — Rated. All 10 ESG policies signed and distributed.
- **Governance** — 54 critical control codes, 37 rule files, 873+ automated tests.
- **Trust Centre** — [herbstgroup.io/trust](https://herbstgroup.io/trust)

> [!IMPORTANT]
> All API keys are managed via environment variables. Never commit secrets to repositories.

---

## Data Isolation Rules

Client data is strictly contained within its project boundary.

> [!CAUTION]
> Cross-client data usage is **forbidden** without explicit CEO authorisation.

| Dataset | Boundary | Rule |
| --- | --- | --- |
| Xprocure | `xprocure/` | Data stays in project — never used elsewhere |
| Alpha Pharm | `greater-corp-alpha-pharm/` | Data stays in project — never used elsewhere |

---

## Development Standards

| Area | Standard |
| --- | --- |
| **Languages** | TypeScript (primary), Python (analytics scripts) |
| **Frameworks** | Astro (website), Next.js 15 (hub), Tailwind CSS |
| **Database** | Turso (libSQL) — 10 databases, 298 tables |
| **Documents** | DocRaptor (PDF), pptxgenjs (PPTX), npm docx (DOCX) |
| **Email** | Resend only — all emails require CEO approval before sending |
| **CI/CD** | GitHub Actions, Vercel deployments |

---

## Contact

| Purpose | Contact |
| --- | --- |
| **General** | dieter@herbstteam.com |
| **Security** | wimpie@herbstteam.com |

---

*Herbst Group (Pty) Ltd — Waterfall Park, Johannesburg, South Africa*
