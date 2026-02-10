# Recurring Challenges

The characteristics described in the **[Problem Space](./problem-space.md)** define the environment in which software systems exist and evolve. Within this environment, a set of challenges arises repeatedly across organizations, domains, and technological contexts.

These challenges are not isolated incidents or the result of individual mistakes. They emerge as **systematic patterns** shaped by longevity, continuous change, organizational context, multiplicity of actors, shifting boundaries, and historical accumulation.

This page identifies and characterizes these recurring challenges. It remains **diagnostic**: it does not propose solutions, prescribe practices, or establish norms. Those concerns are addressed later by **Upstream Software Engineering** as a discipline and conveyed by this guidebook.



## Implicit and Unexamined Decisions

Many decisions that shape a software system are made implicitly, without being explicitly articulated, examined, or recorded. These include decisions about scope, boundaries, architectural assumptions, quality trade-offs, and acceptable forms of change.

Such decisions are often made under time pressure or as part of local problem solving. Once enacted, they become embedded in the system’s structure and behavior, even when they were never intended to be long-term commitments. Over time, these implicit decisions acquire normative force simply by having been made.

The challenge is not that decisions are made implicitly, but that their implicit nature makes them difficult to question, revisit, or reinterpret as context changes. As a result, later actors may inherit constraints without visibility into the assumptions that produced them.



## Loss of Intent and Rationale Over Time

As software systems evolve, the original intent behind decisions often becomes inaccessible. Design rationale, strategic motivations, and contextual assumptions may not be preserved, or may decay as individuals leave, documentation becomes outdated, or informal knowledge is lost.

Research on design rationale and architectural knowledge has long observed that the reasons why decisions were made are often more fragile than the decisions themselves ([Perry & Wolf, 1992](../resources/bibliography.md#perry-wolf-1992); [van der Ven et al., 2006](../resources/bibliography.md#van-der-ven-etal-2006)).  Over time, systems retain the consequences of decisions while losing access to the reasoning that justified them.

This loss of intent complicates later evolution. When rationale is unavailable, changes must be made without knowing which assumptions remain valid, which constraints were deliberate, and which were incidental. The challenge is therefore not merely one of missing documentation, but of diminished interpretability of the system’s current state.



## Fragmented Understanding of the Software System

In long-lived and multi-actor environments, understanding of a software system is typically fragmented. Knowledge is distributed across people, teams, tools, documents, and codebases, with no single, stable point of synthesis.

Studies of large-scale and distributed development show that work is often partitioned across organizational and geographical boundaries, leading to partial and localized views of the system ([Herbsleb & Mockus, 2003](../resources/bibliography.md#herbsleb-mockus-2003)). As actors change over time, these fragments are recombined imperfectly, if at all.

Fragmented understanding is not necessarily a failure of coordination or competence. It is a structural consequence of the problem space. However, it limits the ability to reason about the system as a whole, particularly when making decisions that span components, teams, or organizational boundaries.



## Misalignment Between Intent and Realization

Over time, software systems may diverge from their original intent, even when they continue to function and deliver value. Strategic goals, architectural principles, or quality objectives articulated at one point in time may no longer be reflected in the system’s realized form.

This misalignment often emerges incrementally, through a sequence of locally rational changes made under evolving constraints. No single modification may appear problematic in isolation, yet their cumulative effect can lead to a system whose structure and behavior no longer correspond to its stated or assumed intent.

The challenge here is not that systems change, but that changes occur without a clear basis for assessing whether the resulting system remains consistent with its intended role, scope, or constraints. This sets the stage for later questions of validity, without yet answering them.



## Difficulty Governing Change

In environments characterized by continuous evolution, organizations often struggle to govern change effectively. Governance mechanisms may focus on process compliance, approval workflows, or control structures, without providing clear criteria for evaluating the *substance* of proposed changes.

As a result, it becomes difficult to determine which changes are acceptable, which are risky, and which undermine previously established intent. Decisions may be deferred, escalated, or justified retrospectively, rather than assessed against explicit and shared criteria.

This difficulty is not primarily procedural. It reflects the absence of a stable, explicit basis for reasoning about change in relation to the system’s evolving purpose, constraints, and context.



## Limited Ability to Revisit and Re-evaluate Decisions

Once decisions are embedded in a software system, they are often treated as irreversible. Revisiting past decisions may be perceived as costly, risky, or outside the scope of ongoing work.

However, the inability to reconsider decisions is itself a recurring challenge. As context changes, assumptions that were once valid may no longer hold. Without structured means to re-evaluate earlier decisions, systems accumulate constraints that are no longer justified but remain operative.

This limitation concerns **capability**, not intent. Even when organizations recognize the need to revisit decisions, they may lack the conceptual structures required to do so in a disciplined and non-disruptive way.



## Summary: Patterns of Recurring Challenges

Across diverse contexts, the problem space described in the previous page gives rise to a recurring set of challenges:

- decisions that are implicit rather than explicit,
- loss of original intent and rationale over time,
- fragmented and partial understanding of the system,
- divergence between intent and realized structure,
- difficulty assessing and governing change,
- limited ability to revisit and re-evaluate past decisions.

These challenges are not anomalies or isolated failures. They are structural patterns that emerge from the conditions under which software systems exist and evolve.

They motivate the need for a discipline capable of addressing upstream concerns explicitly. The next page examines why many existing approaches struggle to respond to these challenges.

## Where to go next

The next page, **[Limits of Current Approaches](./limits-of-current-approaches.md)**, analyzes why established methods, practices, and frameworks often fall short when confronted with these recurring challenges.