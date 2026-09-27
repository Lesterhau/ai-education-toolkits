# AI Vendor Procurement Clauses for Education

**A jurisdiction-neutral clause library for RFPs, tenders, pilots, contracts, and renewals**

These clauses are designed to make the [Minimum Safeguards Before Deploying AI in Education](MINIMUM-SAFEGUARDS.md) enforceable through procurement. They are a drafting aid, not legal advice. Buyers should adapt them to local law, bargaining power, risk level, and the specific service.

Use the bracketed fields as placeholders.

---

## How to use this library

For a low-risk tool, select the clauses relevant to the deployment.

For a system that can affect admission, placement, grading, discipline, financial support, disability accommodation, academic progression, employment, credentialing, or access to services, treat the clauses marked **High-risk minimum** as presumptively required.

Do not accept a vendor's general trust center, marketing page, or privacy policy as a substitute for a contractual commitment where the requirement matters to the institution.

---

## 1. AI system disclosure

**High-risk minimum**

> The Supplier shall disclose all artificial intelligence, machine-learning, generative-AI, automated-decision, ranking, recommendation, classification, or predictive components materially used in delivering the Service. The disclosure shall identify the function performed by each component and whether the component is developed by the Supplier or provided by a third party.

The Supplier shall update this disclosure before introducing a materially new AI component into the Service.

**Evidence to request:** architecture summary; list of model providers and material AI subprocessors.

---

## 2. Model and version inventory

**High-risk minimum**

> For AI components used in consequential workflows, the Supplier shall maintain a current record of the model provider, model or model family, version or release identifier where available, material configuration, deployment date, and known evaluation results relevant to the contracted use.

Where a provider does not expose a stable model version, the Supplier shall document how material model changes are detected and governed.

**Evidence to request:** model inventory; version/change log.

---

## 3. Approved purpose and prohibited secondary use

**High-risk minimum**

> The Supplier shall use AI components and Institution Data only for the purposes expressly described in the Agreement. The Supplier shall not repurpose Institution Data, learner interactions, outputs, metadata, behavioral data, or derived profiles for unrelated commercial, advertising, surveillance, profiling, or product-development purposes except where separately and expressly authorized in writing by the Institution and permitted by applicable law.

---

## 4. Training and model-improvement use of institutional data

**High-risk minimum**

Choose the formulation that matches institutional policy.

**No-training default**

> The Supplier shall not use Institution Data, student or staff prompts, uploaded materials, student work, assessments, feedback, outputs, or interaction metadata to train, fine-tune, evaluate, improve, or otherwise develop a general-purpose or third-party model, except to the minimum extent technically necessary to provide the contracted Service and only where expressly authorized in writing by the Institution.

**Opt-in alternative**

> Any use of Institution Data for model training or product improvement requires separate, affirmative, documented authorization describing the data, purpose, model, retention period, and parties receiving the data. Silence, continued use, or acceptance of general terms shall not constitute consent.

---

## 5. Data minimization

> The Supplier shall collect, access, process, transmit, and retain only data reasonably necessary to provide the approved Service. Upon request, the Supplier shall identify the data fields collected, their purpose, source, recipients, retention period, and deletion method.

The Institution may require removal of a data field whose necessity cannot be demonstrated.

---

## 6. Sensitive learner data

**High-risk minimum**

> The Supplier shall apply heightened protections to disability, health, counseling, biometric, disciplinary, immigration, financial, child-safety, and other sensitive learner information. Sensitive data shall not be exposed to a model, subprocessor, or employee unless necessary for an approved purpose and authorized under the Agreement and applicable law.

The Supplier shall identify any AI feature that infers sensitive characteristics not directly provided by the user.

---

## 7. Subprocessors and model providers

> The Supplier shall maintain a current list of material subprocessors and external model providers that may receive Institution Data or materially affect AI outputs. The Supplier shall provide [30] days' advance notice of a material addition or replacement where practicable and shall remain responsible for contractual obligations performed by its subprocessors.

The Institution may object to a proposed subprocessor on documented privacy, security, accessibility, safety, or legal grounds.

---

## 8. Human authority over consequential decisions

**High-risk minimum**

> The Service shall not make a final adverse consequential decision about a learner or employee unless such use is expressly authorized in the Agreement. Where AI informs a consequential decision, a qualified human decision-maker shall retain authority to review, disagree with, override, and correct the AI-supported result.

The Supplier shall provide enough information for that review to be meaningful rather than ceremonial.

---

## 9. Contestability and explanation

**High-risk minimum**

