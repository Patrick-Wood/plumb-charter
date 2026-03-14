# Plumb Operational Governance Charter
**Version 2.7 | March 2026 | Author: Patrick Wood | Maintained by DeskGems LLC**

A governance standard defining authority boundaries, accountability requirements, and quality control principles for AI systems operating in consequential decision contexts.

---

## Important: Charter vs. Implementation

This repository contains the Plumb Operational Governance Charter — a public governance standard.

It does not contain, describe, or provide access to the Plumb operational implementation.

|  | **Charter (This Repository)** | **Plumb Implementation** |
|---|---|---|
| **Status** | Public — open governance standard | Proprietary — trade secret |
| **Availability** | Free to read and reference | Not available |
| **License** | CC BY-ND 4.0 | All rights reserved |
| **Purpose** | Defines what governed AI interaction must achieve | How DeskGems LLC achieves it |

The Plumb v9.1 operational implementation is proprietary intellectual property of DeskGems LLC. It is not for sale, not available for licensing, and is not described in this repository. The Charter defines the governance standard. The implementation is the proprietary mechanism by which DeskGems LLC meets that standard.

---

## What This Charter Is

The Plumb Operational Governance Charter establishes the governance framework for Human-AI Collaboration (HAIC) operational systems. In plain terms: it is a set of rules that governs how AI should behave when the stakes are real — when a wrong answer, an overconfident claim, or a missed boundary could lead to a bad decision with real consequences.

The Charter addresses three structural failures common in ungoverned AI interactions:

**Authority boundary violations** — AI responding to questions that require professional credentials (legal, medical, financial, and similar) without recognizing that boundary and directing the person to the appropriate expert. This creates liability exposure for the user.

**Surface-level analysis** — AI producing responses that look adequate but skip over critical dependencies, trade-offs, or stakeholder considerations — because nothing in the system required it to go deeper.

**Sycophantic evaluation** — AI providing unearned encouragement instead of substantiated analysis when a person asks for honest feedback on their own work or ideas.

The Charter enforces structural controls that prevent these failures before AI responds — not after output has already been generated.

---

## What This Charter Is Not

This Charter is not:

- A description or disclosure of the Plumb v9.1 operational implementation
- A guide for building Plumb or replicating any component of it
- A certification, attestation, or compliance standard for any regulatory framework
- A replacement for professional expertise in legal, financial, medical, or other credentialed domains
- Available for purchase, licensing, or commercial acquisition in any form

Users remain fully responsible for their own decisions. No Charter-aligned system transfers human accountability to AI.

---

## The Core Problem This Charter Solves

Most people interact with AI the same way they use a search engine or ask a colleague — they expect a direct answer and assume the AI will flag it if something is out of bounds. In practice, ungoverned AI systems do not reliably flag those boundaries. They answer confidently when they shouldn't, skip complexity they weren't asked to address, and tell people what they want to hear rather than what the evidence supports.

This matters when the stakes are low. It matters far more when someone is making a business decision, evaluating a legal situation, assessing a financial option, or reviewing work that others will rely on.

The Plumb Charter exists to establish a different operating standard: one where AI works as a disciplined, honest analytical partner — not a yes-machine — and where the boundary between what AI can appropriately do and what requires a human expert is made visible and enforced every time.

---

## Key Governance Concepts

### Authority Suitability Bands

The Charter defines six qualitative governance bands that express who actually holds the authority to act on a given type of work:

**Band 1 — No AI Authority:** The work is something AI is structurally incapable of doing or legally prohibited from doing. Examples include physical tasks and certain regulated professional activities.

**Band 2 — Escalation Required:** The work requires a licensed professional — a credentialed attorney, physician, financial advisor, or similar — and AI cannot substitute for that credential under any circumstances.

**Band 3 — User-Authority Dependent:** The work requires organizational authority that the person asking holds — things like hiring decisions, policy approvals, or binding commitments. AI can prepare materials in support, but the person must execute.

**Band 4 — Collaborative Analytical:** AI can do the analytical work, but the person must validate and decide. Options are presented with trade-offs. No prescriptions.

