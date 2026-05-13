# AI Incident Response Protocol

**Version:** 1.0
**Last updated:** May 2026
**Maintained by:** Charisse Jordan / C Jordan Consulting
**Regulatory basis:** HIPAA Breach Notification Rule (45 CFR §§ 164.400–414), HIPAA Security Rule (proposed updates January 2026), CFPB enforcement guidance, FERPA, ABA Model Rules of Professional Conduct, NIST AI Risk Management Framework 1.0, Colorado SB 26-189 (passed May 9, 2026)

> **How to use this protocol:** This document is designed to be pulled out and followed under pressure — not just read once and filed away. Keep it somewhere accessible. Review it with your team before you need it. The steps are written to be followed in sequence by the person who identifies the incident, without requiring legal or technical expertise to begin the process.

---

## What is an AI incident

For the purposes of this protocol, an AI incident is any event in which an AI tool used by your organization:

- Exposed, disclosed, or potentially compromised sensitive, regulated, or personally identifiable data
- Produced an output that caused or may have caused harm to an individual — clinical, financial, legal, educational, or reputational
- Produced outputs that appear to reflect discriminatory bias against individuals based on protected characteristics
- Generated inaccurate information that was acted upon in a consequential context (e.g. filed with a court, incorporated into a patient record, used to deny credit)
- Operated outside its intended or approved use — including use of a prohibited tool with regulated data
- Was involved in a security breach or unauthorized access event

**When in doubt, report it.** This protocol is designed for the person who is uncertain whether something constitutes an incident. If you are asking the question, escalate. Let `[ROLE]` make the assessment.

---

## Incident severity levels

Assign a severity level as soon as you have enough information to do so. If you are uncertain, default to the higher level and revise down once more is known.

---

### Severity 1 — Critical

**Characteristics:**
- Regulated data (PHI, ePHI, student PII, financial records, privileged communications) has been disclosed to an unauthorized party or AI platform without a data protection agreement
- An AI tool has produced an output that has directly caused clinical harm, financial loss, or legal jeopardy for an individual
- A security breach has occurred involving AI systems that touch regulated data
- A discriminatory AI output has affected access to care, credit, education, or legal services for an individual

**Response timeline:** Immediate. Escalate within 1 hour of discovery.

**Why this matters:** You must notify authorities of most breaches without reasonable delay and no later than 60 days after discovering the breach. Under proposed 2025 HIPAA updates, this timeline shortens to 30 days. Starting the clock correctly matters.

---

### Severity 2 — Significant

**Characteristics:**
- An AI tool produced an output with significant errors that was delivered to a client, patient, or student — but harm has not yet occurred or is uncertain
- An AI tool was used with regulated data outside its approved scope or without a required data protection agreement — but no confirmed disclosure has occurred
- An AI tool produced outputs suggesting bias against a protected group — but no individual has been concretely harmed
- A staff member used a prohibited AI tool with sensitive data

**Response timeline:** Escalate within 4 hours of discovery.

---

### Severity 3 — Moderate

**Characteristics:**
- An AI tool produced an inaccurate output that was caught before being acted upon
- A staff member used an AI tool outside policy guidelines — but no regulated data was involved and no harm occurred
- An AI tool produced outputs that raised concern but have been contained

**Response timeline:** Escalate within 24 hours of discovery. Document and review.

---

## Step-by-step response protocol

Follow these steps in sequence. Do not wait until you have complete information before beginning.

---

### Step 1 — Stop and contain

**Who:** The person who identifies the incident.
**When:** Immediately upon discovery.

- Stop using the AI tool involved in the incident
- If the incident involves active data exposure, suspend access to the affected tool or system if you have the ability to do so safely — do not delete anything
- Do not attempt to investigate or resolve the incident on your own before reporting
- Do not discuss the incident on unencrypted channels or with parties outside the organization

**Do not:** Delete prompts, outputs, or records related to the incident. Preservation of evidence is essential for investigation and potential regulatory obligations.

---

### Step 2 — Report internally

**Who:** The person who identifies the incident.
**When:** Severity 1 — within 1 hour. Severity 2 — within 4 hours. Severity 3 — within 24 hours.

**Report to:** `[ROLE/PRIVACY OFFICER]` or `[ROLE/COMPLIANCE OFFICER]`
**Contact:** `[phone / email / messaging channel]`
**After hours:** `[after-hours contact method]`

**What to include in your report:**
- What AI tool was involved
- What happened — as specifically as you can describe it
- When you discovered it
- What data may have been involved
- What actions you have already taken
- Your name and contact information

**If you cannot reach `[ROLE]` directly:** Escalate to `[BACKUP ROLE]` at `[contact]`.

---

### Step 3 — Initial assessment

**Who:** `[ROLE/PRIVACY OFFICER]` or `[ROLE/COMPLIANCE OFFICER]`
**When:** Within 2 hours of receiving the report for Severity 1; within 8 hours for Severity 2.

Assess the following:

