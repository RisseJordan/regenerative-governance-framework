# AI Use Inventory Template

**Version:** 1.0
**Last updated:** May 2026
**Maintained by:** Charisse Jordan / C Jordan Consulting

> **How to use this template:** Complete one row per AI tool in active use at your organization. Update this inventory when a new tool is adopted, when an existing tool's use changes significantly, or at minimum quarterly. The inventory is a living document — not a one-time exercise.

---

## Why this inventory matters

You cannot govern what you cannot see.

The AI use inventory is the foundation of every other governance activity — policy enforcement, vendor review, quarterly risk assessments, and audit documentation. Organizations that know exactly what AI tools are in use, by whom, and for what purpose are in a fundamentally different risk position than those operating on assumption.

HHS expects that AI software used to create, receive, maintain, or transmit ePHI would be listed as part of the technology asset inventory. The same principle applies across sectors — regulated organizations need to know where AI touches their operations.

---

## Instructions

**Who completes this:** `[ROLE]` is responsible for maintaining this inventory. Staff are responsible for reporting any AI tool they use for work purposes that does not appear on the inventory.

**How often to update:** Minimum quarterly. Also update when:
- A new AI tool is adopted (add before use with regulated data)
- A tool's use changes significantly (new data, new users, new purpose)
- A vendor updates their terms, data practices, or security posture
- A tool is discontinued or removed from use

**How to use the risk tier:** Use the [AI Risk Tiering Framework](./ai-risk-tiering-framework.md) to assign each tool its tier. The tier determines what governance is required.

---

## Inventory

*Copy and complete one entry per tool. Delete this instruction row before use.*

---

### Tool entry template

**Tool name:**
**Vendor / provider:**
**Version or tier of product (e.g. free, enterprise, API):**
**Date added to inventory:**
**Last reviewed:**

**What the tool does:**
*(Brief plain-language description — what problem does it solve?)*

**Who uses it:**
- [ ] Leadership / executives
- [ ] Administrative staff
- [ ] Clinical or direct service staff
- [ ] IT / technical staff
- [ ] All staff
- [ ] Other: _______________

**What data does it access or process:**
- [ ] No regulated data — general productivity use only
- [ ] Protected Health Information (PHI / ePHI)
- [ ] Student education records / student PII
- [ ] Financial records / consumer financial data
- [ ] Confidential client communications / privileged information
- [ ] Employee records
- [ ] Other sensitive data: _______________

**Does this tool make or influence decisions about individuals:**
- [ ] No — outputs are informational only
- [ ] Yes — outputs inform decisions; human review required before action
- [ ] Yes — outputs directly determine or heavily influence consequential decisions

**Risk tier (from AI Risk Tiering Framework):**
- [ ] Tier 1 — Standard Use
- [ ] Tier 2 — Managed Use
- [ ] Tier 3 — Restricted Use

**Vendor data protection status:**
- [ ] Not required (Tier 1, no regulated data)
- [ ] Data protection agreement signed — date: _______________
- [ ] BAA signed (healthcare) — date: _______________
- [ ] Agreement in progress — expected date: _______________
- [ ] No agreement — tool may not be used with regulated data

**Human oversight workflow:**
*(Describe how human review occurs before AI outputs are acted upon. Required for Tier 2 and Tier 3.)*

**Staff owner / accountable person:**
**Contact:**

**Training status:**
- [ ] General AI governance training required and completed
- [ ] Tool-specific training required and completed
- [ ] Training not yet completed — expected date: _______________

**Approval status:**
- [ ] Tier 1 — inventory registration complete
- [ ] Tier 2 — on approved vendor list, data protection agreement in place
- [ ] Tier 3 — formal approval from `[ROLE/COMPLIANCE OFFICER]` and `[ROLE/LEADERSHIP]` on: _______________

**Known risks or concerns:**
*(Note any known issues with accuracy, bias, security, or regulatory exposure)*

**Incident history:**
*(Note any incidents involving this tool — date, nature, resolution)*

