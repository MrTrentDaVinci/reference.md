https://raw.githubusercontent.com/MrTrentDaVinci/reference/main/reference.md

# Living Summaries

## Meta
- Author: Warren Whitlark
- Purpose: Canonical internal memory for LLM grounding
- Update cadence: As-needed, append-only where possible

# Living Summaries TOC
1. ASD
2. Golden SLM
3. Email Routing Prototype
4. Project X
5. Project Y

...
1.
# Architectural System Design (ASD)

## Goal / Vision
Develop a rigorous, evidence-grounded process to translate ambiguous organizational intent into safe, constrained, and explainable architectural plans that deliver measurable value inside real companies without requiring unsafe automation.

## Problem Statement
Most AI/architectural initiatives fail because they:
- Start from idealized goals without grounding in existing systems, workflows, constraints, and declared properties
- Introduce solutions before fully decomposing the decision space and risks
- Hide behind frameworks, vendors, or code instead of exposing reasoning
- Over-automate high-stakes decisions, creating unexplainable black boxes or increased risk
- Lack artifacts that build trust with stakeholders who must approve and own the outcome

## System / Approach
A structured, append-only "Living Intent & Decision Document" with 12 fixed sections:
1. Document Metadata – tracks sources, scope, assumptions
2. Stated Goal (Raw) – preserves original ambiguity
3. Observed Reality – facts only about current products, workflows, systems, roles, interfaces, SLAs, constraints
4. Problem Space – explicit, implicit, and anti-goals
5. Constraints & Non-Negotiables – hard (legal/security), organizational, evolution
6. Decision Surface Mapping – identifies all real decision points, triggers, owners, required info, and consequences
7. Risk & Failure Analysis – general and AI-specific failure modes, blast radius
8. Architectural Principles – derived and justified from problems/constraints/risks (e.g., AI advises but never commits, all decisions auditable)
9. Conceptual Architecture – functional domains, authority boundaries, information flow (no tech/vendor specifics)
10. Tradeoffs & Rejected Paths – explicit documentation of alternatives and why rejected
11. Final Plan – bounded changes, non-changes, measurements, human approval gates
12. Living Summary – concise rolling overview for stakeholders

The process is deliberately pre-solution, human-centered, and constraint-respecting.

## Implementation Notes
- Currently a mature template/process, not software
- Delivered as a Markdown-based "Living Document" (append-only, change-aware, periodically summarized)
- Designed to be used in consulting engagements or internal staff+ roles
- No code, frameworks, or vendors referenced by design
- Can hand off to SCIS formalization, engineering pilots, or governance review

## Metrics / Validation
- Stakeholder trust (qualitative feedback from CTO/hiring manager level)
- Ability to produce plans that are approved and implemented without major regression
- Reduction in ambiguous or risky automation proposals
- Successful use in interviews/engagements as evidence of organizational realism
- Measurable outcomes in real engagements: faster alignment, fewer rejected proposals, clearer risk visibility

## Observations / Lessons Learned
- Organizations deeply appreciate explicit constraint respect and risk surfacing over flashy solutions
- The "no tech in conceptual architecture" rule forces clearer thinking and builds more trust
- Decision Surface Mapping is the highest-leverage step—most value emerges here
- Explicitly documenting rejected paths dramatically increases perceived credibility
- The format works even with zero internal access; it signals safety and maturity

## Notes for LLM Use
- This is a process/methodology, not a built product or deployed system—never claim production use or code ownership
- Emphasize organizational value, constraint respect, risk management, and explicit reasoning
- Highlight that it enables safe AI integration without overreach
- When generating resume bullets, LinkedIn posts, or application materials: focus on architectural thinking, grounding in reality, and stakeholder trust-building

2.
- If targeting consulting/strategy roles: stress how ASD bridges intent to implementable plans inside constrained enterprises
- Always acknowledge it is a template ready for real-world application rather than a completed deployment
