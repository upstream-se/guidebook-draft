# Definition of the Discipline

> ⚠️ **This page is under active construction.**  
> The conceptual structure is established. Wording and refinement will evolve.

This page defines Upstream Software Engineering as a distinct practice within the broader field of Software Engineering.  It clarifies its locus of concern, its object of governance, and its relationship to the construction, operation, and evolution of long-lived software systems.  The definition is intentionally concise; what follows specifies its precise meaning and scope.


## Definition

> **Definition.**  Upstream Software Engineering is the practice of epistemic governance of the intent of long-lived software systems, articulable as durable, revisable commitments about scope and structure that normatively guide their construction, operation, and evolution as their context changes.

The definition above fixes the core locus of the discipline.  The following clarifications stabilize its interpretation without expanding its scope.

**Epistemic governance** concerns the stewardship of knowledge rather than the coordination of activity.  It determines what must be made explicit, preserved, inspectable, and deliberately revisable over time.  Upstream Software Engineering does not govern execution; it governs the knowledge that normatively orients and constrains construction, operation, and evolution.

**Long-lived software systems** are systems that persist across projects, teams, technological shifts, and organizational restructuring.  Their endurance makes durable yet revisable commitments necessary.

**Intent** denotes articulated commitments that bind realization while remaining explicitly revisable through deliberate reconsideration.  These commitments have two inseparable dimensions:  
- commitments about **scope**, concerning what the system is for and not for; and  
- commitments about **structure**, concerning binding design constraints and structural decisions that shape architecture, integration, deployment, automation, and evolution.  

Together, these commitments form the normative core against which construction, operation, and structural transformation are evaluated.

**Context** refers to the real-world environment in which the system is embedded.  Context itself is not governable.  What is subject to governance is the articulated knowledge and assumptions about that environment and their declared relationship to system intent.  When context changes, commitments must be deliberately reinterpreted or revised rather than allowed to drift implicitly.

The meaning of the definition above can be disciplined by examining borderline cases, as anakyzed in the **[Conceptual boundary analysis](./conceptual-boundary-analysis.md)**.


## What is governed

Upstream Software Engineering does not govern activity, artifacts, or execution practices directly.  It governs the **intent of long-lived software systems**, and the articulated knowledge that conditions and justifies that intent.

This requires clarifying three elements: the meaning of *long-lived software systems*, the nature of *intent as commitment*, and the role of *contextual knowledge*.


### Long-lived software systems

A long-lived software system is not defined merely by runtime duration or technical scale.  It is defined by persistence across initiatives, teams, technologies, and organizational configurations.

Such systems:

- outlive individual projects and development cycles,
- accumulate structural and intentional history,
- evolve under changing technological, regulatory, economic, and organizational conditions, and
- remain operational while being continuously modified.

The durability of these systems is precisely what makes epistemic governance necessary.  When a system persists beyond the lifecycle of any single initiative, its commitments cannot remain project-bound.  They must be articulated, preserved, and consciously revised across time.

Upstream is therefore concerned not with one-off development efforts, but with the sustained coherence of systems that endure and evolve.


### Intent as commitments

Intent is not aspiration, preference, or informal vision.  Intent consists of **institutional commitments**.

A commitment binds downstream realization while remaining revisable upstream.  It defines what must be respected unless deliberately reconsidered.

Intent has two interrelated dimensions:

- **Scope-intent** — commitments regarding what the system is meant to do and not do.  These commitments are normative with respect to user requirements and functional evolution.
- **Structure-intent** — commitments and constraints regarding how the system must be structured.  These include architectural principles, design constraints, technology boundaries, environmental assumptions, automation strategies, and other structural decisions that normatively guide architecture and implementation.

Structure-intent constitutes the core set of decisions and constraints that must remain visible, respected, and explicitly revisited when obsolete.

Intent is therefore dual: it concerns both what the system is for and how it must be shaped to remain coherent with that purpose.


### Knowledge of context

Context refers to the external reality within which the system exists: organizational arrangements, regulatory frameworks, technological environments, market conditions, and socio-technical constraints.

Context itself, as real-world environment, is not governable.  
What is governable is the **articulated knowledge and assumptions about that environment**, and the declared relationship between that knowledge and system intent.

Intent is justified relative to an understanding of its context.  When the context changes, commitments must be consciously reinterpreted or revised rather than allowed to erode through drift.

Upstream therefore governs not the external world, but the structured knowledge of how that world conditions and constrains the system's commitments.


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
