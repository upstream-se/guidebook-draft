# Definition of the discipline

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

The meaning of the definition above can be disciplined by examining borderline cases, as analyzed in:

→ **[Conceptual boundary analysis](./conceptual-boundary-analysis.md)** stress-test the definition above by analyzing borderline cases.


## What is governed

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

The full conceptual treatment of intent is developed in **[Intent](../intent.md)**.


### Knowledge of context

Context refers to the external environment within which the system exists: organizational structures, regulatory conditions, technological ecosystems, market forces, and socio-technical constraints.

Context itself is not governable.  What is governable is the articulated knowledge about context and the declared relationship between that knowledge and system intent.

Commitments are justified relative to contextual assumptions.  When contextual conditions change, the validity of those commitments must be re-evaluated.

Upstream governance therefore requires that:

- contextual assumptions be made explicit,
- their linkage to commitments be traceable, and
- reinterpretation occur deliberately rather than implicitly.

The discipline does not attempt to control external reality.  It governs the knowledge that interprets that reality in relation to system intent.

The ontological grounding of context is developed in **[Context](../context.md)**.


## The context–intent relationship

Intent does not exist in isolation.  It is articulated and justified relative to an understanding of context.

The relationship is directional and normative:

- Articulated knowledge about context **justifies** commitments.
- Commitments about scope and structure **constrain** realization.
- Realization operationalizes commitments under evolving conditions.

Context, as interpreted and made explicit, provides the reasons for commitments.  Intent translates those reasons into binding decisions.  Construction and operation instantiate those decisions in practice.

This relationship is not static.

When contextual understanding changes, three possibilities arise:

- The existing commitments remain valid.
- The commitments require reinterpretation.
- The commitments must be explicitly revised.

What must not occur is silent divergence.

If contextual conditions shift while commitments remain formally unchanged yet practically ignored, coherence erodes.  If commitments are modified implicitly without explicit reconsideration, governance dissolves into drift.

Upstream Software Engineering exists to prevent this asymmetry.

It requires that:

- contextual assumptions be articulated,
- their relationship to commitments be explicit, and
- any revision of commitments be deliberate and visible.

The health of a long-lived software system depends not only on structural correctness, but on the sustained alignment between contextual understanding and articulated commitments.

This alignment is the condition for coherent evolution.


## Binding but revisable

The central governance property of intent is that it is both binding and revisable.

**Binding*+ means that articulated commitments normatively constrain realization.  They are not advisory preferences, informal aspirations, or optional guidelines.  They define what must be respected unless deliberately reconsidered.  Structural decisions, requirement refinements, technological choices, and operational configurations must remain coherent with declared commitments.

**Revisable** means that commitments are not immutable.  Long-lived systems evolve under shifting contextual conditions.  Assumptions may become invalid.  Constraints may become obsolete.  Purpose may require reinterpretation.

However, revision must be **explicit, deliberate, and visible**.

Unarticulated modification of commitments constitutes erosion of governance.  Implicit deviation from declared constraints produces drift.  
Freezing commitments permanently produces rigidity.

Upstream Software Engineering therefore treats intent as a governable object whose legitimacy depends on two conditions:

- it constrains action while valid, and  
- it can be consciously re-articulated when context demands change.

Durability does not imply immutability.  
Revisability does not imply informality.

Binding but revisable commitments make coherent evolution possible.


## Upstream and downstream

Software Engineering encompasses multiple layers of concern.  Upstream Software Engineering introduces an explicit stratification between two distinct but interdependent domains of practice.

**Downstream** refers to the realization of software systems: construction, implementation, deployment, operation, automation, testing, refactoring, monitoring, and the production of concrete artifacts.  It governs how systems are built, executed, and modified in practice.

**Upstream** refers to the epistemic governance of the commitments that normatively orient and constrain that realization.  It governs the durability, visibility, traceability, and revisability of intent across time.

The distinction is not hierarchical and not oppositional.

Downstream practices are necessary.  They embody and enact commitments.  They generate the artifacts through which systems operate and evolve.

Upstream does not replace or prescribe downstream methodologies.  It provides the normative core that gives those methodologies coherence across initiatives, teams, technological shifts, and organizational restructuring.

The two domains differ in the following aspects:

- Downstream governs activity and artifact production.  Upstream governs the commitments that define and constrain those activities and artifacts.

- Downstream operates within initiative horizons.  Upstream spans discontinuities.

- Downstream optimizes execution.  Upstream preserves meaning.

- Downstream change modifies structure and behavior.  Upstream change revises commitments.

The stratification becomes visible when systems endure beyond the lifecycle of any single project.  When teams change, technologies shift, or providers transition, downstream execution may be entirely reorganized.  Upstream commitments must remain legible and deliberately revisable if coherence is to persist.

The distinction can be summarized as follows:

| Aspect | Upstream | Downstream |
|------------|-----------|------------|
| Primary object of governance | Intent as commitments | Activity and artifacts |
| Time horizon | Cross-initiative, long-lived | Initiative-bound |
| Mode of control | Epistemic (knowledge stewardship) | Operational and managerial |
| Type of change | Revision of commitments | Modification of implementation |
| Risk when absent | Drift of meaning | Execution failure |

Upstream and downstream are therefore complementary.  Execution without epistemic stewardship leads to drift.  Epistemic articulation without realization remains inert.

Coherent software evolution requires both.


## Where to go next

Proceed to the definiton of **[Software system](../software-system.md)**.

If preferred, proceed to **[The discipline](../index.md)** for the conception of Upstream Software Engineering as a distinct field of study, to **[Foundations](../../index.md)** for an overview of the normative core of the discipline, or to **[Guidebook home](../../../index.md)** for an overview of this guidebook.
