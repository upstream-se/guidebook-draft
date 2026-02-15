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


## What Is Governed

Upstream Software Engineering governs neither activity nor artifacts in themselves.  It governs the articulated commitments that define and constrain a long-lived software system.  The longevity of such systems makes durable epistemic governance necessary.

This requires distinguishing clearly between:

- execution and its products, and  
- the normative knowledge that orients and constrains them.

Construction, operation, deployment, automation, architectural modeling, documentation, and refactoring are all necessary practices.  They are not, however, the primary object of upstream governance.  They are shaped by upstream commitments, but they are not themselves the locus of epistemic control.

Upstream governs two interrelated knowledge domains.


### Intent as binding commitments

Intent is not aspiration, preference, or informal vision.  It consists of institutional commitments that define what must be respected unless deliberately revised.

Such commitments are:

- binding with respect to realization,
- durable across initiatives and organizational discontinuities, and
- explicitly revisable through structured reconsideration.

Intent has two inseparable dimensions:

- **Scope-intent** — commitments regarding what the system is meant to do, what obligations it assumes, and what non-goals delimit its domain.  
- **Structure-intent** — commitments and constraints regarding how the system must be shaped, including architectural principles, structural boundaries, technology constraints, integration assumptions, deployment environments, and automation strategies.

Structure-intent is not architectural description.  It is the set of decisions and constraints that must remain visible, respected, and consciously revisited when they become misaligned with evolving context.

Together, scope-intent and structure-intent form the normative core that governs system realization across time.


### Knowledge of context

Context refers to the external environment within which the system exists: organizational structures, regulatory conditions, technological ecosystems, market forces, and socio-technical constraints.

Context itself is not governable.  What is governable is the articulated knowledge about context and the declared relationship between that knowledge and system intent.

Commitments are justified relative to contextual assumptions.  When contextual conditions change, the validity of those commitments must be re-evaluated.

Upstream governance therefore requires that:

- contextual assumptions be made explicit,
- their linkage to commitments be traceable, and
- reinterpretation occur deliberately rather than implicitly.

The discipline does not attempt to control external reality.  It governs the knowledge that interprets that reality in relation to system intent.


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