**Next review date:**

---

## Completed inventory entries

*Add completed entries below. One section per tool.*

---

### Example entry — for reference only, delete before use

**Tool name:** Microsoft Copilot (M365)
**Vendor / provider:** Microsoft
**Version or tier of product:** Microsoft 365 Business Standard with Copilot add-on
**Date added to inventory:** January 2026
**Last reviewed:** April 2026

**What the tool does:**
AI assistant integrated into Microsoft 365 applications — drafts emails, summarizes documents, assists with Excel, generates meeting summaries in Teams.

**Who uses it:** All staff

**What data does it access or process:**
- [x] No regulated data — general productivity use only *(administrative staff)*
- [x] Confidential client communications *(attorneys and paralegals — enterprise agreement required)*

**Does this tool make or influence decisions about individuals:**
- [x] No — outputs are informational only *(for most use cases)*
- [x] Yes — outputs inform decisions; human review required before action *(for legal drafting and client communications)*

**Risk tier:** Tier 2 — Managed Use *(where used with client data)*

**Vendor data protection status:**
- [x] Data protection agreement signed — date: November 2025
*(Microsoft 365 enterprise agreement includes DPA; BAA executed for healthcare contexts)*

**Human oversight workflow:**
All AI-generated drafts reviewed and edited by the responsible attorney or staff member before sending. No AI-generated document delivered to a client without human review.

**Staff owner / accountable person:** [IT Director / Operations Lead]
**Contact:** [email]

**Training status:**
- [x] General AI governance training required and completed
- [x] Tool-specific training required and completed

**Approval status:**
- [x] Tier 2 — on approved vendor list, data protection agreement in place

**Known risks or concerns:**
Copilot features may surface information across organizational boundaries if access controls are not properly configured. IT has reviewed and confirmed access is scoped appropriately.

**Incident history:** None to date.

**Next review date:** July 2026

---

## Inventory summary

*Update this summary each time the inventory is reviewed.*

**Last full review date:**
**Conducted by:**
**Total tools inventoried:**
**Tier 1 tools:**
**Tier 2 tools:**
**Tier 3 tools:**
**Tools pending vendor agreement:**
**Tools pending approval:**
**Tools flagged for concern:**

**Summary of changes since last review:**

**Next scheduled review:**

---

## Vendor agreement tracker

*Track the status of data protection agreements for all Tier 2 and Tier 3 tools.*

| Tool name | Vendor | Agreement type | Status | Date signed | Renewal date | Owner |
|-----------|--------|---------------|--------|-------------|--------------|-------|
| | | BAA / DPA / Other | Signed / Pending / Not started | | | |
| | | | | | | |

---

## Staff reporting process

Any staff member who becomes aware of an AI tool being used at `[ORGANIZATION]` that does not appear in this inventory should report it to `[ROLE]` immediately.

This includes:
- Tools adopted informally by individual staff or departments
- AI features that have been added to existing software
- Tools used by contractors or vendors on behalf of the organization

Reporting is not punitive — it is how the organization maintains an accurate picture of its AI use. The goal is visibility, not surveillance.

**To report an unregistered tool:** [Contact method / email / internal form]

---

## Related resources in this repository

- [`/risk-frameworks/ai-risk-tiering-framework.md`](./ai-risk-tiering-framework.md) — How to assign risk tiers
- [`/policy-templates`](../policy-templates/) — Sector-specific AI use policies
- [`/assessment-tools/readiness-assessment.md`](../assessment-tools/readiness-assessment.md) — AI Governance Readiness Assessment

---

## Changelog

| Version | Date | Summary of changes |
|---------|------|-------------------|
| 1.0 | May 2026 | Initial release |

---

*This template is provided for educational and operational reference purposes. It does not constitute legal advice. Organizations should consult qualified legal counsel before making compliance decisions. Maintained by Charisse Jordan / C Jordan Consulting — [cjordanconsulting.com](https://cjordanconsulting.com)*
