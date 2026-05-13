# AI Risk Tiering Framework

**Version:** 1.0
**Last updated:** May 2026
**Maintained by:** Charisse Jordan / C Jordan Consulting
**Regulatory basis:** NIST AI Risk Management Framework 1.0 (January 2023), NIST AI 600-1 Generative AI Profile (July 2024), sector-specific regulatory guidance across healthcare, financial services, legal, and education

> **How to use this framework:** This document provides a practical methodology for categorizing AI tools by risk level. Use it during onboarding of new tools, quarterly risk reviews, and when staff raise concerns about a tool in use. It is designed to be applied by operations and compliance staff — not just legal or technical teams.

---

## Why risk tiering matters

Not all AI tools carry the same risk. A tool that drafts internal meeting summaries carries fundamentally different exposure than a tool that influences credit decisions or surfaces patient information. Treating them the same — either prohibiting everything or allowing everything — leaves organizations either unnecessarily constrained or genuinely exposed.

Risk tiering gives organizations a practical way to ask: *what is this tool actually doing, and what does that mean for our obligations?*

The answer determines what governance is required — not whether governance is required at all.

---

## Framework foundation

This tiering framework is grounded in the NIST AI Risk Management Framework (AI RMF 1.0), which organizes AI risk management around four core functions:

- **Govern** — policies, roles, and accountability structures
- **Map** — identifying and categorizing AI risks in context
- **Measure** — evaluating and monitoring risk levels
- **Manage** — responding to, mitigating, and tracking risks

This framework focuses on the **Map** function — providing a practical, plain-language methodology for categorizing AI tools by risk level so that the right governance is applied to each.

The NIST AI RMF defines trustworthiness characteristics that inform risk assessment: validity and reliability, safety, security and resilience, accountability and transparency, explainability, privacy, and fairness with harmful bias managed. This tiering framework operationalizes those characteristics for regulated SMBs.

---

## The three-tier model

### Tier 1 — Standard Use
*Low regulatory and operational risk*

### Tier 2 — Managed Use
*Moderate risk — requires documented oversight*

### Tier 3 — Restricted Use
*High risk — requires formal approval, documented controls, and ongoing monitoring*

---

## Tier definitions and criteria

---

### Tier 1 — Standard Use

**What it means:**
The tool does not process sensitive, regulated, or personally identifiable data. Its outputs do not directly influence consequential decisions about individuals. Errors in its outputs are correctable and carry low harm potential.

**Characteristics of Tier 1 tools:**
- Used for internal, administrative, or general productivity tasks
- No access to patient data, student records, financial records, client information, or other regulated data
- Outputs are reviewed by a human before any action is taken
- Errors are low-consequence and easily identified and corrected
- The tool is used by staff, not surfaced directly to clients, patients, or students

**Examples:**
- AI tools used to draft internal communications or meeting summaries with no sensitive content
- General-purpose AI writing assistants for marketing content or internal documentation
- AI scheduling or calendar tools with no access to sensitive data
- Grammar and editing tools used on non-sensitive documents
- AI tools used for general research on non-client, non-patient topics

**Governance requirements:**
- Must appear on the organization's AI use inventory
- Staff must complete general AI governance training before use
- No special approval required beyond inventory registration
- Annual review as part of standard inventory refresh

---

### Tier 2 — Managed Use

**What it means:**
The tool processes or has access to sensitive data, OR its outputs inform decisions that affect individuals, OR it operates in a client-facing or patient-facing context. Errors or misuse carry meaningful harm potential. Oversight is required but the tool can be used within the organization's existing governance structure.

**Characteristics of Tier 2 tools:**
- Processes or has access to regulated data (PHI, PII, student records, financial data, confidential client information)
- Outputs inform — but do not solely determine — decisions affecting individuals
- Used by staff in regulated workflows (clinical, financial, legal, educational)
- Vendor has signed appropriate data protection agreements
- Human review occurs before outputs are acted upon

**Examples:**
- AI-assisted clinical documentation tools on HIPAA-compliant, BAA-covered platforms
- Legal research AI tools on enterprise platforms with appropriate data protection agreements
- AI-assisted coding and billing tools with regulated data access
- CRM AI features that process client or patient information
- AI writing tools used with de-identified or aggregate data
- Fraud detection tools where human review precedes any action
- AI customer service tools with access to account information
- Learning management system AI features that process student data under a signed data protection agreement

