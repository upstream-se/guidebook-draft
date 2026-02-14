# Definition of the Discipline

> ⚠️ **This page is under active construction.**  
> The conceptual structure is established. Wording and refinement will evolve.

## 1. Definition

> **Definition.**  Upstream Software Engineering is the practice of epistemic governance of the intent of long-lived software systems, articulable as durable, revisable commitments about scope and structure that normatively guide their construction, operation, and evolution as their context changes.

The following elaboration stabilizes the intended interpretation of the definition and prevents drift in its understanding.

**Epistemic governance** concerns the stewardship of knowledge rather than the coordination of activity.  It determines what must be made explicit, preserved, inspectable, and deliberately revisable over time.  Upstream Software Engineering does not govern execution; it governs the knowledge that orients and constrains execution.

**Intent** denotes the set of durable yet revisable commitments that define and constrain a software system.  It has two inseparable dimensions.  **Intent in scope** concerns purpose, domain boundaries, assumptions, obligations, and non-goals.  **Intent in structure** concerns binding design decisions and structural constraints that shape organization, integration, deployment, automation, and evolution.  Together, these commitments constitute the normative core against which construction, operation, and structural transformation are evaluated.

Long-lived systems persist across projects, iterations, organizational restructuring, technological shifts, and provider transitions.  Coherence across such discontinuities requires commitments that are neither implicit nor frozen.  They must constrain decision-making while remaining explicitly revisitable when contextual conditions change.

**Context** itself is not governed as external reality.  What is governed is the explicit knowledge about the context in which the system is embedded and the articulated relationship between that knowledge and system intent.  When context shifts, commitments must be consciously reinterpreted or revised rather than allowed to erode through drift.


## Stress-testing the definition

To assess the robustness of the definition, it is useful to examine how it behaves under boundary conditions. The following cases test whether the definition remains coherent across different types of systems, organizational contexts, and technological environments.

### 1. Short-lived systems

**Case.** Hackathon prototypes, throwaway scripts, or one-off internal tools.

**Observation.** The definition explicitly applies to long lived systems. If durability is not required, epistemic stewardship of intent is unnecessary.

**Implication.** Upstream Software Engineering is not “more process” applied universally. It addresses the structural problem of preserving coherent commitments across time. Where longevity is irrelevant, upstream governance is correspondingly unnecessary.

---

### 2. Greenfield startup environments

**Case.** Early-stage product development with minimal documentation and rapid iteration.

**Observation.** Even in greenfield contexts, there exists intent — vision, commitments, constraints, positioning — that normatively guides development.

**Implication.** Upstream does not require heavy artifacts. It requires that intent be articulable, revisitable, and consciously revised as context shifts. The definition is compatible with lean and iterative environments.

---

### 3. AI-augmented development

**Case.** Large portions of the system are generated or refactored by AI systems.

**Observation.** AI can generate artifacts, but it cannot institutionally commit to intent.

**Implication.** The more artifact production is automated, the more critical explicit intent governance becomes. The definition scales to AI-augmented environments because it governs commitments, not authorship.

---

### 4. Legacy modernization

**Case.** Long-lived systems with decayed documentation and lost rationale.

**Observation.** Intent may be implicit, fragmented, or partially lost.

**Implication.** Upstream practice includes reconstruction and re-articulation of commitments. Durability is not assumed; it is actively re-established.

---

### 5. Highly regulated domains

**Case.** Banking, healthcare, aerospace, or other compliance-intensive environments.

**Observation.** Regulatory frameworks govern risk, controls, and auditability.

**Implication.** Regulatory governance does not necessarily institutionalize durable epistemic stewardship of system-level intent. Upstream governance complements compliance by preserving coherent commitments beyond audit requirements.

---

### 6. Rapid pivot environments

**Case.** Organizations that frequently change business models or strategic direction.

**Observation.** Durability does not imply immutability.

**Implication.** Commitments are durable yet revisable. Upstream governance ensures that revision is explicit and traceable, rather than implicit and accumulative.

---

### 7. Conceptual consistency

Across these boundary cases, the definition remains internally coherent:

- It governs intent rather than artifacts.
- It applies only where long-term coherence matters.
- It accommodates iteration and automation.
- It remains distinct from execution-focused methodologies.
- It scales to AI-augmented environments.

The stress test confirms that the definition is neither overly restrictive nor vacuous. It isolates a specific and historically persistent governance problem: the preservation and conscious revision of articulated commitments about scope and structure as context changes over time.


## 2. What Is Governed

### 2.1 Intent as Commitments

This subsection will clarify that:

- Intent is not aspiration or preference.
- Intent is institutional commitment.
- Intent is binding for downstream realization but revisable upstream.

Intent has two dimensions:

- **Scope-intent** — commitments regarding what the system is meant to do (normative to requirements).
- **Structure-intent** — commitments and constraints regarding how the system must be structured (normative to architecture, technology choices, environments, automation, and design constraints).

Structure-intent constitutes the core set of decisions and constraints that must remain visible, respected, and explicitly revisited when obsolete.


### 2.2 Knowledge of Context

This subsection will clarify that:

- Context refers to the external reality within which the system exists (organizational, technological, regulatory, economic, social).
- Upstream does not govern context itself.
- Upstream governs articulated knowledge about context.
- Intent is justified relative to that articulated contextual knowledge.

Context itself is not governed; knowledge of context is.


## 3. The Intent–Context Relationship

This section will explain the directional relationship:

Context (as understood) → justifies → Intent → constrains → Downstream realization.

When contextual understanding changes:

- Commitments may remain valid,
- Or must be explicitly revised.

Silent drift between context and commitments constitutes a governance failure.

This prepares the conceptual ground for the pages on Change and Software Evolution.


## 4. Binding but Revisable

This section will clarify the core governance property of intent:

- Binding means downstream realization must conform to declared commitments.
- Revisable means upstream may explicitly re-articulate those commitments.
- Revision must be deliberate and visible.
- Unarticulated change constitutes erosion of governance.

Intent is neither immutable nor informal; it is governable.


## 5. Upstream and Downstream

This section will describe the stratification in prose before introducing any summary table.

Downstream concerns:

- execution,
- construction,
- deployment,
- operational control,
- artifact production.

Upstream concerns:

- stewardship of commitments,
- preservation of coherence across initiatives,
- governance beyond project boundaries,
- evolution of meaning across time.

A compact comparison table may be included as a summary at the end of the section.

## Where to go next

Return to:

- **[Discipline](./index.md)**

- **[Foundations](../index.md)**

- **[Guidebook home](../../index.md)**
