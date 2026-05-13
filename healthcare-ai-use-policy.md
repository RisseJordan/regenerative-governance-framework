# AI Use Policy — Healthcare & Behavioral Health Organizations

**Template version:** 1.0
**Last updated:** May 2026
**Maintained by:** Charisse Jordan / C Jordan Consulting
**Regulatory basis:** HIPAA Privacy Rule, HIPAA Security Rule (proposed updates January 2026), HHS OCR Section 1557 Final Rule (effective July 5, 2024), HHS OCR Dear Colleague Letter on AI Nondiscrimination (January 10, 2025), NIST AI Risk Management Framework

> **How to use this template:** This document is a starting point, not a final policy. Every organization is different. Review each section, adjust for your specific context, size, and tools in use, and have a qualified legal or compliance professional review before you adopt it. Fields marked `[ORGANIZATION]`, `[DATE]`, and `[ROLE]` require your input.

---

## Important notice on regulatory currency

AI governance requirements for healthcare organizations are evolving rapidly. This template reflects guidance current as of May 2026, including:

- HHS OCR proposed HIPAA Security Rule updates (January 2026 — proposed, not yet final)
- HHS OCR Section 1557 nondiscrimination requirements effective July 5, 2024
- HHS OCR Dear Colleague Letter on AI nondiscrimination (January 10, 2025)