**Band 5 — AI-Safe Routine:** AI executes the work and the person reviews the result before it is used.

**Band 6 — Deterministic Automation:** Straightforward, algorithmic work that AI executes reliably with a basic verification step.

### Governance Modes

Each Authority Suitability Band maps to a governance Mode that constrains how AI behaves in that context:

- **ESC (Escalation):** A credentialed professional is required. AI prepares materials for that expert consultation but does not attempt to perform the credentialed work itself.
- **DELEGATE:** The person executes using their own organizational authority. AI supports with preparation.
- **COLLAB:** AI drafts and analyzes; the person validates and decides.
- **LEAD:** AI executes comprehensively; the person reviews before use.
- **AUTO:** Deterministic execution with a verification step.

### Escalation Is Permanent

A critical Charter principle: once AI determines that a question requires a licensed professional, that determination cannot be reversed by the person claiming credentials, asserting authority, or pushing back. The reason is structural — AI has no way to verify credentials at the point of interaction. Escalation is based on the nature of the work activity, not the identity of the person asking. This boundary exists to protect users, not to question them.

### Anti-Sycophancy Controls

When a person asks for feedback on their own work, ideas, or qualifications, the Charter requires that AI actively resist the tendency to be agreeable. Claims must be substantiated with evidence. Comparatives require a named basis for comparison. Praise requires criteria. If AI output contains unsupported encouragement, the Charter requires it to be regenerated before delivery.

### Analytical Depth Requirement

The Charter requires that analysis not converge prematurely. For anything beyond a simple factual question, AI must work through multiple analytical passes — expanding options, testing assumptions, mapping trade-offs, and checking for gaps — before producing a response. The complexity of the question determines how deep that process must go. This depth requirement is structural: it cannot be shortened for speed or convenience.

### The Human Review Handoff

Every governed response concludes with an explicit handoff to the human reviewer. This section identifies what needs to be verified before the output is used, what the person needs to validate given their own context, and whether any part of the work requires a credentialed expert before action can be taken. The handoff is not boilerplate — its content is specific to what was actually produced.

### Framework-Anchored Analysis

For analytical work, the Charter requires that a recognized analytical framework — selected based on the nature of the work and the stakes involved — organize the analysis throughout. This provides coherence across a multi-pass analytical process and gives the human reviewer a clear structure for evaluating what was produced. When the framework is applied, it is identified in the handoff so the reviewer can engage with it directly.

### Dataset Intelligence Governance

When AI is analyzing data from external sources — job postings, filings, company profiles, public records, and similar — the Charter requires that AI classify the nature of that data before drawing any conclusions from it. Data that an organization controls and selects (like its own press releases or job postings) carries a structural bias: it shows what the organization chose to share, not what is complete or true. Data compelled by regulation (like required financial disclosures) carries a different character. The Charter requires these distinctions to be made explicit, and requires that conclusions be appropriately bounded based on what the data can actually support.

---

## What Governs Novel and Emerging Domains

A significant governance addition in v2.7 addresses a challenge specific to emerging fields: when there are no established norms to compare against, what can AI responsibly conclude?

The Charter establishes a four-level classification for domain novelty:

- **Established:** Recognized norms exist. Standard benchmarking applies.
- **Adjacent:** No direct norm exists, but norms from a structurally similar domain can be applied with explicit reasoning.
- **Novel:** No established norms and no directly transferable adjacent norms. Conclusions must be clearly labeled as inferred, not sourced. Forecasting is restricted.
- **Compound Novel:** Both the domain and the specific application within it are without precedent. Only structural constraints — things that must logically exist for any entity of that type to function at all — can be stated. No performance claims or normative benchmarks are permitted.

This classification prevents AI from filling the absence of established norms with invented ones, which is one of the most consequential failure modes in AI-assisted analysis of new fields.

---

## What This Charter Does Not Permit

**For users of Charter-governed services:**
- Assuming that AI-produced analysis constitutes professional advice in legal, financial, medical, or other credentialed domains
- Treating escalation determinations as negotiable based on claimed credentials or expertise
- Bypassing the human review handoff without acting on its contents

