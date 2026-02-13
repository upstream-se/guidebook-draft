# 1970s — Complexity era

By the late 1960s, the central problem of Software Engineering had shifted.  The issue was no longer merely *how to produce programs*, but how to manage their growing complexity.  Systems were expanding in size, teams were increasing, and coordination failures were becoming visible.

The “software crisis” narrative articulated at the 1968 NATO Conference (see [Bauer, 1968](../../../resources/bibliography.md#bauer-1968)) reflected this shift: software projects were late, over budget, and difficult to maintain.  The foregrounded problem was **complexity and loss of control**.

In response, the discipline began to search for structural and procedural order.


## What problem was foregrounded?

The dominant concern of this era was **complexity management**:

- Systems were becoming too large to comprehend as single units.
- Interdependencies were implicit and fragile.
- Late-stage integration failures were common.
- Maintenance costs were rising.

The problem was no longer only production failure, but **structural instability and lifecycle unpredictability**.


## What became governable?

Two major domains became explicitly governable:

1. **Structure through modularization.**  
   Parnas (1972) introduced information hiding as a principled way to decompose systems (see [Parnas, 1972](../../../resources/bibliography.md#parnas-1972)).  Modules were no longer merely technical partitions; they became governance instruments for controlling change.

2. **Process through lifecycle control.**  
   Royce (1970) articulated a staged lifecycle model that made development phases explicit and sequentially organized (see [Royce, 1970](../../../resources/bibliography.md#royce-1970)).  Even though later caricatured as “waterfall,” its deeper contribution was the institutionalization of staged governance.

Modularity and lifecycle modeling transformed software from an undifferentiated artifact into something that could be **partitioned and administratively controlled**.


## What governance mode dominated?

This era was characterized primarily by **Managerial × Structural governance**.

- Structural decomposition became explicit and deliberate.
- Lifecycle stages introduced formal coordination checkpoints.
- Responsibility boundaries were institutionalized.

Governance was no longer primarily embedded in coding practice; it became **organizationally structured**.

Socio-technical awareness also deepened during this period.  Conway (1968) demonstrated that system structure mirrors communication structure (see [Conway, 1968](../../../resources/bibliography.md#conway-1968)), making organizational design part of structural governance.  Brooks (1975) emphasized conceptual integrity and communication limits (see [Brooks, 1975](../../../resources/bibliography.md#brooks-1975)), and Dijkstra (1974) argued for disciplined reasoning and separation of concerns (see [Dijkstra, 1974](../../../resources/bibliography.md#dijkstra-1974)).

The discipline was learning that structure and organization are inseparable.


## What durable lesson was extracted?

The durable insight of this era is:

> **Complexity must be governed structurally and procedurally, not merely executed competently.**

Modularity is not only a design convenience; it is a governance mechanism for isolating change ([Parnas, 1972](../../../resources/bibliography.md#parnas-1972)).  
Lifecycle structure is not merely documentation; it is an institutional scaffold for coordination ([Royce, 1970](../../../resources/bibliography.md#royce-1970)).

Software engineering became concerned not just with *writing programs*, but with **organizing systems and the processes that produce them**.


## What remained structurally under-governed?

Despite these advances, an important dimension remained under-articulated:

- **System-level intent** was assumed rather than explicitly governed.
- Architectural rationale was rarely preserved as durable knowledge.
- Purpose and long-term commitments were not institutionalized as revisitable artifacts.

Structure was governed.  Process was governed.  Intent remained largely implicit.

This asymmetry would persist across subsequent eras and ultimately motivate the upstream perspective.


## Where to go next

Continue the historical analysis in **[1980s — Paradigm era](./1980s-paradigm-era.md)**.

If preferred, return to:

- **[Underlying rationale](./index.md)**
- **[Discipline](../index.md)**
- **[Foundations](../../index.md)**
- **[Guidebook home](../../../index.md)**
