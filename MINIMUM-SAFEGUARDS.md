# Minimum Safeguards Before Deploying AI in Education

**A jurisdiction-neutral pre-launch standard for schools, universities, ministries, and education providers**

AI systems can improve learning, accessibility, administration, and research. They can also affect privacy, safety, educational opportunity, academic standing, access, and future prospects. This checklist is designed as a **minimum operational gate** before deployment, not as a substitute for local law.

> **Do not launch a consequential AI use case if any Stop-Ship safeguard below is missing.**

## 1. Purpose, necessity, and proportionality

- Define the exact problem the system is meant to solve.
- Document why AI is necessary or materially better than a non-AI alternative.
- Define success metrics before deployment.
- Identify foreseeable harms and who could bear them.
- Prohibit secondary uses that were not part of the original approval.

**Stop-Ship:** No named purpose, no measurable success condition, or no accountable owner.

## 2. Consequential-decision boundary

Classify whether the system can affect admission, placement, grading, discipline, financial aid, disability support, academic progression, employment, credentialing, or access to services.

For consequential decisions:
- AI may inform a decision, but a named human must retain authority.
- The human reviewer must have enough information and time to disagree with the system.
- The institution must document which parts of the decision were AI-assisted.
- Solely automated adverse decisions should be prohibited unless clearly lawful, justified, and independently reviewed.

**Stop-Ship:** The system can materially affect a learner's opportunities without meaningful human review.

## 3. Appeal, override, and redress

- Provide a visible way for students, families, faculty, or staff to challenge an AI-influenced outcome.
- Appeals must reach a human who can actually change the result.
- Record the reason for the original outcome and the appeal disposition.
- Track patterns in overturned decisions as a safety signal.
- No one should be penalized for requesting human review.

**Stop-Ship:** A person can be harmed by an AI-influenced decision but has no practical path to contest it.

## 4. Data minimization and purpose limitation

- Collect only data necessary for the approved use case.
- Identify every data field sent to the provider or model.
- Define retention and deletion periods.
- Require explicit terms for whether prompts, student work, metadata, or behavioral data may be used for model training or product improvement.
- Treat disability, health, biometric, disciplinary, immigration, financial, and counseling data as especially sensitive.
- Do not upload protected or sensitive data to unapproved consumer tools.

**Stop-Ship:** The institution cannot say what data leaves its environment, why it is needed, who receives it, and when it is deleted.

## 5. Age- and development-appropriate design

- Evaluate whether the interaction style, confidence, anthropomorphism, persuasion, and safety controls are appropriate for the learner's age.
- Children must be clearly told when they are interacting with AI rather than a person.
- Avoid engagement mechanics that encourage emotional dependence or unnecessary continued interaction.
- Provide age-appropriate explanations of limitations, privacy, and how to get human help.

**Stop-Ship:** The system is available to children without an age-appropriate safety review.

## 6. Accessibility and accommodation compatibility

- Test with keyboard-only navigation, screen readers, zoom/reflow, color contrast, captions/transcripts, and other relevant accessibility needs.
- Ensure use of approved assistive AI does not trigger academic-integrity penalties.
- Provide equivalent non-AI or human alternatives when an AI workflow creates an accessibility barrier.
- Include disability/accessibility staff and affected users in evaluation.

**Stop-Ship:** A required AI workflow prevents some learners from accessing the same educational opportunity.

## 7. Fairness and subgroup testing

- Define which groups could experience different error rates or burdens.
- Test outcomes by relevant subgroup where lawful and statistically meaningful.
- Examine false positives and false negatives separately.
- Evaluate language, dialect, disability, socioeconomic, and cultural performance where relevant.
- Do not treat aggregate accuracy as sufficient evidence of fairness.

**Stop-Ship:** A consequential system has not been tested for materially different outcomes across affected groups.

## 8. Transparency and explanation

- Tell users when AI is materially involved.
- State what the system does, what data it uses, and what it cannot reliably do.
- Provide a plain-language explanation of consequential outputs.
- Publish the institution's rules for acceptable use, prohibited use, and escalation.
- Avoid claims that exceed the system's validated capabilities.

**Stop-Ship:** A person can be materially affected without knowing AI was involved.

## 9. Security and misuse testing