**For others referencing this Charter:**
- Claiming your system "implements Plumb" or "runs Plumb" — Plumb v9.1 is a specific proprietary implementation not available for deployment
- Publishing modified versions of this Charter without written permission from DeskGems LLC
- Representing Charter alignment as DeskGems LLC endorsement or certification

---

## Charter Structure

The Charter is organized as follows:

**Section 1** — Introduction, Purpose, and Implementation Boundary Statement

**Section 2** — Governance Principles

**Section 3** — Authority Boundaries, including Authority Suitability Band definitions

**Section 4** — Accountability Requirements

**Section 5** — Quality Control Mechanisms

**Section 6** — Implementation Architecture (functional requirements only — no implementation details)

**Section 7** — Compliance and Maintenance

**Appendix A** — Work Activity Classification: Principles (classification mechanism is proprietary)

**Appendix B** — Iteration Depth Requirements (implementation is proprietary)

**Appendix C** — Glossary

**Appendix D** — CLIENT Voice Governance: Principles (voice patterns are proprietary)

---

## Implementation Boundary

The Charter specifies what governed AI interaction must achieve. It does not specify how.

Implementation-specific details are proprietary to each compliant system and are not published here. Organizations or individuals developing Charter-compliant implementations must design their own original mechanisms for meeting the functional requirements. Building a compliant implementation means designing something new — not adapting or extending the Plumb implementation, which is not available.

---

## Framework References

The Charter is informed by established governance, risk, and control frameworks referenced as conceptual peer groups:

- **COSO** — Internal Control and Enterprise Risk Management principles
- **ISO-style** — Control and risk management standards
- **SOC-style** — Control assertion logic and evidence requirements
- **BABOK** — Business analysis methodology (IIBA)
- **Occupational labor standards** — Used as work activity classification authority basis (specific taxonomies are part of the proprietary implementation)

The Charter is not a certification under, replacement for, or attestation of compliance with any of these frameworks.

---

## Usage

This Charter is published for:

- **Evaluation** — Understand the governance posture of Plumb-governed analysis services before engaging with them
- **Reference** — Access the governance standard applied in DeskGems LLC consulting engagements
- **Research** — Study Human-AI Collaboration operational governance design as a field
- **Inspiration** — Inform the development of original governance frameworks in other contexts, provided the Charter itself is not modified without permission

---

## Relationship to DeskGems LLC Services

The Plumb Operational Governance Charter is the published governance standard applied in Patrick Wood's AI-augmented consulting practice under DeskGems LLC. Clients receiving analysis from this practice receive deliverables governed by Charter principles.

The Plumb v9.1 operational implementation — the proprietary system by which those principles are operationalized — is not disclosed through consulting engagements or any other channel.

---

## License

This Charter is licensed under **Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)**.

You are free to:
- **Share** — Copy and redistribute the Charter in any medium or format for any purpose, including commercial use

Under the following terms:
- **Attribution** — You must give appropriate credit to Patrick Wood / DeskGems LLC and link to this repository
- **No Derivatives** — You may not remix, transform, or build upon the Charter material and distribute the modified version without written permission from DeskGems LLC

This license governs the Charter document only. The Plumb v9.1 operational implementation is proprietary intellectual property of DeskGems LLC, is not covered by this license, and is not available under any license.

To request permission for derivative Charter works, open an issue using the Derivative Request template.

---

## Feedback and Discussion

For questions, feedback, or discussion:

- Open an issue using the Charter Feedback template
- Reference specific Charter sections
- Discuss governance principles and compliance questions — not implementation requests

Implementation-related requests (how does Plumb work, can I use the system prompt, where is the implementation) will be closed without response. The implementation is proprietary and is not discussed in this repository.

---

## Citation

Wood, P. (2026). *Plumb Operational Governance Charter* (Version 2.7). DeskGems LLC. Retrieved from https://github.com/Patrick-Wood/plumb-charter

---

*Plumb Operational Governance Charter is a product of DeskGems LLC. Plumb v9.1 is proprietary intellectual property of DeskGems LLC. All rights reserved.*
