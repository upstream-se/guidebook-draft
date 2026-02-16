# Upstream Software Engineering definition

This page defines Upstream Software Engineering as a distinct practice within the broader field of Software Engineering.  It clarifies its locus of concern, its object of governance, and its relationship to the construction, operation, and evolution of long-lived software systems.

The definition is intentionally concise.  The sections that follow establish the core conceptual elements on which the discipline rests.


## Definition

> **Definition.**  Upstream Software Engineering is the practice of epistemic governance of the intent of long-lived software systems, articulable as durable, revisable commitments about scope and structure that normatively guide their construction, operation, and evolution as their context changes.

The definition fixes the locus of the discipline: governance of articulated commitments that orient and constrain realization across time.

Its precise meaning depends on five interdependent conceptual elements.


## Core elements of the discipline

Upstream Software Engineering rests on five mutually reinforcing elements.  None is reducible to the others.

### Epistemic governance

Epistemic governance concerns the stewardship of knowledge rather than the coordination of activity.  It determines what must be made explicit, preserved, inspectable, traceable, and deliberately revisable over time.

Upstream does not govern execution directly.  It governs the knowledge that normatively orients and constrains construction, operation, and evolution.

→ See **[Epistemic governance](../epistemic-governance.md)** for the definition of epistemic governance and its role in the discipline.


### Software system

A software system is the enduring socio-technical entity whose commitments persist across initiatives, teams, technological shifts, and organizational restructuring.

Upstream presupposes such persistence.  Without a long-lived system, durable commitments would not be structurally necessary.

→ See **[Software system](../software-system.md)** for the definition of the enduring entity that bears intent.


### Intent

Intent denotes articulated commitments that bind realization while remaining explicitly revisable through deliberate reconsideration.

Intent has two inseparable dimensions:

- commitments about **scope**, concerning what the system is for and not for;  
- commitments about **structure**, concerning binding design constraints and structural decisions that shape architecture, integration, deployment, automation, and evolution.

Together, these commitments form the normative core against which construction, operation, and structural transformation are evaluated.

→ See **[Intent](../intent.md)** for the definition of intent and its role in the discipline.


### Context

Context refers to the real-world environment in which the system is embedded.

Context itself is not governable.  What is subject to governance is the articulated knowledge and assumptions about that environment and their declared relationship to system intent.

When context changes, commitments must be deliberately reinterpreted or revised rather than allowed to drift implicitly.

→ See **[Context](../context.md)** for the definition of context and its role in the discipline.


### Stewardship and authority

Binding commitments presuppose identifiable stewardship and recognized authority.

Without accountable stewardship:

- commitments become advisory rather than binding,
- revision becomes drift,
- governance becomes rhetorical.

Upstream does not prescribe organizational structure.  It asserts a structural requirement: durable commitments require accountable authority capable of preserving and revising them.

→ See **[Stewardship and authority](../stewardship-and-authority.md)** for the institutional conditions of epistemic governance.


## The context–intent relationship

Intent is articulated and justified relative to an understanding of context.

The relationship is directional and normative:

- articulated knowledge about context **justifies** commitments,
- commitments about scope and structure **constrain** realization,
- realization operationalizes commitments under evolving conditions.

When contextual understanding changes, three possibilities arise:

- commitments remain valid,
- commitments require reinterpretation,
- commitments must be explicitly revised.

Silent divergence between contextual reality and articulated commitments constitutes governance failure.

Upstream Software Engineering exists to prevent such asymmetry.


## Binding but revisable

The central governance property of intent is that it is both binding and revisable.

**Binding** means that articulated commitments normatively constrain realization.  They define what must be respected unless deliberately reconsidered.

**Revisable** means that commitments are not immutable.  When contextual conditions change, they may be explicitly re-articulated.

Durability does not imply immutability.  Revisability does not imply informality.

Binding but revisable commitments make coherent evolution possible.


## Upstream and downstream

Software Engineering encompasses multiple layers of concern. Upstream introduces an explicit stratification between two distinct but interdependent domains.

**Downstream** concerns realization: construction, implementation, deployment, operation, automation, testing, refactoring, monitoring, and artifact production.

**Upstream** concerns the epistemic governance of the commitments that normatively orient and constrain that realization.

The distinction is not hierarchical and not oppositional:

- Downstream governs activity and artifact production.  Upstream governs the commitments that define and constrain those activities and artifacts.  

- Downstream operates within initiative horizons.  Upstream spans discontinuities.  

- Downstream optimizes execution.  Upstream preserves meaning.

Execution without epistemic stewardship leads to drift.  Epistemic articulation without realization remains inert.

Coherent software evolution requires both.

→ See **[Upstream and downstream](../upstream-and-downstream.md)** for the distinction between epistemic governance and execution-oriented practice.


## Where to go next

Continue to **[Software system](../software-system.md)** for the definition of the enduring socio-technical entity that bears intent.

Proceed to **[The discipline](../index.md)** for the conceptual structure of this part, to **[Foundations](../../index.md)** for the normative framework of the discipline, or to **[Guidebook](../../../index.md)** for the complete structure of the guidebook.
