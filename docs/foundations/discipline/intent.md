# Intent

> ⚠️ **This page is under active construction.**  
> The conceptual definition is stable. Refinement of wording and examples may continue.

A precise understanding of **intent** is central to Upstream Software Engineering.  Upstream governs intent.  It is therefore necessary to define what kind of knowledge object intent is, and how it differs from aspiration, preference, or description.


## Definition

> **Definition.**  Intent is the set of durable, revisable commitments about the scope and structure of a long-lived software system that normatively constrain its construction, operation, and evolution.

Intent is not a mood, ambition, or informal vision.  It is an articulated commitment that binds realization while remaining explicitly revisable through deliberate reconsideration.

Intent has two inseparable dimensions:

- **Scope-intent** — commitments concerning what the system is for, what obligations it assumes, what domain boundaries delimit it, and what non-goals define its limits.
- **Structure-intent** — commitments and constraints concerning how the system must be shaped, including architectural principles, structural boundaries, technology constraints, integration assumptions, deployment conditions, and automation strategies.

Together, these commitments form the normative core that governs system realization across time.


## What it is not

Intent is not:

- a list of requirements,
- a backlog of features,
- a product vision statement,
- an architectural diagram,
- a strategy document, or
- an implementation plan.

Requirements, designs, and plans may express or refine intent.  They do not constitute intent in themselves.

Intent is the binding layer of commitment that gives normative force to such artifacts.


## Core properties

For intent to be governable, it must exhibit the following properties:

- **Articulable** — it must be expressible in explicit form.
- **Inspectable** — it must be visible and reviewable.
- **Durable** — it must persist beyond initiatives and personnel changes.
- **Revisable** — it must be explicitly reconsiderable when contextual conditions change.
- **Normative** — it must constrain realization rather than merely describe it.

Durability does not imply immutability.  Revisability does not imply informality.  Intent remains binding while valid, and explicitly revisable when no longer justified.


## Intent across time

Long-lived software systems endure across projects, iterations, technological shifts, provider transitions, and organizational restructurings.  Intent persists across these discontinuities.

When intent remains implicit, coherence erodes gradually.  When intent is treated as immutable, rigidity emerges.  When intent is revised without explicit articulation, governance dissolves into drift.

The health of a long-lived system depends on maintaining intent as an explicit and consciously revisable commitment.


## Relation to other concepts

Intent is borne by a **software system** and justified relative to **context**.

- A software system is the enduring socio-technical entity whose commitments persist.
- Context provides the conditions that justify or challenge those commitments.

The interplay between context and intent explains how and why commitments must evolve.


## Where to go next

Continue to **[Context](./context.md)** for the definition of the environment within which commitments are justified.

Proceed to **[The discipline](./index.md)** for the conceptual structure of Upstream Software Engineering, to **[Foundations](../index.md)** for the normative framework of the guidebook, or to **[Guidebook](../../index.md)** for the complete structure of the guidebook.