- Review authentication, access controls, logging, data leakage, prompt injection, model/tool permissions, and abuse paths.
- Test whether students can cause the system to reveal other users' information or internal instructions.
- Limit tool access to the minimum required.
- Maintain a contact and escalation path for security incidents.

**Stop-Ship:** Sensitive systems or data are exposed without a documented security test and incident owner.

## 10. Incident response

- Define what counts as an AI incident: harmful output, privacy breach, discriminatory outcome, unauthorized action, model failure, or policy violation.
- Name who receives reports and who can suspend the system.
- Preserve logs needed to investigate while respecting privacy.
- Define notification obligations to affected people.
- Conduct a post-incident review and document corrective action.

**Stop-Ship:** Nobody has authority to pause the system when something goes wrong.

## 11. Model and vendor change control

- Record the model, version, provider, configuration, integrations, and approval date.
- Require notice of material model, policy, data-use, or terms-of-service changes where contractually possible.
- Re-test consequential workflows after material changes.
- Define rollback or suspension criteria.
- Do not assume that a tool approved last year is still the same system.

**Stop-Ship:** The institution cannot identify which model/version is making consequential outputs or cannot suspend use after a material change.

## 12. Evidence before scale

- Pilot with a limited population and predefined evaluation period.
- Measure learning or operational outcomes, not novelty or engagement alone.
- Compare against the existing non-AI process where possible.
- Include failure cases and unintended consequences in the evaluation.
- Set a sunset/review date before launch.

**Stop-Ship:** A system is being scaled institution-wide without evidence that it improves the intended outcome enough to justify its risks and costs.

## 13. User participation

- Include students, educators, families, disability/accessibility representatives, and affected staff in design or review when feasible.
- Provide channels for ongoing feedback after deployment.
- Document where stakeholder concerns changed the deployment.

## 14. Exit, portability, and deletion

- Define what happens if the vendor fails, changes terms, raises prices, or becomes unacceptable.
- Ensure the institution can export necessary records and continue essential services.
- Require deletion or return of institutional data at contract end where legally and technically possible.
- Avoid avoidable vendor lock-in for core educational functions.

## Minimum governance record

For every approved AI use case, retain at least:

- use-case owner;
- purpose and success metric;
- risk classification;
- model/provider/version;
- data categories and retention terms;
- human-review process;
- appeal/redress process;
- accessibility review;
- fairness testing summary;
- security review;
- incident owner;
- approval date;
- next review date;
- suspension/rollback trigger.

## High-risk educational use cases

Extra scrutiny is warranted when AI affects access, admission, grading, placement, discipline, credentialing, financial support, disability accommodations, or other decisions that can materially alter a person's educational or professional path.

## Source frameworks

This standard synthesizes operational requirements from current international and public-sector frameworks rather than treating any one framework as globally controlling law:

1. **UNICEF, Guidance on AI and Children v3.0 (2025).** Child-centred AI requirements include safety, privacy, non-discrimination, transparency, accountability, inclusion, oversight, and redress. https://www.unicef.org/innocenti/reports/policy-guidance-ai-children
2. **UNICEF AI Strategy 2025–2030.** Principles include necessity and proportionality, do no harm, privacy, fairness, human autonomy and oversight, transparency, accountability, inclusion, and sustainability. https://www.unicef.org/digitalimpact/unicef-ai-strategy-2025-2030-ai-every-child
3. **UNESCO, Guidance for Generative AI in Education and Research.** Human-centred, age-appropriate, privacy-protective validation and governance. https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research
4. **NIST AI Risk Management Framework 1.0.** MANAGE 4 calls for post-deployment monitoring, appeal and override, decommissioning, incident response, recovery, and change management. https://www.nist.gov/itl/ai-risk-management-framework
5. **European Commission AI Act Service Desk, Education and Vocational Training.** Certain AI uses affecting educational access, admission, assessment, and related outcomes are classified as high-risk under the EU AI Act. https://ai-act-service-desk.ec.europa.eu/en/education-and-vocational-training

## How to use this

- Use it as a procurement gate, pilot checklist, board briefing, or internal audit.
- Add local legal requirements rather than replacing this baseline.
- If a safeguard is irrelevant to a use case, document why instead of silently skipping it.
- Re-run the checklist after material model or vendor changes.

**License:** Same license as this repository. Adapt freely within the repository's license terms.