**Governance requirements:**
- Must appear on the organization's AI use inventory with full documentation
- Vendor must be on the approved vendor list with a signed data protection agreement
- Designated staff owner responsible for oversight of the tool
- Staff using the tool must complete tool-specific training before use
- Human review required before outputs are acted upon — documented in workflow
- Quarterly check-in as part of ongoing risk review
- Included in annual risk review with documented findings

---

### Tier 3 — Restricted Use

**What it means:**
The tool makes or substantially influences consequential decisions about individuals, OR it processes highly sensitive regulated data without adequate controls, OR it operates autonomously in a high-stakes context without sufficient human oversight. Errors or misuse carry significant harm potential — regulatory, legal, clinical, or financial.

**Characteristics of Tier 3 tools:**
- Makes or is a substantial factor in decisions with material legal or clinical consequences for individuals
- Processes the highest-sensitivity regulated data (PHI used in clinical decisions, credit decisioning data, IEP records, privileged legal communications)
- Operates with limited or no human review before consequential outputs
- Has the potential to produce discriminatory outcomes at scale
- Regulatory obligations are specific and active (HIPAA Security Rule, ECOA adverse action, FERPA, ABA ethics rules)

**Examples:**
- AI clinical decision support tools that influence diagnosis or treatment
- AI credit underwriting or scoring models used in lending decisions
- AI tools used to make or recommend student placement, advancement, or discipline decisions
- AI tools that process privileged attorney-client communications on unapproved platforms
- AI hiring or screening tools used in employment decisions
- Any AI tool operating without documented human override capability in a consequential decision context
- Consumer AI platforms used with any regulated data (prohibited — not just restricted)

**Governance requirements:**
- Formal approval required from `[ROLE/COMPLIANCE OFFICER]` and `[ROLE/LEADERSHIP]` before deployment
- Vendor must be on the approved vendor list with full due diligence documentation
- Written impact assessment completed before deployment
- Human override capability must be documented and functional
- Dedicated staff owner with specific accountability for the tool
- Staff training required before any use — including scenario-specific training
- Monthly monitoring during initial deployment period; quarterly thereafter
- Included in every quarterly risk review with documented findings
- Incident response protocol specifically covering this tool
- Annual reapproval required — not just review

---

## Risk tiering decision tool

Use these questions to determine the appropriate tier for any AI tool. Start at the top and work down. The first question that applies determines the minimum tier.

---

**Question 1: Does this tool process, access, or receive any of the following?**
- Protected Health Information (PHI) or electronic PHI (ePHI)
- Student education records or student PII
- Financial records, credit data, or consumer financial information
- Confidential client communications or legally privileged information
- Employee records with sensitive personal information

**If yes → minimum Tier 2. Continue to Question 3.**
**If no → continue to Question 2.**

---

**Question 2: Does this tool operate in a client-facing, patient-facing, or student-facing context?**
- Is the tool surfaced directly to clients, patients, or students?
- Do its outputs directly affect how clients, patients, or students experience your organization's services?

**If yes → minimum Tier 2. Continue to Question 3.**
**If no → Tier 1. Document in inventory and apply Tier 1 governance.**

---

**Question 3: Does this tool make or substantially influence consequential decisions?**
- Does it produce outputs that directly determine or heavily influence decisions about an individual's access to care, credit, education, legal services, or employment?
- Could errors in its outputs cause significant harm to an individual — financial, clinical, legal, or educational?
- Does it operate with limited or no human review before outputs are acted upon?

**If yes → Tier 3. Formal approval required before use.**
**If no → Tier 2. Apply Tier 2 governance requirements.**

---

**Question 4 (Tier 2 and above): Does the vendor have appropriate data protection agreements in place?**
- Has the vendor signed a Business Associate Agreement (healthcare), data protection agreement (education/financial), or equivalent contractual data protection terms?
- Has the vendor confirmed that regulated data will not be used to train AI models?

**If no → the tool may not be used with regulated data regardless of tier. Escalate to `[ROLE]` before proceeding.**

---

## Cross-sector risk considerations

The following risk factors increase the tier level of any tool, regardless of its base classification. If any apply, move the tool up at least one tier.

