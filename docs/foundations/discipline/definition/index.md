# Upstream Software Engineering definition

This page defines Upstream Software Engineering as a distinct practice within the broader field of Software Engineering.  It clarifies its locus of concern, its object of governance, and its relationship to the construction, operation, and evolution of long-lived software systems.  The definition is intentionally concise; what follows stabilizes its interpretation and situates its core elements.


## Definition

> **Definition.**  Upstream Software Engineering is the practice of epistemic governance of the intent of long-lived software systems, articulable as durable, revisable commitments about scope and structure that normatively guide their construction, operation, and evolution as their context changes.

The definition fixes the core locus of the discipline.  What follows stabilizes its interpretation without expanding its scope.

**Epistemic governance** concerns the stewardship of knowledge rather than the coordination of activity. It determines what must be made explicit, preserved, inspectable, and deliberately revisable over time. Upstream Software Engineering does not govern execution; it governs the knowledge that normatively orients and constrains construction, operation, and evolution.


## Core elements of the discipline

Upstream Software Engineering presupposes four interdependent conceptual elements:

- the **software system** that persists across time,
- the **intent** that normatively constrains realization,
- the **context** that justifies and conditions commitments,
- and the **stewardship and authority** that make binding governance possible.

Each is stabilized here and developed in its own page.


### Software system

A long-lived software system is the enduring socio-technical entity centered on executable software whose behavior, structure, and commitments persist across projects, teams, technological shifts, provider transitions, and organizational restructurings.

It is not a repository, a deployment instance, or a temporary initiative. It is the identifiable system that accumulates structural and intentional history over time. Its persistence across discontinuities is what makes durable epistemic governance necessary.

→ See **[Software system](../software-system.md)** for the definition of the enduring socio-technical entity that bears intent.


### Intent

Intent is the set of durable, revisable commitments about the scope and structure of a long-lived software system. These commitments normatively constrain construction, operation, and evolution.

Intent has two inseparable dimensions: commitments about **scope**, which define what the system is for and not for, and commitments about **structure**, which define binding design constraints and structural decisions. Together, they form the normative core against which realization is evaluated across time.

→ See **[Intent](../intent.md)** for the definition of intent and its role in the discipline.


### Context

Context refers to the real-world environment within which the system exists: organizational arrangements, regulatory conditions, technological ecosystems, market forces, and socio-technical constraints.

Context itself is not governable. What is subject to governance is the articulated knowledge and assumptions about that environment and their declared relationship to system intent. When contextual understanding changes, the validity of commitments must be deliberately re-evaluated.

→ See **[Context](../context.md)** for the definition of context and its role in the discipline.


### Stewardship and authority

Binding commitments presuppose identifiable responsibility. If intent is to constrain realization and remain deliberately revisable, there must exist a locus of authority capable of articulating, preserving, interpreting, and revising commitments across discontinuities.

Authority does not prescribe a specific organizational form. It establishes a structural requirement: without accountable stewardship, commitments lose binding force and governance collapses into informal practice.

→ See **[Stewardship and authority](../stewardship-and-authority.md)** for the institutional conditions that make binding intent possible.

## What is governed

Upstream Software Engineering governs neither activity nor artifacts in themselves. It governs the articulated commitments that define and constrain a long-lived software system, together with the structured knowledge that justifies and conditions those commitments.

Construction, operation, deployment, automation, architectural modeling, documentation, and refactoring are necessary practices. They are shaped by upstream commitments, but they are not themselves the primary locus of epistemic control.

Upstream governance therefore concerns:

- the durability of commitments,
- the explicit articulation of contextual assumptions,
- the traceability between commitments and context,
- and the visible revision of commitments when conditions change.


## The context–intent relationship

Intent does not exist in isolation. It is articulated and justified relative to an understanding of context.

The relationship is directional and normative:

- Articulated knowledge about context **justifies** commitments.
- Commitments about scope and structure **constrain** realization.
- Realization operationalizes commitments under evolving conditions.

When contextual understanding changes, three possibilities arise:

- The existing commitments remain valid.
- The commitments require reinterpretation.
- The commitments must be explicitly revised.

What must not occur is silent divergence. If contextual conditions shift while commitments remain formally unchanged yet practically ignored, coherence erodes. If commitments are modified implicitly without explicit reconsideration, governance dissolves into drift.

Upstream Software Engineering exists to prevent this asymmetry.


## Binding but revisable

The central governance property of intent is that it is both binding and revisable.

**Binding** means that articulated commitments normatively constrain realization. They are not advisory preferences or informal aspirations.

**Revisable** means that commitments are not immutable. Long-lived systems evolve under shifting contextual conditions. Revision must be explicit, deliberate, and visible.

Unarticulated modification constitutes erosion of governance.  
Permanent rigidity constitutes failure to adapt.

Durability does not imply immutability. Revisability does not imply informality. Binding but revisable commitments make coherent evolution possible.


## Upstream and downstream

Software Engineering encompasses multiple layers of concern. Upstream Software Engineering introduces an explicit stratification between two distinct but interdependent domains of practice.

**Downstream** refers to realization: construction, implementation, deployment, operation, automation, testing, refactoring, monitoring, and artifact production.

**Upstream** refers to the epistemic governance of the commitments that normatively orient and constrain that realization.

Execution without epistemic stewardship leads to drift.  
Epistemic articulation without realization remains inert.  

Coherent software evolution requires both.

→ See **[Upstream and downstream](../upstream-and-downstream.md)** for the distinction between epistemic governance and execution-oriented practice.


## Where to go next

Continue to **[Software system](./software-system.md)** for the definition of the enduring socio-technical entity that bears intent.

Proceed to **[The discipline](../index.md)** for the conceptual structure of Upstream Software Engineering, to **[Foundations](../../index.md)** for the normative framework of the discipline, or to **[Guidebook](../../../index.md)** for the complete structure of the guidebook.