**Data exposure:**
- What data was involved?
- Is it regulated data (PHI, ePHI, student PII, financial records, privileged communications)?
- Was it disclosed to a third party or AI platform without authorization?
- Does the exposure trigger a breach notification obligation?

**Harm assessment:**
- Has any individual been concretely harmed?
- Is harm ongoing or imminent?
- Has an AI-generated output been acted upon in a consequential context?

**Regulatory obligations:**
- Does this incident trigger HIPAA Breach Notification Rule obligations?
- Does this incident trigger FERPA notification obligations?
- Does this incident require notification to any other regulatory body?
- Does Colorado SB 26-189 apply — is this an automated decision-making incident involving a consequential decision?

**Scope:**
- Is this isolated to one tool, one staff member, one incident?
- Or is there evidence of a pattern — multiple staff members, multiple incidents, systemic misuse?

Document your assessment in the incident log before taking further action.

---

### Step 4 — Suspend the tool

**Who:** `[ROLE/PRIVACY OFFICER]` or `[ROLE/COMPLIANCE OFFICER]`, in coordination with `[ROLE/IT]`
**When:** Immediately for Severity 1. Within 24 hours for Severity 2 if assessment confirms a risk.

Suspend use of the AI tool involved in the incident pending full investigation. This means:

- Notifying all staff who use the tool that it is suspended
- Removing access if technically feasible
- Notifying the vendor if the incident involves their tool or platform

**Do not restore access** to the tool until root cause has been identified and corrective action has been implemented and verified.

---

### Step 5 — Preserve evidence

**Who:** `[ROLE/IT]` in coordination with `[ROLE/PRIVACY OFFICER]`
**When:** As soon as possible — before any systems are modified, updated, or reset.

Preserve:
- Prompts entered into the AI tool, if accessible
- Outputs generated by the tool
- Any documents, records, or communications created using AI-generated content
- Access logs showing who used the tool, when, and what data was accessed
- Vendor communications related to the incident

Evidence must be preserved in a secure location with restricted access. Document the chain of custody.

---

### Step 6 — Determine notification obligations

**Who:** `[ROLE/PRIVACY OFFICER]` and `[ROLE/LEGAL COUNSEL]`
**When:** Within 24 hours of initial assessment for Severity 1.

#### Healthcare organizations — HIPAA
If PHI is disclosed to a third-party AI tool without a Business Associate Agreement in place, or if de-identified information is re-identified by a vendor's AI system, the incident qualifies as a notifiable breach under the HIPAA Breach Notification Rule.

If a HIPAA breach is confirmed or probable:
- Affected individuals must be notified
- HHS OCR must be notified no later than 60 days after discovery (proposed update: 30 days)
- Breaches affecting 500 or more individuals in a state require media notification
- Business associates must notify covered entities of breaches at or by the business associate

Document the four-factor risk assessment used to determine whether the incident constitutes a notifiable breach: the nature and extent of the PHI involved; who accessed or could access it; whether PHI was actually acquired or viewed; and the extent to which risk has been mitigated.

#### Financial services organizations — CFPB and state regulators
- Assess whether the incident triggers any regulatory notification obligations under applicable state or federal financial services law
- Assess whether any consumer has been harmed by an AI-generated adverse action that requires correction or notification
- Consult legal counsel before making any external notification

#### Legal services organizations — State bar obligations
- Assess whether client confidentiality has been breached
- Consult applicable state bar ethics rules on breach notification to clients
- Assess whether any AI-generated work product with errors has been filed with a court and requires correction or withdrawal

#### Education organizations — FERPA
- Assess whether student PII has been disclosed to an unauthorized party
- FERPA does not have a specific breach notification timeline but requires prompt action to mitigate harm
- Consult legal counsel for state-specific student privacy breach notification requirements

#### Colorado organizations — SB 26-189
Colorado SB 26-189, passed May 9, 2026 and expected effective January 1, 2027, requires organizations deploying automated decision-making technology in consequential decisions to provide explanations, correction rights, and human review access to affected individuals. Assess whether any AI-related incident involves a consequential decision affecting a Colorado consumer.

---

### Step 7 — Notify affected individuals and regulators

**Who:** `[ROLE/PRIVACY OFFICER]` or `[ROLE/COMPLIANCE OFFICER]`, in coordination with `[ROLE/LEGAL COUNSEL]`
**When:** Per applicable regulatory timelines determined in Step 6.

All external notifications must be reviewed by `[ROLE/LEGAL COUNSEL]` before being sent.

Notifications to individuals must include, at minimum:
- A description of what happened
- What information was involved
- What steps the organization is taking
- What steps the individual can take to protect themselves
- Contact information for questions

Maintain copies of all notifications sent and the dates they were sent.

---

### Step 8 — Root cause analysis

**Who:** `[ROLE/PRIVACY OFFICER]`, `[ROLE/IT]`, and the staff member's supervisor
**When:** Within 5 business days of containment for Severity 1 and 2.