> The Supplier shall support the Institution in providing affected individuals with a practical process to challenge a materially adverse AI-influenced outcome. For consequential workflows, the Service shall preserve or provide the information reasonably necessary to explain the factors, inputs, rules, or evidence materially contributing to the output, subject to lawful protection of security and intellectual property.

The Supplier shall not design the system so that human review is technically impossible.

---

## 10. Accessibility

**High-risk minimum for student-facing systems**

> The Supplier shall design and maintain student- and staff-facing components to meet the accessibility standard specified by the Institution, including [WCAG version/level or applicable local standard]. The Supplier shall provide current accessibility conformance documentation and shall remediate material accessibility defects within agreed timelines.

The Supplier shall notify the Institution of known accessibility limitations that materially affect use of the Service.

---

## 11. Age-appropriate and child-safety controls

**High-risk minimum for minors**

> Where the Service is available to children, the Supplier shall document age-appropriate safety controls addressing harmful content, manipulation, anthropomorphic or relational design, privacy, inappropriate data collection, and escalation to human support where applicable.

The Supplier shall not intentionally use engagement optimization intended to foster emotional dependency or unnecessary continued interaction by minors.

---

## 12. Evaluation and subgroup performance

**High-risk minimum**

> Before production use in a consequential workflow, the Supplier shall provide evidence reasonably sufficient to evaluate performance for the intended context. Where relevant and lawful, that evidence shall include error rates, known limitations, false-positive and false-negative behavior, and materially different performance across affected populations, languages, dialects, accessibility needs, or other relevant groups.

Aggregate accuracy alone shall not satisfy this requirement where subgroup failures could materially harm individuals.

---

## 13. Unsupported capability claims

> The Supplier warrants that material claims made to the Institution concerning the Service's accuracy, capability, safety, educational effectiveness, or compliance are supported by evidence appropriate to the claim and deployment context.

The Supplier shall promptly correct a representation that it learns is materially inaccurate or no longer current.

---

## 14. Security and AI-specific misuse testing

**High-risk minimum**

> The Supplier shall maintain security controls proportionate to the Service and shall assess reasonably foreseeable AI-specific misuse and failure modes, including unauthorized data disclosure, prompt injection, cross-user data exposure, excessive tool permissions, harmful automated actions, and circumvention of safety controls where relevant to the architecture.

The Supplier shall provide a process for reporting suspected security or AI-safety vulnerabilities.

---

## 15. AI incident notification

**High-risk minimum**

> The Supplier shall notify the Institution without undue delay, and no later than [X hours/days] after confirmation, of an AI Incident materially affecting the Institution or its users.

An **AI Incident** includes, as applicable: unauthorized disclosure or action; material privacy or security failure; discriminatory or systematically erroneous outcomes; harmful output causing or reasonably capable of causing material harm; failure of required human-control mechanisms; or a material breach of an AI-specific contractual safeguard.

The Supplier shall preserve relevant evidence, cooperate with investigation and remediation, and provide a written post-incident summary when requested.

---

## 16. Emergency suspension

**High-risk minimum**

> The Institution may immediately suspend an AI feature, integration, model, or consequential workflow where it reasonably determines that continued operation presents a material safety, privacy, security, accessibility, legal, or educational risk.

The Supplier shall provide a practicable mechanism to disable or isolate the affected functionality without unnecessarily terminating unrelated essential services.

---

## 17. Material model and service changes

**High-risk minimum**

> The Supplier shall notify the Institution before a material change that could reasonably alter risk, functionality, data use, output behavior, model capability, accessibility, safety controls, or consequential-decision performance, where advance notice is technically and commercially practicable.

For material changes to consequential workflows, the Institution may require re-evaluation before continued production use.

Examples include:
- replacement of the underlying model or model family;
- material changes to training or data-use practices;
- addition of autonomous tool use or external actions;
- removal or weakening of a safety control;
- significant changes to retention or subprocessors;
- changes likely to alter measured performance.

---

## 18. Monitoring and drift

**High-risk minimum**

> The Supplier shall maintain post-deployment monitoring appropriate to the contracted use and shall notify the Institution of known material degradation, drift, recurring failure patterns, or newly discovered limitations relevant to the Institution's use.

Where the Institution supplies documented incident or appeal data, the Supplier shall provide a process to incorporate that evidence into investigation and remediation.

---

## 19. Logs and audit evidence

**High-risk minimum**

> The Service shall maintain audit records reasonably sufficient to investigate consequential outputs and material incidents, subject to privacy and security requirements. Records should identify, where applicable, the relevant system/model version, time, material input provenance, output or decision, human intervention, and subsequent correction or appeal.

Retention periods shall be agreed in writing and shall not exceed legitimate operational, legal, or safety needs without justification.

---

## 20. Independent assessment