Check the [HHS OCR website](https://www.hhs.gov/ocr) and [HHS HIPAA resources](https://www.hhs.gov/hipaa) regularly for updates. This template will be updated as regulations change.

---

## 1. Purpose

This policy establishes how `[ORGANIZATION]` uses artificial intelligence (AI) tools — including AI-powered software, embedded AI features in existing platforms, and generative AI tools — in ways that protect patient privacy, maintain regulatory compliance, and reduce the risk of harm to the people we serve.

AI tools offer real benefits for healthcare organizations. They can reduce administrative burden, support clinical workflows, and improve access to care. They also introduce risks — to patient privacy, to equitable care, and to regulatory compliance — that require active management.

This policy is designed to make AI use at `[ORGANIZATION]` safe, transparent, and accountable. It is not designed to prevent AI adoption. It is designed to make sure that adoption happens thoughtfully.

---

## 2. Scope

This policy applies to:

- All staff, contractors, volunteers, and business associates of `[ORGANIZATION]`
- All AI tools used in any aspect of our work — clinical, administrative, billing, communications, or operations
- AI tools provided by vendors as well as tools staff access independently (e.g. ChatGPT, Microsoft Copilot, Google Gemini)

This policy applies regardless of whether the AI tool was officially adopted by the organization or is being used informally by individual staff members.

---

## 3. Definitions

**Artificial intelligence (AI) tool** — Any software that uses machine learning, large language models, predictive algorithms, or similar technology to generate outputs including text, decisions, recommendations, summaries, or predictions.

**Protected Health Information (PHI)** — Any individually identifiable health information as defined under HIPAA, including patient names, dates of service, diagnoses, treatment records, billing information, and any other information that could identify a patient.

**Electronic Protected Health Information (ePHI)** — PHI that is created, received, maintained, or transmitted in electronic form.

**Patient care decision support tool** — As defined under HHS OCR Section 1557: any automated or non-automated tool, mechanism, method, technology, or combination thereof used to support clinical decision-making in health programs or activities.

**Consequential decision** — Any decision that has a material effect on a patient's access to care, treatment, benefits, or services.

**High-risk AI use** — Any use of an AI tool that touches PHI, influences clinical decisions, or affects patient access to care or services.

---

## 4. Core principles

`[ORGANIZATION]` is committed to using AI in ways that are:

**Safe** — AI tools must not expose patient data, create clinical risk, or result in harm to the people we serve.

**Equitable** — AI tools must not discriminate against patients on the basis of race, color, national origin, sex, age, disability, or any other protected characteristic. This obligation is enforceable under Section 1557 of the Affordable Care Act.

**Transparent** — Patients have a right to know when AI is being used in decisions that affect their care. Staff have a right to understand what AI tools are in use and how to use them appropriately.

**Accountable** — Every AI tool in use at `[ORGANIZATION]` has a designated owner who is responsible for its appropriate use and ongoing review.

**Reversible** — AI-generated outputs in clinical contexts must be subject to human review. No consequential decision about a patient's care should be made by an AI tool without qualified human oversight.

---

## 5. Permitted uses of AI

The following uses of AI are permitted at `[ORGANIZATION]` subject to the safeguards in this policy:

- Administrative tasks that do not involve PHI (e.g. drafting general communications, scheduling non-patient content, internal meeting summaries with no patient information)
- Clinical documentation support where PHI is handled through a HIPAA-compliant, Business Associate Agreement (BAA)-covered platform
- Coding and billing support through approved, BAA-covered platforms
- Summarization of de-identified information for internal operations
- Research and background tasks where no PHI is involved

All permitted uses must be documented in the AI use inventory maintained by `[ROLE/PRIVACY OFFICER]`.

---

## 6. Prohibited uses of AI

The following uses of AI are prohibited at `[ORGANIZATION]`:

- Entering, uploading, or sharing any PHI into any AI tool that does not have a signed Business Associate Agreement (BAA) with `[ORGANIZATION]`. This includes free or consumer versions of tools like ChatGPT, Google Gemini, and similar platforms.
- Using AI to make final clinical decisions without qualified human review and override capability
- Using AI tools to generate content about specific patients for external communications without human review
- Using AI tools that have been identified as producing discriminatory outputs in patient care contexts without first implementing documented mitigation measures
- Using AI tools that process ePHI without documented approval from `[ROLE/PRIVACY OFFICER]` and `[ROLE/SECURITY OFFICER]`
- Using personal accounts on AI platforms for any work-related tasks involving organizational or patient data

---

## 7. PHI and HIPAA compliance requirements

### 7.1 Business Associate Agreements
Any AI tool that creates, receives, maintains, or transmits PHI must be covered by a signed BAA before use. No exceptions.

Staff must not use any AI tool to process PHI unless that tool appears on our approved vendor list and the BAA is in place. If you are unsure whether a BAA exists for a tool you want to use, contact `[ROLE/PRIVACY OFFICER]` before using it.

### 7.2 Minimum necessary standard
When using AI tools that are approved to process PHI, staff must apply the HIPAA minimum necessary standard. Only the PHI strictly necessary for the task at hand should be included in any AI prompt or input.

Do not enter full patient records, complete medical histories, or unnecessary identifying information into an AI tool when a more limited data set would accomplish the same purpose.

### 7.3 AI tools in the technology asset inventory
Consistent with proposed updates to the HIPAA Security Rule (January 2026), `[ORGANIZATION]` will maintain a technology asset inventory that includes all AI tools that create, receive, maintain, or transmit ePHI. This inventory will be reviewed at least quarterly and updated when new tools are adopted or existing tools are modified.

### 7.4 Risk analysis
AI tools that process ePHI are subject to our security risk analysis process. Any new AI tool proposed for use with ePHI must be reviewed for security risk before adoption. Existing tools will be reviewed as part of our annual risk analysis cycle.

---

## 8. Nondiscrimination requirements (Section 1557)

HHS OCR's Section 1557 Final Rule, effective July 5, 2024, prohibits healthcare organizations that receive federal financial assistance from discriminating through their use of patient care decision support tools, including AI.

`[ORGANIZATION]` will:

- Maintain a current list of all AI tools used in clinical decision-making contexts
- Review each tool for known or reasonably foreseeable risks of discriminatory output, including bias in training data, input variables related to protected characteristics, and disparate impact on specific patient populations
- Implement mitigation measures where risks are identified, including staff training and human override protocols
- Establish a process for patients to report concerns about discriminatory AI-influenced decisions
- Ensure that all patient care decision support tools allow qualified staff to override AI-generated outputs

This is not a one-time review. It is an ongoing obligation. `[ROLE]` is responsible for maintaining documentation of this review process and making it available upon request.

---

## 9. Human oversight requirements

No AI tool at `[ORGANIZATION]` makes final consequential decisions about patient care, treatment, benefits, or access to services without qualified human review.

This means:

- AI-generated clinical recommendations must be reviewed by a licensed clinician before acting on them
- AI-generated documentation must be reviewed by the responsible clinician before being incorporated into the medical record
- AI-generated outputs that influence billing, coding, or prior authorization must be reviewed by a qualified staff member before submission
- Any staff member has the authority — and the responsibility — to override an AI-generated output they believe is incorrect, harmful, or inappropriate

Override decisions should be documented and reported to `[ROLE]` so patterns can be identified and addressed.

---

## 10. Staff responsibilities

All staff who use AI tools in their work are responsible for:

- Reading and understanding this policy before using any AI tool for work purposes
- Using only AI tools that appear on the approved vendor list when PHI is involved
- Applying the minimum necessary standard when entering any patient-related information into an AI tool
- Reporting any concern about an AI tool's output — including outputs that seem discriminatory, inaccurate, or harmful — to `[ROLE]`
- Completing AI governance training as required by `[ORGANIZATION]`
- Never sharing login credentials for AI tools with other staff members

---

## 11. Vendor and business associate requirements

Any vendor providing AI-powered tools to `[ORGANIZATION]` that involve PHI must:

- Execute a Business Associate Agreement with `[ORGANIZATION]` before the tool is used
- Provide documentation of their security controls upon request
- Notify `[ORGANIZATION]` of any known security incidents involving PHI within the timeframes required by HIPAA
- Provide information about how their AI tool was trained, including whether training data included PHI, and what steps were taken to address potential bias

`[ORGANIZATION]` will conduct vendor AI due diligence reviews at least annually for any AI vendor with access to PHI.

---

## 12. Incident response

If an AI tool causes or contributes to a potential HIPAA breach, discriminatory outcome, or clinical harm, the following steps apply:

1. The staff member who identifies the issue reports it immediately to `[ROLE/PRIVACY OFFICER]`
2. `[ROLE/PRIVACY OFFICER]` assesses whether a HIPAA breach notification obligation is triggered
3. Use of the AI tool is suspended pending review if the incident involves PHI exposure or clinical harm
4. The incident is documented in the incident log maintained by `[ROLE]`
5. Root cause is identified and corrective action is implemented before the tool is returned to use
6. If the incident involves a pattern of discriminatory output, it is escalated to `[ROLE]` and the tool's use is reviewed under the Section 1557 nondiscrimination framework

---

## 13. Policy governance

**Policy owner:** `[ROLE/PRIVACY OFFICER]`
**Review cycle:** This policy will be reviewed at minimum annually, and updated any time a material change in regulation, technology, or organizational practice requires it.
**Training:** All staff will complete AI governance training within 30 days of hire and annually thereafter. Training completion will be documented.
**Effective date:** `[DATE]`
**Next review date:** `[DATE + 1 YEAR]`

---

## 14. Acknowledgment

By using any AI tool in connection with their work at `[ORGANIZATION]`, staff members acknowledge that they have read, understand, and agree to comply with this policy.

A signed acknowledgment form is required for all staff with access to AI tools that involve PHI. `[ROLE]` maintains signed acknowledgment records.

---

## Regulatory references

- HIPAA Privacy Rule: 45 CFR Part 164, Subpart E
- HIPAA Security Rule: 45 CFR Part 164, Subpart C
- HIPAA Security Rule NPRM: 90 FR 901 (January 6, 2025)
- Section 1557 of the Affordable Care Act Final Rule: 89 FR 37522 (May 6, 2024), effective July 5, 2024
- HHS OCR Dear Colleague Letter on AI Nondiscrimination: January 10, 2025
- NIST AI Risk Management Framework: [https://www.nist.gov/system/files/documents/2023/01/26/AI%20RMF%201.0.pdf](https://www.nist.gov/system/files/documents/2023/01/26/AI%20RMF%201.0.pdf)

---

## Changelog

| Version | Date | Summary of changes |
|---------|------|-------------------|
| 1.0 | May 2026 | Initial release |

---

*This template is provided for educational and operational reference purposes. It does not constitute legal advice. Organizations should consult qualified legal counsel before adopting any compliance policy. Maintained by Charisse Jordan / C Jordan Consulting — [cjordanconsulting.com](https://cjordanconsulting.com)*
