# Regulatory Resources & Reference Materials

**Version:** 1.0
**Last updated:** May 2026
**Maintained by:** Charisse Jordan / C Jordan Consulting

> **How to use this file:** This is a curated, annotated reference library — not an exhaustive list. Every resource here has been selected because it is directly useful for small and midsize regulated organizations building or maintaining AI governance. Each entry includes plain-language notes on what it is, why it matters, and when to use it.

**Note on currency:** AI governance guidance is being issued and updated continuously across all sectors. Check each source directly for the most current version. This file is updated as part of the repository's regular maintenance cycle.

---

## Section 1 — Cross-sector frameworks

These resources apply across industries. Start here if you are new to AI governance or need a foundational framework.

---

### NIST AI Risk Management Framework (AI RMF 1.0)

**Source:** National Institute of Standards and Technology (NIST)
**URL:** [https://www.nist.gov/itl/ai-risk-management-framework](https://www.nist.gov/itl/ai-risk-management-framework)
**Direct PDF:** [https://nvlpubs.nist.gov/nistpubs/ai/nist.ai.100-1.pdf](https://nvlpubs.nist.gov/nistpubs/ai/nist.ai.100-1.pdf)
**Published:** January 26, 2023 | **Under revision as of May 2026 — AI RMF 1.1 forthcoming**

**What it is:**
The foundational voluntary framework for AI risk management in the United States. Organized around four core functions: Govern, Map, Measure, and Manage. Sector-agnostic and use-case agnostic — designed for organizations of all sizes.

**Why it matters:**
Aligning with NIST AI RMF is referenced as an affirmative defense under Colorado SB 26-189 and is cited across federal agency guidance for healthcare, financial services, and education. It is the closest thing to a universal baseline for AI governance in the U.S.

**When to use it:**
When building your governance program from scratch. When a client, auditor, or regulator asks what framework you are using. When assessing a vendor's AI governance practices.

**Plain-language note:**
The framework does not tell you exactly what to do — it tells you how to think about AI risk management. The Playbook (linked below) is more practical for implementation.

---

### NIST AI RMF Playbook

**Source:** NIST AI Resource Center
**URL:** [https://airc.nist.gov/](https://airc.nist.gov/)
**Published:** 2023 | **Under revision — will be updated after AI RMF 1.1 is published**

**What it is:**
Suggested actions and documentation practices that help organizations achieve the outcomes described in the AI RMF. More operationally specific than the framework itself.

**When to use it:**
When translating the AI RMF into practical governance steps. More useful than the framework document alone for most SMBs.

---

### NIST AI 600-1 — Generative AI Profile

**Source:** NIST
**URL:** [https://airc.nist.gov/technical-reports/](https://airc.nist.gov/technical-reports/)
**Published:** July 26, 2024

**What it is:**
A companion profile to AI RMF 1.0 specifically addressing generative AI. Defines risk categories unique to generative AI — including confabulation, data privacy in prompts, harmful bias, information integrity, and information security — and provides suggested actions.

**Why it matters:**
Most AI tools used by regulated SMBs today are generative AI tools — ChatGPT, Copilot, Gemini. This profile addresses the specific risks those tools introduce that the base framework did not fully anticipate.

**When to use it:**
When assessing or governing any generative AI tool. When staff ask why a free-tier AI tool is prohibited for use with regulated data.

---

### NIST AI Resource Center (AIRC)

**Source:** NIST
**URL:** [https://airc.nist.gov/](https://airc.nist.gov/)

**What it is:**
NIST's central hub for AI risk management resources — the framework, playbook, profiles, use cases, and crosswalks to other frameworks. Updated as new guidance is published.

**When to use it:**
As your primary reference point for NIST AI governance resources. Check here before searching elsewhere.

---

## Section 2 — Healthcare: HIPAA and HHS guidance

---

### HHS HIPAA resources for AI

**Source:** U.S. Department of Health and Human Services
**URL:** [https://www.hhs.gov/hipaa/for-professionals/index.html](https://www.hhs.gov/hipaa/for-professionals/index.html)

**What it is:**
HHS's central HIPAA resource hub — Privacy Rule, Security Rule, Breach Notification Rule, enforcement actions, and guidance documents. The authoritative source for all HIPAA compliance questions.

**When to use it:**
When verifying what HIPAA requires. When reviewing breach notification obligations. When preparing for or responding to a compliance inquiry.

---

### HIPAA Security Rule NPRM — Proposed Updates for AI and ePHI

**Source:** HHS Office for Civil Rights (OCR)
**URL:** [https://www.hhs.gov/hipaa/for-professionals/security/hipaa-security-rule-nprm/factsheet/index.html](https://www.hhs.gov/hipaa/for-professionals/security/hipaa-security-rule-nprm/factsheet/index.html)
**Published:** December 27, 2024 | **Proposed — not yet final as of May 2026**

**What it is:**
The first proposed major update to the HIPAA Security Rule in over 20 years. Removes the distinction between required and addressable safeguards, mandates technology asset inventories that include AI tools, and introduces stricter cybersecurity expectations for ePHI.

**Why it matters:**
When finalized, this rule will require healthcare organizations to explicitly include AI tools that touch ePHI in their technology asset inventories and risk analysis. Organizations should prepare now.

**Plain-language note:**
This is proposed — not yet final. Monitor HHS for the final rule and effective date.

---

### HHS OCR Dear Colleague Letter on AI Nondiscrimination

**Source:** HHS Office for Civil Rights
**URL:** [https://www.hhs.gov/civil-rights/for-individuals/section-1557/index.html](https://www.hhs.gov/civil-rights/for-individuals/section-1557/index.html)
**Published:** January 10, 2025

**What it is:**
A Dear Colleague letter from HHS OCR confirming that Section 1557 of the Affordable Care Act applies to AI-powered patient care decision support tools. Requires covered healthcare organizations to identify and mitigate risks of AI-driven discrimination.

**Why it matters:**
Effective July 5, 2024, healthcare organizations using patient care decision support tools — including AI — are subject to Section 1557 nondiscrimination requirements. This letter clarifies what that means in practice.

**When to use it:**
When reviewing AI tools used in clinical decision-making. When training clinical staff on AI governance. When auditing patient care decision support tools for bias.

---

### HHS Breach Notification Rule

**Source:** HHS
**URL:** [https://www.hhs.gov/hipaa/for-professionals/breach-notification/index.html](https://www.hhs.gov/hipaa/for-professionals/breach-notification/index.html)

**What it is:**
The rules governing when and how healthcare organizations must notify individuals, HHS, and media following a breach of unsecured PHI. Current timeline: no later than 60 days after discovery. Proposed update: 30 days.

**When to use it:**
Any time an AI incident may involve PHI exposure. During incident response Step 6 — determining notification obligations.

---

## Section 3 — Financial services: CFPB and fair lending

---

### CFPB Advanced Technology Resources

**Source:** Consumer Financial Protection Bureau
**URL:** [https://www.consumerfinance.gov/rules-policy/advanced-technology/](https://www.consumerfinance.gov/rules-policy/advanced-technology/)

**What it is:**
CFPB's central resource page for AI and advanced technology guidance — including circulars on adverse action notification requirements for AI-based credit decisions, commentary on fair lending and algorithmic bias, and enforcement actions.

**When to use it:**
When reviewing AI tools used in credit decisioning. When building or reviewing adverse action notification processes. Bookmark and check regularly — CFPB updates this page as new guidance is issued.

---

### CFPB Circular 2022-03: Adverse Action Notifications and Complex Algorithms

**Source:** CFPB
**URL:** [https://www.consumerfinance.gov/compliance/supervisory-guidance/circular-2022-03-adverse-action-notification-requirements-in-connection-with-credit-decisions-based-on-complex-algorithms/](https://www.consumerfinance.gov/compliance/supervisory-guidance/circular-2022-03-adverse-action-notification-requirements-in-connection-with-credit-decisions-based-on-complex-algorithms/)
**Published:** 2022

**What it is:**
CFPB guidance confirming that creditors must comply with ECOA and Regulation B adverse action notification requirements even when complex algorithms or AI make credit decisions. Creditors cannot use "black box" as an excuse for vague adverse action notices.

**Why it matters:**
This is the foundational CFPB position on AI and adverse action. Every financial services organization using AI in credit decisions needs to understand this.

---

### CFPB Circular 2023-03: Specific Reasons for Adverse Action Using AI

**Source:** CFPB
**URL:** [https://www.consumerfinance.gov/compliance/supervisory-guidance/cfpb-circular-2023-03/](https://www.consumerfinance.gov/compliance/supervisory-guidance/cfpb-circular-2023-03/)
**Published:** 2023

**What it is:**
Extends CFPB 2022-03 with additional specificity — creditors must provide precise, specific reasons for AI-driven adverse actions. Generic checklist reasons are not sufficient if they do not reflect the actual factors the AI model weighted.

---

### CFPB Comment on AI in Financial Services (August 2024)

**Source:** CFPB
**URL:** [https://www.consumerfinance.gov/about-us/newsroom/cfpb-comment-on-request-for-information-on-uses-opportunities-and-risks-of-artificial-intelligence-in-the-financial-services-sector/](https://www.consumerfinance.gov/about-us/newsroom/cfpb-comment-on-request-for-information-on-uses-opportunities-and-risks-of-artificial-intelligence-in-the-financial-services-sector/)
**Published:** August 12, 2024

**What it is:**
The CFPB's most comprehensive statement on AI in financial services, issued in response to a Treasury Department RFI. Confirms that existing consumer financial protection laws apply fully to AI — with no exceptions for new technologies.

**Key quote:** "There are no exceptions to the federal consumer financial protection laws for new technologies."

**When to use it:**
When a vendor or staff member suggests that AI tools operate in a different regulatory space than traditional tools. When educating leadership on AI compliance obligations.

---

## Section 4 — Legal services: ABA ethics guidance

---

### ABA Formal Opinion 512 — Generative AI Tools

**Source:** American Bar Association
**URL:** [https://www.americanbar.org/groups/professional_responsibility/publications/model_rules_of_professional_conduct/](https://www.americanbar.org/groups/professional_responsibility/publications/model_rules_of_professional_conduct/)
**Published:** July 29, 2024

**What it is:**
The ABA's first formal ethics opinion on generative AI in legal practice. Addresses how Model Rules 1.1 (competence), 1.4 (communication), 1.5 (fees), 1.6 (confidentiality), and 5.3 (supervision) apply to AI tools. The foundational national reference for legal AI governance.

**When to use it:**
When building or reviewing an AI governance policy for a legal services organization. When training attorneys and staff on AI ethics obligations.

**Plain-language note:**
Your state bar may have issued its own opinion that adds to or differs from ABA Formal Opinion 512. Always check your state bar's guidance alongside this.

---

### ABA Task Force on Law and Artificial Intelligence

**Source:** American Bar Association
**URL:** [https://www.americanbar.org/groups/law_and_artificial_intelligence/](https://www.americanbar.org/groups/law_and_artificial_intelligence/)

**What it is:**
The ABA's ongoing work on AI and legal practice — including the Year Two Report (2025) and continuing guidance on AI ethics, competence, and governance in law firms.

**When to use it:**
For current developments in legal AI ethics. Check annually for updated guidance.

---

### State bar AI ethics opinions — finding yours

**What to search for:**
Search your state bar's website for "artificial intelligence ethics opinion" or "formal opinion AI." As of May 2026, more than half of U.S. state bars have issued or are developing AI ethics guidance.

**Notable published opinions:**
- Florida Bar Advisory Opinion 24-1 (January 2024)
- North Carolina Bar 2024 Formal Ethics Opinion 1
- Check your state bar for jurisdiction-specific guidance

---

## Section 5 — Education: FERPA and student privacy

---

### Student Privacy Policy Office — FERPA Resources

**Source:** U.S. Department of Education
**URL:** [https://studentprivacy.ed.gov/ferpa](https://studentprivacy.ed.gov/ferpa)

**What it is:**
The Department of Education's central FERPA resource — regulations, guidance documents, FAQs, and policy interpretations. The authoritative source for all FERPA compliance questions.

**When to use it:**
When verifying what FERPA requires. When reviewing AI vendor data practices. When responding to a student or parent inquiry about data rights.

---

### Student Privacy Compass — AI in Education

**Source:** Student Privacy Policy Office
**URL:** [https://studentprivacy.ed.gov](https://studentprivacy.ed.gov)

**What it is:**
The Student Privacy Policy Office's resource hub — including guidance on AI and generative AI tools in educational settings, FERPA compliance resources, and state-level AI guidance tracking.

**When to use it:**
When vetting AI tools for use in educational contexts. When reviewing state-level student privacy requirements.

---

### Future of Privacy Forum — Vetting Generative AI Tools for Schools

**Source:** Future of Privacy Forum
**URL:** [https://fpf.org/](https://fpf.org/)
**Published:** April 2024

**What it is:**
A practical guide for reviewing generative AI tools for FERPA compliance — what questions to ask vendors, how to assess data use terms, and what to look for in a student data protection agreement.

**Why it matters:**
One of the most practical resources available for educational organizations evaluating AI tools. Plain language, actionable, and grounded in real vendor review experience.

**When to use it:**
During vendor vetting for any AI tool that will be used with students or student data.

---

## Section 6 — Colorado state law

---

### Colorado SB 26-189 — Rewritten AI Law (May 2026)

**Source:** Colorado General Assembly
**URL:** [https://leg.colorado.gov/bills/sb26-189](https://leg.colorado.gov/bills/sb26-189)
**Status:** Passed May 9, 2026 — awaiting governor's signature — expected effective January 1, 2027

**What it is:**
Colorado's rewritten AI consumer protection law. Replaces the original SB 24-205. Focuses on "covered automated decision-making technology" (ADMT) that processes personal data used to materially influence consequential decisions in employment, housing, lending, insurance, healthcare, education, and legal services. Requires consumer disclosures, adverse-outcome explanations, correction rights, and human review access. Eliminates the exemptions that previously applied to some federally regulated entities.

**Why it matters:**
Applies to organizations operating in Colorado across all four sectors covered by this repository. Affected organizations should begin preparing compliance programs now ahead of the January 1, 2027 effective date.

**Plain-language note:**
The original SB 24-205 has been replaced. References to SB 24-205 in older resources are outdated. Use SB 26-189 as the current Colorado AI law.

---

### Colorado Attorney General — AI Resources

**Source:** Colorado Attorney General's Office
**URL:** [https://coag.gov/](https://coag.gov/)

**What it is:**
The Colorado AG has exclusive enforcement authority under SB 26-189. The AG's office will conduct rulemaking (mandatory under SB 26-189, to be completed by January 1, 2027). Monitor this page for rulemaking updates and compliance guidance.

---

### Original SB 24-205 — For Historical Reference Only

**Source:** Colorado General Assembly
**URL:** [https://leg.colorado.gov/bills/sb24-205](https://leg.colorado.gov/bills/sb24-205)
**Status:** Replaced by SB 26-189 as of May 2026

**Plain-language note:**
Included here for reference only. SB 24-205 has been replaced. Do not use this as the basis for current compliance planning.

---

## Section 7 — Staying current

AI governance guidance is issued and updated continuously. These resources help you track what is changing.

---

### NIST AI Resource Center — New Releases

**URL:** [https://airc.nist.gov/](https://airc.nist.gov/)

Check for new profiles, playbook updates, and companion resources as they are published. AI RMF 1.1 is forthcoming.

---

### CFPB Newsroom — Advanced Technology

**URL:** [https://www.consumerfinance.gov/about-us/newsroom/](https://www.consumerfinance.gov/about-us/newsroom/)

Filter for "artificial intelligence" or "advanced technology" to track new CFPB guidance, enforcement actions, and circulars.

---

### HHS OCR Newsroom

**URL:** [https://www.hhs.gov/ocr/newsroom/index.html](https://www.hhs.gov/ocr/newsroom/index.html)

Monitor for new HIPAA enforcement actions, guidance documents, and AI-related updates.

---

### Student Privacy Policy Office — News and Updates

**URL:** [https://studentprivacy.ed.gov/](https://studentprivacy.ed.gov/)

Monitor for FERPA guidance updates, new Dear Colleague letters, and edtech-related guidance.

---

### AI Incident Database

**Source:** Partnership on AI
**URL:** [https://incidentdatabase.ai/](https://incidentdatabase.ai/)

**What it is:**
A public database of documented AI incidents across industries. Useful for understanding what types of AI failures have occurred in regulated sectors and how organizations responded.

**When to use it:**
When training staff on real-world AI risk. When identifying patterns that may be relevant to your organization's tool use. When building incident response scenarios for tabletop exercises.

---

## Section 8 — How this repository is maintained

The Regenerative Governance Framework™ repository is maintained by Charisse Jordan. Resources in this file are verified against primary sources before inclusion and reviewed as part of the repository's regular maintenance cycle.

If you identify a resource that should be included, an outdated link, or a regulatory development that affects the guidance in this repository, open an issue or reach out directly.

**[cjordanconsulting.com/ai-governance-framework](https://cjordanconsulting.com/ai-governance-framework)**
**[LinkedIn](https://linkedin.com/in/charissejordan)**

---

## Changelog

| Version | Date | Summary of changes |
|---------|------|-------------------|
| 1.0 | May 2026 | Initial release — includes NIST AI RMF, HHS/HIPAA, CFPB, ABA, FERPA, and Colorado SB 26-189 resources |

---

*This resource list is provided for educational and operational reference purposes. It does not constitute legal advice. Maintained by Charisse Jordan / C Jordan Consulting — [cjordanconsulting.com](https://cjordanconsulting.com)*