> For deployments designated high-risk by the Institution, the Supplier shall cooperate with reasonable independent testing, audit, red-team, accessibility, privacy, or impact-assessment activities subject to appropriate confidentiality and security controls.

Where direct model access cannot be provided, the Supplier shall propose an alternative that allows meaningful evaluation rather than relying solely on self-attestation.

---

## 21. Evidence portability

> Upon request and at contract end, the Supplier shall provide the Institution with exportable copies of institutional records reasonably necessary for continuity, audit, appeals, and legal obligations in a commonly usable format.

The Supplier shall document dependencies that would materially impede migration to another provider or non-AI process.

---

## 22. Data return and deletion at exit

**High-risk minimum**

> Upon termination or expiration, the Supplier shall return or make available agreed Institution Data and then securely delete remaining copies within [X days], except where retention is legally required. The Supplier shall provide deletion confirmation upon request and shall identify any residual backups and their deletion schedule.

---

## 23. Service continuity and non-AI fallback

> For an AI function supporting an essential educational process, the Supplier shall document service-continuity arrangements and any dependencies that could prevent the Institution from reverting to a human or non-AI workflow.

The Institution should not accept a design in which an AI service becomes technically indispensable to a core function without an exit strategy.

---

## 24. Documentation survives marketing changes

> Contractual safeguards, data-use restrictions, incident obligations, audit rights, and deletion commitments shall control over less-protective statements in marketing materials, product pages, click-through terms, or later general online policies, except where the parties expressly agree otherwise in writing.

---

# Supplier disclosure schedule

Require bidders to complete this schedule before award.

| Item | Supplier response |
|---|---|
| AI functions used in the service | |
| Underlying model provider(s) | |
| Model/version identifiers available | |
| Material AI subprocessors | |
| Data sent to each model/provider | |
| Uses customer data for training/improvement? | |
| Retention period for prompts/uploads/outputs | |
| Consequential decisions supported | |
| Human override supported | |
| Explanation/appeal support | |
| Accessibility conformance | |
| Evaluation data available | |
| Subgroup testing performed | |
| AI incident contact | |
| Material-change notification process | |
| Emergency suspension mechanism | |
| Export format at contract end | |
| Deletion timetable | |

---

# Suggested procurement scoring

Do not score responsible-AI requirements as a tiny optional category while price and feature count dominate the award.

For systems that affect learners materially, buyers can make critical safeguards **pass/fail conditions** and score the remaining evidence quality separately.

Example evaluation dimensions:
- demonstrated fitness for the educational purpose;
- privacy/data governance;
- accessibility;
- safety and security;
- evidence quality and known limitations;
- human review and contestability;
- change control and monitoring;
- interoperability and exit;
- total cost, including oversight and migration.

---

# Source frameworks

This library is deliberately jurisdiction-neutral, but its structure is informed by current public procurement and AI-governance resources:

1. **European Public Buyers Community — Updated EU AI Model Contractual Clauses (2025).** Full and light versions are available for public buyers, with translations in 24 EU languages. https://public-buyers-community.ec.europa.eu/communities/procurement-ai/resources/updated-eu-ai-model-contractual-clauses
2. **UK Government — Guidelines for AI Procurement.** Addresses data provenance, explainability, supplier evaluation, vendor lock-in, training, incident reporting, and end-of-life planning. https://www.gov.uk/government/publications/guidelines-for-ai-procurement/guidelines-for-ai-procurement
3. **UK Cabinet Office — PPN 017: Improving Transparency of AI Use in Procurement (2025).** Provides supplier-disclosure questions and AI risk-management prompts for procurements. https://www.gov.uk/government/publications/ppn-017-improving-transparency-of-ai-use-in-procurement
4. **NIST — AI Risk Management Framework.** Includes third-party risk, monitoring, incident response, human oversight, appeal/override, and change management. https://www.nist.gov/itl/ai-risk-management-framework
5. **NIST — Cybersecurity Supply Chain Risk Management Due Diligence Quick-Start Guide (2026).** Provides implementation-ready supplier due-diligence practices. https://www.nist.gov/news-events/news/2026/07/nist-releases-finalized-c-scrm-due-diligence-assessment-quick-start-guide
6. **UNICEF — Guidance on AI and Children v3.0 (2025).** Child-centred requirements for safety, privacy, fairness, transparency, accountability, inclusion, oversight, and redress. https://www.unicef.org/innocenti/reports/policy-guidance-ai-children

---

## Maintenance rule

Review this library at least annually and after major changes in AI regulation, procurement standards, model capabilities, or evidence. A contract written for one model generation should not be assumed adequate for the next.

**License:** Same license as this repository. Adapt within the repository's license terms.
