# Methodologies and process frameworks

Methodologies and process frameworks constitute a family of approaches primarily concerned with organizing and improving how software work is performed.  They define roles, routines, coordination mechanisms, feedback cycles, and technical practices that shape day-to-day execution.

Representative examples of this family include [Scrum](https://scrumguides.org/), [Extreme Programming (XP)](http://www.extremeprogramming.org/), Lean Software Development (Poppendieck & Poppendieck, 2003), [Kanban](https://kanban.university/), [LeSS](https://less.works/), and scaled variants such as [SAFe](https://scaledagileframework.com/) and [Disciplined Agile](https://www.pmi.org/disciplined-agile).  While differing in structure and scope, these approaches share a common focus on governing how work is carried out.

In relation to the upstream problem space described in the **[Problem Space](../problem-space.md)** and articulated through the **[Recurring Challenges](../recurring-challenges.md)**, methodologies are especially relevant because they directly influence the mechanisms through which change is enacted (see [Bennett & Rajlich, 2000](../../resources/bibliography.md#bennett-rajlich-2000); [Fitzgerald & Stol, 2017](../../resources/bibliography.md#fitzgerald-stol-2017)).


## Characteristic orientation

Approaches in this family are primarily oriented toward improving coordination, adaptability, and delivery effectiveness.  Their central concern is the organization of work: how tasks are sequenced, how teams interact, how feedback is incorporated, and how decisions are made in the course of execution.

They typically assume that effective governance emerges from disciplined practice and structured interaction.  For example, Scrum emphasizes iterative planning and inspection through defined events and roles, while XP embeds governance in technical discipline through practices such as pair programming and continuous integration.

Scaled frameworks such as SAFe, LeSS, and Disciplined Agile introduce additional layers of coordination across teams and portfolios.  While they extend governance beyond the team level, their primary structuring mechanisms remain centered on execution planning, synchronization, and delivery flow.

Across these variations, governance is largely embedded in workflow structures and team practices rather than in explicit, inspectable knowledge representations about long-term structural coherence or durable articulation of system intent.


## Governance mode emphasis

Analyzed through the governance–knowledge lens, methodologies and process frameworks predominantly emphasize **operational governance**.

In Scrum, XP, and Kanban, constraints and expectations are embedded in daily routines, defined roles, iteration cycles, and technical practices.  Governance is enacted through habitualized practice and team discipline.  Decision-making authority is often distributed and situational, occurring within bounded events such as sprint planning or retrospectives.

Scaled frameworks introduce stronger elements of **managerial governance**, particularly in coordinating multiple teams, aligning roadmaps, synchronizing releases, and structuring portfolio-level flow.  Authority becomes more formalized through defined roles, planning cadences, and coordination forums.

However, governance within this family remains primarily oriented toward managing execution rather than toward systematic stewardship of shared knowledge assets.  While artifacts such as backlogs, increment definitions, and roadmaps are explicit, they function mainly as coordination instruments rather than as durable, inspectable representations of architectural or intentional knowledge.


## Primary knowledge object governed

The primary knowledge object governed by methodologies and process frameworks is **execution**.

These approaches explicitly regulate how work is performed: iteration length, work-in-progress limits, refinement practices, review cycles, and feedback incorporation.  They structure behavior and coordination in order to improve responsiveness, flow, and delivery reliability.

Structural concerns may be addressed indirectly.  For example, XP promotes refactoring and design simplicity, and Scrum encourages emergent design within iterations.  However, structural knowledge is typically governed implicitly through technical discipline rather than through dedicated architectural knowledge frameworks ([Perry & Wolf, 1992](../../resources/bibliography.md#perry-wolf-1992)).

Intentional knowledge—such as long-term purpose, explicit non-goals, durable articulation of assumptions, or preservation of guiding constraints—is generally expressed in lightweight artifacts such as product visions or roadmap statements.  These serve planning and alignment purposes but are not typically treated as governable knowledge assets in an epistemic sense.


## Resulting governance configuration

Taken together, methodologies and process frameworks tend to cluster around the following governance configurations within the governance–knowledge matrix:

- **Operational × Execution** — governance embedded in daily practice and routines governing how work is performed.
- **Managerial × Execution** — governance enacted through coordination and planning structures, particularly in scaled or enterprise-level variants.

Occasional movement toward **Operational × Structural** may occur through design practices and refactoring discipline.  However, structural and intentional knowledge are not typically the primary objects of governance within this family.

This configuration reflects a strong emphasis on regulating activity and improving execution effectiveness, with limited systematic focus on explicit structural or intentional knowledge governance.


## Relationship to the upstream problem space

Methodologies and process frameworks directly address challenges related to coordination of work, responsiveness to change, and iterative delivery ([Fitzgerald & Stol, 2017](../../resources/bibliography.md#fitzgerald-stol-2017)).  They provide mechanisms for managing variability in execution and for incorporating feedback into ongoing development cycles.

However, challenges related to durable articulation of system intent, explicit governance of assumptions over time, and preservation of long-term coherence across organizational or provider boundaries are not systematically addressed within this family ([Bennett & Rajlich, 2000](../../resources/bibliography.md#bennett-rajlich-2000); [Lehman & Ramil, 2003](../../resources/bibliography.md#lehman-ramil-2003)).

This observation does not reflect a deficiency of these approaches within their intended scope.  Rather, it indicates that their dominant orientation lies in governing execution, while other dimensions of the upstream problem space fall outside their primary focus.


## Transition

This analysis provides a structured basis for comparison with other families of approaches.  The following pages apply the same governance–knowledge lens to additional categories, enabling systematic comparison across governance modes and knowledge objects.