| Risk factor | Why it matters |
|-------------|---------------|
| Tool uses nontraditional data inputs (behavioral, location, social signals) | Increases proxy discrimination risk — relevant to ECOA, Section 1557, Colorado SB 26-189 |
| Tool outputs are used with vulnerable populations (minors, patients in crisis, individuals in financial distress) | Harm potential is amplified — heightened human oversight required |
| Tool has previously produced inaccurate, biased, or harmful outputs | History of errors requires elevated governance regardless of intended use |
| Tool is provided by a vendor with no data breach history documentation | Unknown security posture increases data exposure risk |
| Tool processes data of individuals who did not consent to AI use | Consent and transparency obligations apply |
| Tool operates in a context where regulatory scrutiny is active or anticipated | Audit-readiness requirements apply regardless of tool sophistication |

---

## Generative AI — specific risk considerations

NIST AI 600-1, the Generative AI Profile published in July 2024, defines 12 risk categories unique to or exacerbated by generative AI, including confabulation, data privacy, harmful bias, information integrity, and information security.

For generative AI tools specifically — tools that generate text, documents, summaries, recommendations, or decisions — apply the following additional considerations regardless of tier:

**Confabulation / hallucination risk**
Generative AI tools may produce outputs that appear accurate but are factually incorrect. In regulated contexts — clinical documentation, legal filings, financial disclosures, student records — this carries specific harm and liability exposure. Human verification of factual claims is required in all Tier 2 and Tier 3 contexts.

**Data privacy in prompts**
Text entered into generative AI tools becomes part of the interaction with the model. If that text contains regulated data, data protection requirements apply to the prompt itself — not just to structured data fields.

**Output traceability**
In regulated contexts, it must be possible to trace which AI tool produced which output and when. Generative AI tools used in Tier 2 or Tier 3 contexts must be documented in a way that preserves this traceability.

---

## Tier summary reference

| | **Tier 1 — Standard** | **Tier 2 — Managed** | **Tier 3 — Restricted** |
|---|---|---|---|
| **Data sensitivity** | No regulated data | Regulated data with controls | Highest-sensitivity regulated data |
| **Decision impact** | No consequential decisions | Informs decisions; human review required | Makes or substantially influences consequential decisions |
| **Approval required** | Inventory registration | Inventory + approved vendor list | Formal approval from leadership/compliance |
| **Vendor agreement** | Not required | Required | Required + full due diligence |
| **Human oversight** | Recommended | Required and documented | Required with override capability documented |
| **Training** | General AI governance | Tool-specific training | Scenario-specific training |
| **Review cadence** | Annual | Quarterly + annual | Monthly (initial), quarterly, annual reapproval |

---

## How to use this framework in practice

**When adopting a new tool:**
Run it through the decision tool in Section 5. Assign a tier. Apply the corresponding governance requirements before the tool is used with any regulated data or in any regulated workflow.

**During a quarterly risk review:**
Review all Tier 2 and Tier 3 tools. Confirm vendor agreements are current. Confirm human oversight workflows are functioning. Confirm no incidents have occurred that would change the tier assignment.

**When a staff member raises a concern:**
Apply the cross-sector risk considerations in Section 6. If any apply, escalate the tier and notify `[ROLE]`.

**When a new regulation or enforcement action is published:**
Review all Tier 2 and Tier 3 tools for relevance. Regulatory change is the most common reason to re-tier an existing tool.

---

## Related resources in this repository

- [`/policy-templates`](../policy-templates/) — Sector-specific AI use policies that implement this framework
- [`/assessment-tools/readiness-assessment.md`](../assessment-tools/readiness-assessment.md) — AI Governance Readiness Assessment
- [`/risk-frameworks/ai-use-inventory-template.md`](./ai-use-inventory-template.md) — Template for documenting all AI tools in use

---

## Changelog

| Version | Date | Summary of changes |
|---------|------|-------------------|
| 1.0 | May 2026 | Initial release |

---

*This framework is provided for educational and operational reference purposes. It does not constitute legal advice. Organizations should consult qualified legal counsel before making compliance decisions. Maintained by Charisse Jordan / C Jordan Consulting — [cjordanconsulting.com](https://cjordanconsulting.com)*