Identify:
- What specific failure occurred — policy gap, training gap, vendor failure, technical misconfiguration, or human error
- Whether this is an isolated incident or evidence of a pattern
- Whether the AI tool's risk tier was correctly assigned
- Whether the vendor's data protection practices met their contractual obligations
- Whether staff training was adequate to prevent this incident

Document findings in the incident log. Root cause findings must be specific — "staff error" is not sufficient. The question is: what conditions made this error possible, and what would prevent it from recurring?

---

### Step 9 — Corrective action

**Who:** `[ROLE/PRIVACY OFFICER]` in coordination with relevant department leads
**When:** Implementation plan within 10 business days; implementation within 30 days for Severity 1.

Corrective action must address the root cause, not just the symptom. Depending on findings, corrective action may include:

- Updating the AI use policy to address the gap identified
- Revising or adding training for staff — with documented completion
- Adding the tool to a higher risk tier with additional governance requirements
- Requiring additional vendor contractual protections
- Removing the tool from approved use
- Technical controls to prevent recurrence
- Changes to workflow to require human review where it was previously absent

Document all corrective actions taken. Do not restore the suspended AI tool to use until corrective action has been implemented and verified.

---

### Step 10 — Close and learn

**Who:** `[ROLE/PRIVACY OFFICER]`
**When:** After corrective action is implemented and verified.

- Complete the incident log entry with full documentation of the incident, assessment, notifications, root cause, and corrective action
- Brief leadership on the incident and what was done
- Determine whether the incident should be shared (anonymized) in training materials to help staff recognize similar situations in the future
- Schedule a follow-up review 90 days after closure to verify that corrective action is sustained

---

## Incident log template

*Maintain one entry per incident. Store in a secure location accessible to `[ROLE]` and `[ROLE/LEGAL COUNSEL]`.*

---

**Incident ID:** *(assign sequentially: AI-2026-001, AI-2026-002, etc.)*
**Date discovered:**
**Discovered by:**
**Date reported to `[ROLE]`:**
**Severity level assigned:** 1 / 2 / 3
**Revised severity (if applicable):**

**AI tool involved:**
**Vendor:**
**Risk tier of tool at time of incident:**

**Description of incident:**
*(What happened, in plain language)*

**Data involved:**
- Type of data:
- Number of individuals affected (estimated):
- Whether data was confirmed disclosed to unauthorized party: Yes / No / Unknown

**Containment actions taken:**
*(What was done to stop the incident, and when)*

**Evidence preserved:** Yes / No
*(What was preserved and where it is stored)*

**Regulatory assessment:**
- HIPAA breach notification triggered: Yes / No / Under assessment
- Other regulatory notification triggered: Yes / No — specify:
- Date legal counsel notified:

**Notifications sent:**
- Individuals notified: Yes / No — date:
- HHS OCR notified: Yes / No — date:
- Other regulators notified: Yes / No — specify:
- Vendor notified: Yes / No — date:

**Root cause:**
*(Specific finding — not "human error" but what made the error possible)*

**Corrective action:**
*(What was done, by whom, and when)*

**Tool restoration:**
- Tool restored to use: Yes / No
- Date restored:
- Conditions for restoration:

**Incident closed:** Yes / No — date:
**90-day follow-up scheduled:** Yes / No — date:

**Closed by:**

---

## Quick reference — regulatory notification timelines

| Regulation | Trigger | Timeline |
|-----------|---------|----------|
| HIPAA Breach Notification Rule | Breach of unsecured PHI | No later than 60 days after discovery (proposed update: 30 days) |
| HIPAA — breaches 500+ individuals | Breach of unsecured PHI affecting 500+ in a state | Simultaneously with individual notification; also notify media |
| HIPAA — business associate | BA discovers breach | BA must notify covered entity promptly |
| FERPA | Disclosure of student PII | Promptly — no specific federal timeline; state laws may apply |
| CFPB / financial services | Consumer harm from AI output | Consult legal counsel — varies by state and regulation |
| Colorado SB 26-189 (effective Jan 1, 2027) | Consequential decision affecting Colorado consumer | Explanation, correction rights, and human review access required |

---

## Related resources in this repository

- [`/risk-frameworks/ai-risk-tiering-framework.md`](../risk-frameworks/ai-risk-tiering-framework.md) — How tools are tiered by risk
- [`/risk-frameworks/ai-use-inventory-template.md`](../risk-frameworks/ai-use-inventory-template.md) — Tool inventory
- [`/policy-templates`](../policy-templates/) — Sector-specific AI use policies

---

## Changelog

| Version | Date | Summary of changes |
|---------|------|-------------------|
| 1.0 | May 2026 | Initial release |

---

*This protocol is provided for educational and operational reference purposes. It does not constitute legal advice. Organizations should consult qualified legal counsel before making compliance decisions, particularly regarding breach notification obligations. Maintained by Charisse Jordan / C Jordan Consulting — [cjordanconsulting.com](https://cjordanconsulting.com)*
